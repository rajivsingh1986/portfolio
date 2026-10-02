# Portfolio Customization Guide

## 📋 Quick Edit Checklist

This guide helps you customize the portfolio with your actual information.

---

## **1. Hero Section (First Thing Visitors See)**

Find this in `index.html`:

```html
<h1>AI & DevOps <span class="highlight">Engineering</span></h1>
<p>Building intelligent systems, automation frameworks, and scalable cloud infrastructure</p>
```

**Change to your headline:**
```html
<h1>Your Name<br><span class="highlight">Your Title</span></h1>
<p>Your professional tagline - 1-2 lines about what you do</p>
```

**Examples:**
- "Full-Stack AI Engineer" | "Cloud Architect" | "DevOps Specialist"

---

## **2. About Section**

Find and update:
```html
<p>I'm a full-stack AI/ML engineer and DevOps specialist...</p>
```

**Write 2-3 sentences about yourself:**
- Background & experience
- What you specialize in
- What makes you unique

---

## **3. Update Skills**

Find each skill card and update:

```html
<div class="skill-card">
    <h3>🤖 AI & Machine Learning</h3>
    <ul>
        <li>LLM Integration & RAG</li>
        <li>Multi-Agent Systems</li>
        <!-- Update these -->
    </ul>
</div>
```

**Your Skill Categories Might Be:**
- Languages (Python, Go, TypeScript, etc.)
- Cloud (AWS, Azure, GCP)
- Databases (PostgreSQL, MongoDB, etc.)
- Tools (Docker, Kubernetes, Git, etc.)

---

## **4. Add Your Projects**

This is the most important section! Update each project card:

```html
<div class="project-card">
    <div class="project-header">
        <h3>Your Project Name</h3>
        <p>One-line description of what it does</p>
        <div class="project-tags">
            <span class="tag">Technology1</span>
            <span class="tag">Technology2</span>
        </div>
    </div>
    <div class="project-body">
        <ul class="project-features">
            <li>What you built</li>
            <li>Key feature</li>
            <li>Another feature</li>
        </ul>
        <div class="project-links">
            <a href="https://github.com/link">GitHub →</a>
        </div>
    </div>
</div>
```

**For Each Project, Include:**
- ✅ Project name
- ✅ What problem it solves
- ✅ Technologies used
- ✅ 3-4 key features/accomplishments
- ✅ Links (GitHub, live demo)

**Project Examples from Your Workspace:**

1. **Multi-Agent AI System**
   - Tools: CrewAI, LangChain, Python
   - Focus: Agent coordination, autonomous task execution

2. **Infrastructure Automation**
   - Tools: Ansible, Terraform, Azure/AWS
   - Focus: Enterprise deployment, configuration management

3. **AI-Powered Business Intelligence**
   - Tools: Python, FastAPI, Power BI
   - Focus: Data pipeline, analytics dashboards

---

## **5. Update Contact Links**

Find the contact section:

```html
<div class="contact-links">
    <a href="https://github.com" target="_blank">GitHub</a>
    <a href="https://linkedin.com" target="_blank">LinkedIn</a>
    <a href="mailto:contact@example.com">Email</a>
    <a href="#">Resume</a>
</div>
```

**Replace with your actual links:**
```html
<a href="https://github.com/YOUR_USERNAME" target="_blank">GitHub</a>
<a href="https://linkedin.com/in/YOUR_PROFILE" target="_blank">LinkedIn</a>
<a href="mailto:your.email@example.com">Email</a>
<a href="https://example.com/resume.pdf">Resume</a>
```

---

## **6. Update Footer**

Find:
```html
<p>&copy; 2024 AI/ML & DevOps Engineer. All rights reserved. | Crafted with ❤️</p>
```

Change to:
```html
<p>&copy; 2024 Your Name. All rights reserved. | Crafted with ❤️</p>
```

---

## **7. Change Colors (Optional)**

The portfolio uses a blue/green color scheme. To customize:

Find the CSS section at the top of `index.html`:

```css
:root {
    --primary: #0f172a;           /* Dark background */
    --accent: #3b82f6;            /* Bright blue - change this */
    --accent-light: #60a5fa;      /* Lighter blue - change this */
}
```

**Color Options:**
- Blue: `#3b82f6` (current)
- Purple: `#8b5cf6`
- Green: `#10b981`
- Orange: `#f59e0b`
- Red: `#ef4444`
- Teal: `#14b8a6`

[Color picker](https://htmlcolorcodes.com) - pick your color, copy the hex code

---

## **8. Update Logo/Branding**

Find:
```html
<div class="logo">CODE.AI</div>
```

Change to your name or brand:
```html
<div class="logo">Your Name</div>
```

---

## **Testing Your Changes**

### Local Preview
```bash
cd portfolio
# Windows
python -m http.server 8000

# Or use VS Code Live Server
# Right-click index.html → Open with Live Server
```

Then open: `http://localhost:8000`

### Mobile Test
- Use Chrome DevTools (F12) → Toggle device toolbar
- Or visit on your phone if running locally
- Check: text readable, buttons clickable, layout responsive

### Link Verification
- Click every link to verify it works
- External links should open in new tab (target="_blank")

---

## **Common Mistakes to Avoid**

❌ **Don't:**
- Leave placeholder text in ("contact@example.com")
- Have broken links
- Use inconsistent formatting
- Make descriptions too long (keep it concise)
- Have typos in project descriptions

✅ **Do:**
- Use your real contact information
- Make every link work
- Use consistent capitalization
- Be specific about achievements
- Proof-read everything

---

## **Content Tips for More Impact**

### Project Descriptions

❌ Bad: "Built a project with Python"

✅ Good: "Developed multi-agent coordination system using CrewAI that reduced manual task processing by 70%"

### About Section

❌ Bad: "I know Python and cloud stuff"

✅ Good: "Full-stack engineer with 5+ years building AI systems and cloud infrastructure, specializing in LLM integration and enterprise automation"

### Achievements

❌ Bad: "20+ projects"

✅ Good: "20+ production systems deployed | $2M+ infrastructure managed | 95% customer satisfaction"

---

## **Recommended Edits Order**

1. ✅ Update hero headline and tagline
2. ✅ Update about section
3. ✅ Update 6 project cards with YOUR projects
4. ✅ Update skills section
5. ✅ Update contact links
6. ✅ Update achievements numbers
7. ✅ Update footer
8. ✅ Test on mobile
9. ✅ Verify all links work
10. ✅ Deploy!

---

## **Adding More Projects**

To add a 7th project, duplicate this code after the 6th project:

```html
<div class="project-card">
    <div class="project-header">
        <h3>Project Name</h3>
        <p>Description</p>
        <div class="project-tags">
            <span class="tag">Tech1</span>
            <span class="tag">Tech2</span>
        </div>
    </div>
    <div class="project-body">
        <ul class="project-features">
            <li>Feature 1</li>
            <li>Feature 2</li>
            <li>Feature 3</li>
        </ul>
        <div class="project-links">
            <a href="https://github.com/...">GitHub →</a>
        </div>
    </div>
</div>
```

The grid will auto-arrange!

---

## **Getting Help**

- **HTML Questions**: [MDN Web Docs](https://developer.mozilla.org)
- **Color Picker**: [htmlcolorcodes.com](https://htmlcolorcodes.com)
- **Image Compression**: [tinypng.com](https://tinypng.com)
- **Emoji Reference**: [emojipedia.org](https://emojipedia.org)

---

**You're ready to customize! 🚀**

Edit, test locally, deploy, and start getting business inquiries!
