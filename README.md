# Alex Dev — Portfolio Site

A personal portfolio website built as part of the **TaskFlow Full-Stack Internship** (Task 1).

## 📁 File Structure

```
portfolio-site/
├── index.html       # Home page (hero, projects, skills)
├── about.html       # About page (bio, timeline, stack)
├── contact.html     # Contact page (form + social links)
├── styles/
│   └── main.css     # Global styles (design tokens, components, responsive)
├── images/          # Image assets
└── README.md        # This file
```

## ✅ Features

- **3 Pages** — Home, About, Contact with consistent navigation
- **Responsive Design** — Mobile-first layout using CSS Grid & Flexbox
  - Mobile (≤768px): Stacked layout, hamburger menu
  - Desktop (>768px): Multi-column sections
- **Modern CSS** — CSS custom properties (design tokens), hover effects, transitions
- **No frameworks** — Pure HTML5 + CSS3 + vanilla JS

## 🚀 Deployment

### Option 1: GitHub Pages
```bash
git init
git add .
git commit -m "Initial portfolio"
git remote add origin https://github.com/username/portfolio-site.git
git push -u origin main
```
Then: **Settings → Pages → Source: main / (root)**

Live at: `https://username.github.io/portfolio-site`

### Option 2: Netlify
Drag and drop the project folder to [netlify.com/drop](https://app.netlify.com/drop)

## 🛠 Design Choices

- **Dark theme** with a purple accent (`#7c6afc`) — high contrast, easy on the eyes
- **Syne** (display) + **Inter** (body) font pairing for a modern, technical feel
- **Glassmorphism navbar** — fixed, blurred background for depth
- **Skill bars** with gradient fills to show proficiency levels

## 📋 Skills Validated (Task 1 Checklist)

| Skill | Evidence |
|-------|----------|
| HTML5 Semantics | `<nav>`, `<section>`, `<footer>`, semantic structure |
| CSS Flexbox/Grid | `.projects-grid`, `.about-grid`, `.skills-grid` |
| Media Queries | Mobile breakpoint at 768px, hamburger menu |
| Git Basics | Commit history in repository |
| Deployment | Live URL via GitHub Pages / Netlify |
