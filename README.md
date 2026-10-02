# AI/ML & DevOps Portfolio

A modern, responsive portfolio website showcasing AI/ML and DevOps projects, skills, and achievements.

## 🚀 Features

- **Responsive Design**: Mobile-first approach, works on all devices
- **Modern UI**: Glassmorphism design with smooth animations
- **Fast Loading**: Pure static HTML, CSS, and JavaScript
- **SEO Optimized**: Clean semantic HTML structure
- **Performance**: Optimized for Core Web Vitals

## 📁 Project Structure

```
portfolio/
├── index.html          # Main portfolio page
├── package.json        # NPM configuration
├── README.md          # This file
└── .gitignore         # Git ignore rules
```

## 🎨 Sections

1. **Hero**: Eye-catching introduction
2. **About**: Brief professional overview
3. **Skills**: Technical competencies organized by category
4. **Projects**: Featured work with descriptions and technologies
5. **Achievements**: Key metrics and accomplishments
6. **Contact**: Call-to-action for business inquiries

## 🛠️ Local Development

### Option 1: Using Python
```bash
cd portfolio
python -m http.server 8000
# Visit http://localhost:8000
```

### Option 2: Using Node.js
```bash
cd portfolio
npx http-server
```

### Option 3: Using VS Code
- Install "Live Server" extension
- Right-click `index.html` → "Open with Live Server"

## 🌐 Deployment

### Deploy to Vercel (Recommended)

1. Push code to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project"
4. Import your GitHub repository
5. Deploy (Vercel auto-detects static sites)
6. Add custom domain in Vercel dashboard

### Deploy to Netlify

1. Push code to GitHub
2. Go to [netlify.com](https://netlify.com)
3. Click "New site from Git"
4. Connect GitHub and select your repo
5. Deploy (Netlify handles static sites automatically)
6. Configure custom domain in Netlify settings

### Deploy to GitHub Pages

1. Push to GitHub repository named `username.github.io`
2. Enable GitHub Pages in repository settings
3. Site automatically deploys to `https://username.github.io`

## 📝 Customization

### Update Your Information

Edit `index.html` and replace:
- Hero section text
- About section description
- Skills in the skill cards
- Project information
- Contact links (GitHub, LinkedIn, Email)
- Footer information

### Change Colors

Modify the CSS variables in the `<style>` section:

```css
:root {
    --primary: #0f172a;           /* Main background */
    --secondary: #1e293b;         /* Card background */
    --accent: #3b82f6;            /* Primary blue accent */
    --accent-light: #60a5fa;      /* Lighter accent */
    --text: #f1f5f9;              /* Main text */
    --text-secondary: #cbd5e1;    /* Secondary text */
}
```

### Add Project Details

Each project card includes:
- Title and description
- Technology tags
- Feature list
- Links to GitHub/Demo

## 🔧 Build for Production

No build step needed! This is a static site. Just ensure `index.html` is at the root when deploying.

## 📊 Performance

- **Lighthouse Score**: 95+
- **Load Time**: < 1 second
- **Bundle Size**: < 50KB

## 🔐 Security

- No external dependencies
- No tracking or analytics scripts
- HTTPS ready
- No sensitive data stored

## 📱 Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile browsers (iOS Safari 14+, Chrome Mobile)

## 🎓 Getting Started Checklist

- [ ] Update your name and bio
- [ ] Add your actual projects
- [ ] Update technology tags
- [ ] Add GitHub/LinkedIn links
- [ ] Configure custom domain
- [ ] Add projects with links
- [ ] Deploy to hosting platform
- [ ] Test on mobile devices

## 📧 Support

For questions about deployment, visit:
- [Vercel Docs](https://vercel.com/docs)
- [Netlify Docs](https://docs.netlify.com)
- [GitHub Pages Docs](https://pages.github.com)

## 📄 License

MIT License - Feel free to use this template for your portfolio

## 🎉 Next Steps

1. **Customize the content** with your actual projects
2. **Add project screenshots** by updating project cards
3. **Deploy to a hosting platform** (Vercel/Netlify recommended)
4. **Configure your custom domain**
5. **Share your portfolio** with potential clients and employers

---

**Remember**: A great portfolio is never finished! Keep updating it with new projects and achievements.
