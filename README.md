# Portfolio Website

A personal portfolio site built with plain HTML and CSS — no frameworks, no build step, no JavaScript (the mobile nav menu uses a pure-CSS checkbox toggle).

🔗 **Live Demo:** [peroute.github.io/portfolio-website-class](https://peroute.github.io/portfolio-website-class/)

## 📁 Structure

```
portfolio-website-class/
├── index.html          # Home page: hero, about, skills, contact
├── projects.html        # Projects page: project cards
├── cv.html               # Online CV: education, experience, skills & languages
├── css/
│   └── style.css        # All styling for the site
├── images/
│   └── profile.jpg      # Profile photo (used in the hero avatar circle)
├── files/
│   └── CV.pdf            # Downloadable resume, linked from the nav and hero
└── README.md
```

## 📄 Pages

- **Home** (`index.html`) — hero section with photo + "View My Work" / "Download CV" buttons, About Me cards, Skills pills, and a Contact box.
- **Projects** (`projects.html`) — a stacked list of project cards, each with a title, date/context line, tech tags, and description highlights.
- **CV** (`cv.html`) — an on-site resume with a header (name + "Download PDF" button), Education/Experience timelines, and a Skills & Languages info grid.

## 🎨 Key CSS classes

- **Layout:** `.container`, `.section-heading`, `.alt-bg`
- **Header / nav:** `.site-header`, `.navbar`, `.logo`, `.nav-toggle` (+ `.nav-toggle-label`, checkbox hack, no JS), `.nav-links`
- **Buttons:** `.btn`, `.btn-primary`, `.btn-outline`
- **Home:** `.hero`, `.hero-inner`, `.avatar-circle`, `.hero-heading`, `.hero-tagline`, `.hero-actions`, `.about-grid` / `.about-card`, `.skills-grid` / `.skill-pill`, `.contact-box` / `.contact-links`
- **Projects:** `.projects-grid`, `.project-card`, `.project-body`, `.tag-list` / `.tag`, `.project-meta`, `.project-highlights`
- **CV:** `.cv-header`, `.cv-block`, `.timeline-item`, `.info-grid` / `.info-card`
- **Footer:** `.site-footer`, `.footer-links`, `.footer-copyright`

## ✏️ Customizing

- Edit page content directly in `index.html`, `projects.html`, or `cv.html`.
- All styling lives in `css/style.css`.
- Replace `images/profile.jpg` with your own photo — it's used as the background image of the hero `.avatar-circle`.
- Replace `files/CV.pdf` with your own resume — it's linked from the nav's CV page and the homepage's "Download CV" button.

## 🚀 Running locally

Just open `index.html` in your browser — no build step or dependencies required.
