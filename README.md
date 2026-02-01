# 🚀 Portfolio Web

Creative web portfolio showcasing my web development projects, system architecture, and automation work.

## ✨ Features

- **Modern Design**: Dark gradient theme with smooth animations
- **Fully Responsive**: Mobile-first design that works on all devices
- **Interactive Elements**: Hover effects, smooth scrolling, and micro-interactions
- **Project Showcase**: Display your best work with detailed case studies
- **Tech Stack Badges**: Highlight your skills and technologies
- **Contact Section**: Direct links to WhatsApp, Email, and GitHub

## 📂 Folder Structure

```
portfolio-web/
├── index.html          # Main portfolio page (single file)
├── img/                # Project screenshots and images
│   └── .gitkeep
└── README.md           # Project documentation
```

## 🛠️ Tech Stack

- **HTML5**: Semantic markup
- **CSS3**: Custom properties, Flexbox, Grid
- **JavaScript**: Vanilla JS for interactions
- **No frameworks**: Pure HTML/CSS/JS for fast loading

## 🚀 Quick Start

### Option 1: Download & Open Locally

1. Clone or download this repository
2. Open `index.html` in your browser
3. Done! 🎉

### Option 2: Deploy to GitHub Pages

1. Go to **Settings** → **Pages**
2. Select **main** branch as source
3. Click **Save**
4. Your portfolio will be live at `https://mirul-Work.github.io/portfolio-web/`

### Option 3: Deploy to Hostinger/cPanel

1. Upload all files to your hosting `public_html` folder
2. Access via your domain

## 📝 Customization

### Update Personal Info

Edit `index.html` and update:
- **Name**: Search for "Mirul" and replace
- **Description**: Update hero section text
- **Projects**: Edit project cards with your own data
- **Contact**: Update WhatsApp number, email, GitHub links

### Add Project Images

1. Save screenshots in `img/` folder
2. Update `data-img` attributes in project cards:
   ```html
   data-img="img/your-project.png"
   ```

### Change Colors

Edit CSS variables in `<style>` section:
```css
:root {
  --bg: #050816;        /* Background color */
  --accent: #f59e0b;     /* Accent color */
  --text: #e5e7eb;       /* Text color */
}
```

## 🎨 Adding More Projects

Copy this template and paste in the `.projects-grid` section:

```html
<article class="project-card"
  data-title="Your Project Title"
  data-description="Detailed description of your project, what problem it solves, and the tech stack used."
  data-img="img/your-screenshot.png"
  data-link="https://your-project-url.com"
  data-tags="Laravel · Vue · MySQL">
  
  <div class="project-thumb">
    <strong>Project tagline</strong><br />
    Short description visible on card.
  </div>
  <div class="project-label">Client name · 2026</div>
  <div class="project-title">Your Project Title</div>
  <p class="project-copy">
    Brief description of the project for the card preview.
  </p>
  <div class="project-meta">
    <span class="project-chip">Tech 1</span>
    <span class="project-chip">Tech 2</span>
  </div>
  <div class="project-footer">
    <span>Goal: What was achieved</span>
    <a class="project-link" href="#" target="_blank">
      Case study <span>↗</span>
    </a>
  </div>
</article>
```

## 📱 Modal Feature

Click any project card to view:
- Full project description
- Screenshot/demo image
- Live project link
- Tech stack used

## 🌐 Live Demo

> Will be available after enabling GitHub Pages

## 📄 License

Free to use for personal portfolio. Feel free to customize and make it your own!

## 🤝 Credits

Designed & built by **Mirul** — Full-stack Developer from Terengganu, Malaysia.

---

**Questions?** Reach out via [GitHub Issues](https://github.com/mirul-Work/portfolio-web/issues) or WhatsApp!
