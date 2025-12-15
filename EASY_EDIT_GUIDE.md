# Easy Website Update Guide 🎯

Welcome! This guide will help you update your professional website without any technical knowledge. Think of it like editing a document on Google Docs, but for your website.

---

## How to Edit Your Website

### Option 1: Edit Files Directly on GitHub (Easiest)

1. **Go to your GitHub repository**
   - Open your web browser and go to: `https://github.com/Ashley-L-8/Ashley-L-8.github.io`
   - Sign in to your GitHub account

2. **Find the file you want to edit**
   - Look for the file names listed below
   - Click on the file name to open it

3. **Click the Edit Button**
   - Look for a **pencil icon** ✏️ in the top right corner of the file
   - Click it to start editing

4. **Make your changes**
   - Find the text you want to change
   - Delete the old text and type in the new text
   - It's just like editing in Word!

5. **Save your changes**
   - Scroll to the bottom of the page
   - Click the green **"Commit changes"** button
   - A small popup will appear - just click **"Commit changes"** again
   - Your website will automatically update in a few seconds!

---

## Which Files to Edit?

### 📄 `index.html` - Your Home Page

**Find this section:**
```
Welcome to my professional portfolio. I am a driven individual...
```

**Replace it with:** Your own introduction (2-3 sentences about yourself)

**Find this section:**
```
Professional Title / Expertise
```

**Replace it with:** Your actual job title or main expertise

---

### 📄 `experience.html` - Your Work History

**Find this section:**
```
2023 - Present
Current Job Title
Company Name, Location
```

**Replace with:**
- Your actual job dates
- Your actual job title
- Company name and location

**Do this for each job you want to add.**

**For Education, find:**
```
Graduation Year
Degree Name
University/College Name
```

**Replace with your actual education.**

**For Skills, find:**
```
<span style="background: #ecf0f1; padding: 8px 15px; border-radius: 5px;">Skill 1</span>
```

**To add a skill, copy this line and change "Skill 1" to your actual skill.**

---

### 📄 `projects.html` - Show Your Work

**Find this section:**
```
Project Name One
A brief description of the project...
```

**Replace with:**
- Your actual project name
- Your description of what you did
- Change the tags (words in colored boxes) to describe your project

**Copy this entire section to add more projects.**

---

## Update Your Contact Info

**In all files** (index.html, experience.html, projects.html), find:

```
<a href="mailto:your.email@example.com"><i class="fas fa-envelope"></i></a>
```

**Replace** `your.email@example.com` with your actual email address.

The LinkedIn link is already set to your profile - no changes needed there!

---

## Need to Add More Content?

### Adding More Job Experiences
In `experience.html`, find a job section and copy the entire block:
```
<div class="timeline-item">
    <div class="timeline-date">2023 - Present</div>
    <h3 class="timeline-role">Current Job Title</h3>
    <div class="timeline-company">Company Name, Location</div>
    <p>
        Description here.
    </p>
</div>
```

Paste it again and update the dates, title, and description.

### Adding More Projects
In `projects.html`, find a project card and copy the entire block:
```
<div class="project-card">
    <div class="project-content">
        <h3 class="project-title">Project Name One</h3>
        <p>
            Description here.
        </p>
        <div class="project-tags">
            <span>Strategy</span>
        </div>
    </div>
</div>
```

Paste it again and update with your new project details.

---

## Design & Colors

**Want to change colors?** Open `style.css` and find the top section:

```
:root {
    --primary-color: #2c3e50;  (Dark blue)
    --secondary-color: #34495e;  (Medium blue)
    --accent-color: #c0392b;  (Red)
    --text-color: #333;  (Dark gray)
    --bg-color: #f9f9f9;  (Light gray)
}
```

You can change these color codes. (Look up "HTML color picker" online for easy color selection!)

**Common colors:**
- Navy Blue: `#2c3e50`
- Professional Gray: `#34495e`
- Red/Accent: `#c0392b`
- White: `#ffffff`
- Black: `#000000`

---

## Troubleshooting

### "My changes aren't showing up!"
- Wait a few seconds - the website updates automatically
- Refresh your browser (Ctrl+R or Cmd+R)
- If still not showing after 1 minute, check that you clicked "Commit changes"

### "I accidentally deleted something important!"
- Don't panic! GitHub keeps a history
- Go to the file, click the "History" tab, and click a previous version to restore it

### "I'm not sure what to change"
- Look for the text that matches what you see on your website
- That's the section you need to update

---

## Preview Your Changes

To see how your website looks:
1. Go to `https://ashley-l-8.github.io` (your live website)
2. Your changes appear automatically after a few seconds

---

## Getting Help

If you need help:
1. Go to your GitHub repository
2. Click **"Issues"** tab
3. Click **"New Issue"** and describe what you need help with
4. A developer can help you!

---

Good luck! Your website is ready to showcase your professional achievements! 🌟
