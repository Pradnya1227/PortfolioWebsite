# Pradnya Wakode — Portfolio Website

A multi-page portfolio website with a dark wine theme, showcasing projects, skills, and experience.

## 📁 Files Included

- `index.html` — Homepage with hero, stats, skills preview, and featured project
- `about.html` — About page with education, certifications, interests, and full skills
- `projects.html` — Detailed project showcase with Problem → Approach → Result breakdowns
- `contact.html` — Contact page with form and availability info
- `style.css` — Complete stylesheet for all pages
- `script.js` — JavaScript for animations and interactions

## 🚀 Setup Instructions

1. **Add Your Resume**
   - Place your resume PDF in the same folder
   - Name it: `Pradnya_Wakode_-_Resume.pdf`
   - Or update all references in the HTML files to match your filename

2. **Update Project Links**
   - In `projects.html`, update the GitHub repository URLs:
     - `/pinterest-visual-board` → your actual repo name
     - `/image-recommender` → your actual repo name
     - `/dsa` → your actual repo name

3. **Optional: Update Images**
   - Replace placeholder Unsplash images with your own project screenshots
   - Just change the `src` attributes in the `<img>` tags

## 🎨 Features

### Design
- Dark wine color scheme (#6B1A2B, #C9A96E gold accents)
- Grain texture overlay for depth
- Smooth scroll animations
- Responsive layout (mobile-friendly)
- Custom hover states throughout

### Pages

**Home (index.html)**
- Hero section with typing animation
- Stats showcase (95% SSC, GDGC, 2027)
- Skills preview
- Featured project highlight
- CTA section

**About (about.html)**
- Personal story
- Beyond the code interests (art, Kathak, puzzles, reading)
- Education timeline
- Certifications
- Live GitHub contribution graph
- Full technical skills

**Projects (projects.html)**
- 3 detailed project showcases
- Problem → Approach → Result format
- Project images and overlays
- GitHub and live demo links
- "Coming soon" teaser section

**Contact (contact.html)**
- Contact form (frontend only — see note below)
- Email, LinkedIn, GitHub cards
- Availability info
- Resume download section

### Animations
- Scroll-triggered fade-up reveals
- Typing animation for hero role
- Active nav highlighting on scroll
- Smooth page transitions

## 📝 Customization Tips

### Colors
All colors are defined in CSS variables at the top of `style.css`:
```css
:root {
  --wine: #6B1A2B;
  --gold: #C9A96E;
  --cream: #F4EDE4;
  /* ... etc */
}
```
Change these to update the entire color scheme.

### Fonts
Current fonts (loaded from Google Fonts):
- **Playfair Display** — Headings
- **Syne** — Body text
- **JetBrains Mono** — Code/technical text

To change: update the `<link>` tag in each HTML file's `<head>`.

### Contact Form
The form currently shows a success message but **doesn't actually send emails**. 

To make it functional:
1. Set up a backend endpoint (e.g., using Formspree, EmailJS, or your own server)
2. Update the JavaScript in `script.js` where it says "In production..."
3. Uncomment the fetch() example and add your endpoint URL

Or use a service like:
- **Formspree**: https://formspree.io/
- **EmailJS**: https://www.emailjs.com/
- **Netlify Forms**: Built-in if hosting on Netlify

## 🌐 Deployment

### Option 1: GitHub Pages (Free)
1. Create a new GitHub repository
2. Upload all files (keep the same structure)
3. Go to Settings → Pages
4. Select "Deploy from a branch" → main branch
5. Your site will be live at `https://YOUR_USERNAME.github.io/REPO_NAME/`

### Option 2: Netlify (Free, Recommended)
1. Drag and drop the entire folder to https://app.netlify.com/drop
2. Done! You get a free URL instantly
3. Optional: Connect to GitHub for automatic updates

### Option 3: Vercel (Free)
1. Sign up at https://vercel.com
2. Import your GitHub repository
3. Deploy automatically

## ✅ Final Checklist

Before publishing:
- [ ] Add your resume PDF (`Pradnya_Wakode_-_Resume.pdf`)
- [ ] Update project GitHub URLs in `projects.html`
- [ ] Test all navigation links
- [ ] Check mobile responsiveness
- [ ] Replace placeholder project images (optional)
- [ ] Set up contact form backend (optional)
- [ ] Test in different browsers

## 💡 Tips

- The GitHub contribution graph loads from `github.com/Pradnya1227` — it will show your real activity
- The typing animation cycles through: Visual-First Developer, Cloud Enthusiast, UI/UX Designer, ML Explorer, Kathak Dancer, Problem Solver
- All external links open in new tabs automatically
- The site works 100% offline (no external dependencies except fonts and GitHub chart)

## 🎯 Your Info Already Included

✅ Email: pradnyawakode2712@gmail.com
✅ LinkedIn: linkedin.com/in/pradnya-wakode
✅ GitHub: github.com/Pradnya1227
✅ Education: PCCOE Pune, Graduating 2027
✅ GDGC Cloud Team Executive
✅ Google Cloud Study Jams 2024
✅ 95% SSC, 79% HSC

---

Built with care for Pradnya Wakode · 2025
