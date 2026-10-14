# Personal Portfolio Website — HTML5 & CSS3 Internship Project

A high-performance personal developer portfolio built strictly using **semantic HTML5** and **modern CSS3**, with zero external frameworks, libraries, or JavaScript.

---

## 📋 Project Description (Ready for Submission Form)

> **Portfolio Summary (3–5 Sentences):**  
> Built as an internship showcase, this personal portfolio introduces Prashant Mittal, an aspiring frontend developer, highlighting academic credentials, technical proficiencies, and featured projects. The website is engineered with strict semantic HTML5 landmarks and modern CSS3, incorporating CSS custom properties, responsive Flexbox, and CSS Grid layouts. It delivers an accessible, high-contrast visual experience optimized across mobile, tablet, and desktop viewports without relying on JavaScript or external CSS frameworks.

---

## 🚀 Key Features & Highlights

1. **Strict HTML5 & CSS3 Compliance**:
   - Zero JavaScript, React, Bootstrap, or TailwindCSS dependencies.
   - 100% compliant with the project constraints and guidelines.
2. **Semantic HTML5 Architecture**:
   - Organized landmark tags: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, and `<footer>`.
   - Descriptive heading hierarchies (`<h1>` through `<h4>`), ARIA accessibility attributes, and descriptive image `alt` texts.
3. **Modern CSS3 Design System**:
   - Tokenized CSS variables (`:root`) for color palette, elevations, typography, and spacing scales.
   - Smooth scrolling (`scroll-behavior: smooth`) with CSS scroll margin anchors (`scroll-padding-top`).
   - Ambient glow backdrops and card elevation micro-animations.
4. **Pure CSS Responsive Navigation**:
   - Desktop flex navigation with animated active underline indicators.
   - Pure CSS mobile drawer and animated hamburger toggle using the checkbox hack (no JavaScript needed).
5. **7 Required Portfolio Sections**:
   - **Header / Navigation**: Branding logo (`<Prashant Mittal/>`), navigation links (`#home`, `#about`, `#skills`, `#projects`, `#contact`), and quick CTA button.
   - **Hero / Home**: Availability status pill with pulsing indicator, bold headline, role summary, key academic statistics, developer avatar, and call-to-action buttons.
   - **About Me**: 3-card grid covering personal biography, degree education details, and career interests.
   - **Skills**: 9 technical skills categorized into *Core Web Standards*, *Layouts & Styling*, and *Tools & Best Practices* with skill level badges.
   - **Projects**: 3 featured projects (*EduTrack Dashboard*, *EcoPulse Sustainability Portal*, *DevReads Technical Library*) with mockups, descriptions, tech tags, and interactive links.
   - **Contact**: Direct email (`prashantmittal0091@gmail.com`), GitHub profile (`github.com/Prashantmittal0091`), and an accessible contact form with a visual demo disclaimer.
   - **Footer**: Copyright line, quick links, and a smooth back-to-top button.

---

## 📁 Project Folder Structure

```text
HTML/
│
├── index.html                   # Semantic HTML5 document
├── style.css                    # Dedicated CSS3 stylesheet with design tokens
├── README.md                    # Project documentation & submission notes
│
├── images/                      # Optimized image assets
│   ├── profile.jpg              # Professional 3D developer avatar
│   ├── project-dashboard.jpg    # EduTrack Dashboard project preview
│   ├── project-ecopulse.jpg     # EcoPulse Environmental Portal preview
│   └── project-devreads.jpg     # DevReads Technical Library preview
│
└── screenshots/                 # Submission proof
    ├── desktop.png              # Desktop viewport screenshot (1440x900)
    └── mobile.png               # Mobile viewport screenshot (390x844)
```

---

## 🛠️ How to View Locally

### Option 1: Direct File Opening
Double click `index.html` or right click and choose **Open with** &rarr; **Google Chrome** / **Microsoft Edge**.

### Option 2: Local HTTP Server (Python)
Run the following command in terminal:
```bash
python -m http.server 5500
```
Then navigate to:
```text
http://localhost:5500
```

---

## ✅ Submission Checklist Verification

- [x] **Valid HTML5 Structure**: `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`, meta charset utf-8, meta viewport.
- [x] **Semantic Tags**: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`.
- [x] **Section IDs**: `#home`, `#about`, `#skills`, `#projects`, `#contact` all jump correctly.
- [x] **Separate CSS**: All styling is placed in `style.css`.
- [x] **CSS Variables**: Main colors, gradients, fonts, and shadows are tokenized in `:root`.
- [x] **Flexbox & CSS Grid**: Used extensively for navigation, hero, about grid, skills, and project cards.
- [x] **Responsive Media Queries**: Screen tested at desktop (1440px), tablet (1024px), and mobile (390px).
- [x] **Hover and Focus States**: Complete interactive feedback on buttons, links, inputs, and cards.
- [x] **No Horizontal Overflow**: Verified on desktop, tablet, and mobile.
- [x] **Screenshots Captured**: `screenshots/desktop.png` and `screenshots/mobile.png` created and verified.
- [x] **Pure HTML & CSS Constraint**: Zero JavaScript or external frameworks used.
