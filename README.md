# Biya Mary George — Personal Portfolio

A minimal, professional single-page portfolio built with pure HTML and CSS. Hosted on GitHub Pages.

**Live Demo:** `https://yourusername.github.io/portfolio` *(replace `yourusername` with your GitHub username)*

---

## Features

✅ Minimal, professional design  
✅ Professional typography (Inter font)  
✅ Fully responsive (mobile-first)  
✅ Single-page layout  
✅ Fast, no build tools needed  
✅ SEO-friendly  

---

## Deploy to GitHub Pages (5 minutes)

### Step 1: Create a GitHub Repository

1. Go to [github.com/new](https://github.com/new)
2. Repository name: `portfolio` (or any name you prefer)
3. Description: "My personal portfolio"
4. Choose **Public**
5. Click **Create repository**

### Step 2: Initialize Git & Push Files

In PowerShell/Terminal, navigate to your portfolio folder and run:

```powershell
cd c:\Users\USER\OneDrive\Documents\myprofile
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/yourusername/portfolio.git
git push -u origin main
```

Replace `yourusername` with your actual GitHub username.

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (top right)
3. Scroll to **Pages** (left sidebar)
4. Under "Build and deployment":
   - Source: Select **Deploy from a branch**
   - Branch: Select **main** and **/root** 
5. Click **Save**
6. Wait 1–2 minutes for the build to complete

### Step 4: View Your Live Portfolio

Your site is now live at:
```
https://yourusername.github.io/portfolio
```

---

## Customization

### Update Content

Edit `index.html` to fill in:
- **Projects:** Replace placeholder project cards with your actual projects
- **Skills:** Add/remove skill cards
- **Contact:** Update email and social links
- **About:** Refine your bio

### Change Colors

Edit `styles.css` color variables (top of file):

```css
:root {
    --primary-color: #1f2937;      /* Dark gray */
    --accent-color: #3b82f6;       /* Blue */
}
```

Try these color combinations:
- **Professional:** `#1f2937` (dark gray) + `#3b82f6` (blue)
- **Modern:** `#111827` (nearly black) + `#06b6d4` (cyan)
- **Warm:** `#7c3aed` (purple) + `#f97316` (orange)

### Change Fonts

Update the Google Fonts import in `index.html` (`<head>`):

```html
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;600;700&display=swap" rel="stylesheet">
```

[Browse Google Fonts](https://fonts.google.com) and copy the embed code.

---

## Project Structure

```
portfolio/
├── index.html           # Main portfolio page
├── styles.css           # All styling (minimal, professional)
├── README.md            # This file
└── .gitignore           # Git configuration
```

---

## Deployment Alternatives

**Want a different domain name?**

- **Custom Domain:** GitHub Pages supports custom domains (~$10–12/year)
  1. Buy domain from GoDaddy, Namecheap, or similar
  2. In GitHub Settings > Pages, add your domain name
  3. Follow GitHub's DNS instructions

- **Free Alternative Hosting:**
  - **Netlify:** Drag & drop deployment, auto-deploys from GitHub
  - **Vercel:** Optimized for static sites, fast CDN
  - **Cloudflare Pages:** Free, fast, unlimited sites

---

## Making Updates

After deployment, any changes to `index.html` or `styles.css` will auto-update:

1. Edit files locally
2. Commit & push to GitHub:
   ```powershell
   git add .
   git commit -m "Update portfolio content"
   git push
   ```
3. Wait 1–2 minutes, refresh your live site

---

## Support

- **GitHub Pages Help:** [docs.github.com/pages](https://docs.github.com/pages)
- **Google Fonts:** [fonts.google.com](https://fonts.google.com)
- **Markdown Guide:** [markdownguide.org](https://www.markdownguide.org)

---

**Your portfolio is ready to showcase your skills!** 🚀

