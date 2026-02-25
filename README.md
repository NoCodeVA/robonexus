# RoboNexus — AI-Powered Robotics Website

A fully responsive, multi-page website about AI and robotics solutions across industries. Built with pure HTML, CSS, and JavaScript — no frameworks or dependencies required.

## 🚀 Live Demo (GitHub Pages)

> After deploying, your site will be live at:
> `https://<your-username>.github.io/<your-repo-name>/`

---

## 📁 File Structure

```
robonexus-website/
├── index.html          ← Homepage (start here)
├── solutions.html      ← Industry solutions
├── robots.html         ← Robot catalog
├── ai-tech.html        ← AI technology platform
├── education.html      ← Education programs
├── about.html          ← About & team
├── contact.html        ← Contact & demo request
├── assets/
│   ├── css/
│   │   └── style.css   ← All styles
│   └── js/
│       └── main.js     ← Interactivity & animations
└── README.md
```

---

## 🌐 Deploy to GitHub Pages

### Option 1 — Upload via GitHub UI (easiest)

1. Go to [github.com](https://github.com) and create a **new repository** (e.g. `robonexus-site`)
2. Click **"uploading an existing file"**
3. Drag and drop **all files and folders** from this zip (keep the folder structure intact)
4. Click **"Commit changes"**
5. Go to **Settings → Pages**
6. Under **Source**, select `Deploy from a branch`
7. Set branch to **`main`** and folder to **`/ (root)`**
8. Click **Save** — your site will be live in ~60 seconds

### Option 2 — Git CLI

```bash
# Unzip the download, then:
cd robonexus-website

git init
git add .
git commit -m "Initial commit — RoboNexus website"

# Create repo on GitHub first, then:
git remote add origin https://github.com/<your-username>/<your-repo>.git
git branch -M main
git push -u origin main

# Then enable GitHub Pages in repo Settings → Pages → main branch / root
```

---

## ✅ Pages Included

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Hero, industries, AI tech, stats, testimonials |
| Solutions | `solutions.html` | Manufacturing, Healthcare, Logistics, Agriculture, Construction, Energy |
| Our Robots | `robots.html` | Filterable catalog of 9 robots with full specs |
| AI Technology | `ai-tech.html` | NexusAI platform, architecture diagram, RoboSim |
| Education | `education.html` | K-12, University, Professional & Online programs |
| About | `about.html` | Mission, values, timeline, team, careers |
| Contact | `contact.html` | Demo request form, offices, FAQ |

---

## 🎨 Features

- **Fully responsive** — works on mobile, tablet, desktop, and Mac
- **Dark futuristic design** — purple/cyan accent palette with animated SVG robot
- **Animated particle system** and orbital ring effects on homepage
- **Scroll-triggered counter animations** on impact statistics
- **Intersection Observer** fade-in animations throughout
- **Hamburger navigation** for mobile with dropdown menus
- **Interactive contact form** with simulated submission feedback
- **FAQ accordion** on contact page
- **No external dependencies** — only Google Fonts CDN for typography

---

## 🛠 Customisation

- **Colors:** Edit CSS variables at the top of `assets/css/style.css` (`:root` block)
- **Content:** Edit text directly in each `.html` file
- **Images:** All images load from Unsplash CDN — replace `src` URLs with your own
- **Logo:** SVG logo is inline in the `<nav>` of each page — edit the SVG paths to customise

---

## 📋 Requirements

- No build step needed
- No Node.js or npm required
- Works in all modern browsers (Chrome, Firefox, Safari, Edge)
- Internet connection needed for Google Fonts and Unsplash images to load

---

*Built with HTML5, CSS3, and Vanilla JavaScript*
