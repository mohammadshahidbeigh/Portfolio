# 🚀 Harnoor Singh - Portfolio

A bold, modern portfolio website built with NeoBrutalism design principles.

## 🎨 Design Features

- **NeoBrutalism Style**: Bold borders, bright contrasting colors, hard shadows
- **Responsive Design**: Looks great on all devices
- **Smooth Animations**: Scroll effects and hover interactions
- **Clean Code**: Semantic HTML, modular CSS, vanilla JavaScript

## 💡 Why Vanilla JavaScript?

This portfolio intentionally uses plain HTML, CSS, and JavaScript instead of modern frameworks like React or TypeScript. Here's why:

### Performance First
- **Zero build time**: No compilation, bundling, or transpilation needed
- **No framework overhead**: The entire site loads in milliseconds with no runtime dependencies
- **Smaller bundle size**: ~30KB total vs 100KB+ for even minimal React apps
- **Instant page loads**: No hydration delays or JavaScript parsing bottlenecks

### Simplicity & Maintainability
- **Easy to understand**: Anyone can read and modify the code without learning a framework
- **No build tooling**: No webpack, Vite, or complex build configurations to maintain
- **Future-proof**: Will work in browsers 10 years from now without dependency updates
- **Lower barrier to entry**: Easy for others to fork and customize

### Right Tool for the Job
- **Static content**: A portfolio is mostly static text and images - no complex state management needed
- **Minimal interactivity**: Smooth scrolling and hover effects don't require React's virtual DOM
- **SEO-friendly**: Pure HTML with no client-side rendering concerns
- **No over-engineering**: Using React for a portfolio would be like using a sledgehammer to crack a nut

### Learning & Teaching
- **Back to basics**: Demonstrates mastery of web fundamentals
- **Teaching tool**: Great reference for learning core web technologies
- **No magic**: Every line of code is explicit and visible

**When you should use frameworks:**
- Complex state management across many components
- Real-time data synchronization
- Large team collaboration with TypeScript type safety
- Apps with hundreds of interactive components

For a personal portfolio, vanilla JavaScript delivers the best user experience with the lowest complexity.

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── style.css           # NeoBrutalism styles
├── script.js           # Interactive JavaScript
└── README.md          # This file
```

## 🚀 Deployment Options for hsinghplay.usa.dev

### Option 1: Cloudflare Pages (RECOMMENDED - FREE)

Cloudflare Pages is perfect since your domain is already on Cloudflare!

**Steps:**
1. **Create a GitHub repository** for your portfolio
   ```bash
   cd portfolio
   git init
   git add .
   git commit -m "Initial portfolio commit"
   git branch -M main
   git remote add origin https://github.com/iharnoor/portfolio.git
   git push -u origin main
   ```

2. **Connect to Cloudflare Pages**
   - Go to Cloudflare Dashboard → Pages
   - Click "Create a project"
   - Connect your GitHub account
   - Select your portfolio repository
   - Build settings:
     - Framework preset: None
     - Build command: (leave empty)
     - Build output directory: `/`
   - Click "Save and Deploy"

3. **Add Custom Domain**
   - In Cloudflare Pages → Your project → Custom domains
   - Click "Set up a custom domain"
   - Enter: `hsinghplay.usa.dev`
   - Cloudflare will automatically configure DNS
   - ✅ Done! Your site will be live in minutes

**Benefits:**
- ✅ Free forever
- ✅ Automatic HTTPS
- ✅ Global CDN (super fast)
- ✅ Automatic deployments from Git
- ✅ Unlimited bandwidth
- ✅ Built-in analytics

---

### Option 2: GitHub Pages (FREE)

**Steps:**
1. Create a repo named `iharnoor.github.io` or any name
2. Push your portfolio files
3. Go to Settings → Pages
4. Source: Deploy from branch `main`
5. Custom domain: `hsinghplay.usa.dev`
6. Add CNAME record in Cloudflare DNS:
   ```
   CNAME  @  iharnoor.github.io
   ```

**Benefits:**
- ✅ Free
- ✅ Easy to use
- ✅ Automatic HTTPS
- ⚠️ Limited to 100GB bandwidth/month

---

### Option 3: Vercel (FREE)

**Steps:**
1. Push code to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Import your repository
4. Add custom domain: `hsinghplay.usa.dev`
5. Update Cloudflare DNS with Vercel's nameservers

**Benefits:**
- ✅ Free for personal projects
- ✅ Instant deployments
- ✅ Edge network
- ✅ Great developer experience

---

### Option 4: Netlify (FREE)

**Steps:**
1. Push code to GitHub
2. Go to [netlify.com](https://netlify.com)
3. "Add new site" → Import from Git
4. Deploy settings: None needed
5. Add custom domain in Site settings

**Benefits:**
- ✅ Free tier generous
- ✅ Form handling
- ✅ Serverless functions

---

## 🎯 Quick Start (Local Development)

1. **Open the portfolio locally:**
   ```bash
   cd portfolio
   open index.html
   # or for a local server:
   python3 -m http.server 8000
   # Then visit: http://localhost:8000
   ```

2. **Edit content:**
   - Update `index.html` for content changes
   - Modify `style.css` for styling
   - Customize `script.js` for interactions

3. **Customize:**
   - Replace `email@example.com` with your real email
   - Update YouTube link if needed
   - Add more projects or sections as desired

## 🔧 Customization Guide

### Change Colors
Edit CSS variables in `style.css`:
```css
:root {
    --color-primary: #FFD700;    /* Yellow */
    --color-secondary: #00D4FF;  /* Cyan */
    --color-accent: #FF006E;     /* Pink */
}
```

### Add New Sections
Follow the existing HTML structure and add matching CSS classes.

### Update Content
All content is in `index.html` - simply edit the text within the HTML tags.

## 📦 Production Checklist

Before deploying:
- [ ] Update email address
- [ ] Verify all links work
- [ ] Test on mobile devices
- [ ] Check all images load
- [ ] Test smooth scrolling
- [ ] Verify responsiveness
- [ ] Add favicon (optional)
- [ ] Add meta tags for SEO (optional)

## 🌟 Features to Add (Optional)

- Blog section
- Project showcase with screenshots
- Dark mode toggle
- Contact form
- Google Analytics
- Social media meta tags (Open Graph)

## 📝 License

Feel free to use this portfolio as a template for your own site!

---

Built with ❤️ and NeoBrutalism ⚡
