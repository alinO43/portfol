# 🚀 Deployment Guide

## ✅ Pre-Deployment Checklist

- [x] Git repository initialized
- [x] All 144 files staged and committed
- [x] .gitignore configured
- [x] README.md created with setup instructions
- [x] Production-ready code (no debug logs, no console errors)
- [x] All images optimized and in place (103 files)
- [x] Responsive design tested (mobile, tablet, desktop)
- [x] CSS classes migrated (563 inline styles → reusable classes)

## 📤 Push to GitHub

```bash
cd "путь/до/портфолио"

# Add remote repository
git remote add origin https://github.com/your-username/portfolio.git

# Push to GitHub
git branch -M main
git push -u origin main
```

## 🌐 Deploy to GitHub Pages

1. Go to repository Settings
2. Scroll to "Pages" section
3. Under "Build and deployment"
4. Select "Deploy from a branch"
5. Choose branch: **main**
6. Select folder: **/ (root)**
7. Save

Site will be live at: `https://your-username.github.io/portfolio`

## 🔗 Deploy to Vercel

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy from project directory
vercel

# Answer prompts:
# - Link to existing project? No
# - Set up new project? Yes
# - Project name: portfolio
# - Framework: Other
```

Site will be live at: `https://portfolio-{id}.vercel.app`

## 📋 What's Included

### Pages
- `index.html` - Main portfolio page with all case studies
- `autobrief-case.html` - AutoBrief B2B SaaS project
- `company-profile-case.html` - Company Profile verification service
- `landing-case.html` - Find Analytics landing page
- `lms-itam-case.html` - LMS ITAM educational platform

### Assets
- `styles.css` - 37 reusable CSS classes
- `support.js` - Design system runtime & interactivity
- `screens/` - 103 optimized project images
- `assets/` - Icons, logos, and additional resources

### Documentation
- `README.md` - Setup and overview
- `CSS_REFACTORING_FIXES.md` - CSS migration details
- `CSS_REFACTOR_REPORT.md` - Original refactoring report
- `MIGRATION_REPORT.md` - Style migration statistics

## 🔄 After Deployment

1. **Test live site**: Click all links, check responsive design
2. **Monitor with**: Google Analytics, Sentry, or similar
3. **Update DNS**: Point custom domain if needed
4. **Share links**: 
   - GitHub repo link
   - Live site URL
   - Resume/CV link (if applicable)

## 🛠️ Local Development

```bash
# Option 1: Python
python3 -m http.server 8000

# Option 2: Node.js
npx serve .

# Option 3: Live Server
# Use VS Code extension "Live Server"
```

Then visit: `http://localhost:8000`

## 📝 Version History

**v1.0** (Current)
- 4 complete case studies
- Full responsive design
- Production-ready code
- Ready for deployment

## ❓ FAQ

**Q: Can I add more case studies?**
A: Yes. Create `{project-name}-case.html` and link from index.html

**Q: How do I update text?**
A: Edit HTML files directly. Use `styles.css` for styles.

**Q: What if I want to change colors?**
A: Update color values in `.style` attributes or add new CSS classes in `styles.css`

**Q: Can I use analytics?**
A: Yes. Add Google Analytics or similar tracking scripts to `<head>` tags.

---

**Ready to deploy? Your portfolio is production-ready! 🎉**
