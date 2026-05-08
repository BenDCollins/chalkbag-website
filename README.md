# 🧗 Chalkbag — The Internet's Climbing Catalog

> A multi-page mock website for a fictional rock climbing resource company, built from scratch as a web development and UX/UI design practice project.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 📌 Project Overview

Chalkbag is a fictional rock climbing hub designed to serve climbers of all skill levels — from first-timers to elite athletes. The site aggregates curated video lessons, unbiased gear recommendations, a community newsletter sign-up, and a contact portal.

This project was built entirely by hand as a front-end development and UX/UI design exercise. No frameworks, no templates, no generators — just semantic HTML, organized CSS, and a touch of vanilla JavaScript.

---

## 🗂️ Site Structure

```
Chalkbag/
├── index.html                  # Home page
├── lessons.html                # Curated video tutorials & grade charts
├── supplies.html               # Gear & clothing recommendations
├── newsletter.html             # Newsletter sign-up form
├── contact.html                # Contact form
├── contact-submission.html     # Post-contact confirmation page
├── newsletter-submission.html  # Post-newsletter confirmation page
│
├── styles/
│   ├── main.css                # Global styles, nav, layout, responsive breakpoints
│   ├── lessons.css             # Lesson page layout (iframe grid, aside nav)
│   ├── supplies.css            # Supplies page layout (product grid)
│   ├── newsletter.css          # Newsletter form styles
│   ├── contact.css             # Contact form styles
│   ├── form-submission.css     # Confirmation page styles
│   └── print.css               # Print stylesheet
│
├── js/
│   └── home-button.js          # Handles "Join the Community" CTA button redirect
│
└── images/                     # All photography assets (gear, climbers, products)
```

---

## 📄 Pages

**Home (`index.html`)** — Brand introduction, value proposition, and a CTA button that routes users to the newsletter sign-up.

**Lessons (`lessons.html`)** — 18 curated YouTube videos organized into Beginner, Intermediate, and Advanced sections. Includes a sticky sidebar nav and two detailed climbing grade conversion charts (V-Scale/Font for bouldering, YDS/French for sport climbing).

**Supplies (`supplies.html`)** — Gear and clothing recommendations across four categories: Shoes, Chalk, Gear, and Clothing. Each item links to its Amazon product page and is clearly labeled as commission-free and unendorsed.

**Newsletter (`newsletter.html`)** — A detailed sign-up form with contact info fields, experience level radio buttons, topic interest checkboxes, a message textarea, and a referral source dropdown.

**Contact (`contact.html`)** — A contact form capturing name, email, phone, message, and reason for inquiry (feedback, business, sponsorship, etc.).

---

## 🎨 Design Decisions

**Color palette** — Deep purple-to-black gradient background (`#24004a` → black) with white text and a burnt orange hover accent (`#d15a00`). The palette evokes the grit and atmosphere of outdoor climbing.

**Layout** — Sidebar navigation on multi-content pages (Lessons, Supplies) for in-page anchor jumping. Images float right to wrap text naturally. Flexbox powers the main nav and page structure.

**Responsive design** — A `max-width: 768px` media query collapses the header, stacks the nav vertically, and hides decorative images and the aside on smaller screens for a clean mobile experience.

**Print stylesheet** — A dedicated `print.css` removes navigation and decorative elements for clean, readable printed output.

**Semantic HTML** — Proper use of `<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<aside>`, `<footer>`, and `<figure>` throughout. Forms use `<fieldset>` and `<legend>` for accessibility grouping.

---

## ⚙️ Technical Highlights

- **Vanilla JS** — A single `home-button.js` file handles the "Join The Community!" CTA using `addEventListener` and `window.location.href`, keeping the script lightweight and purposeful.
- **No dependencies** — Zero external libraries, frameworks, or build tools. Runs in any browser by opening `index.html`.
- **Embedded media** — YouTube iframes use `referrerpolicy`, `allowfullscreen`, and descriptive `title` attributes for security and accessibility compliance.
- **Form UX** — Both forms include `required` validation, logical tab order, descriptive labels, and placeholder text. Post-submission confirmation pages provide clear user feedback.
- **Viewport meta tag** — Included on all pages for proper mobile rendering.

---

## 🚀 Running Locally

```bash
# Clone the repository
git clone https://github.com/BenDCollins/chalkbag.git
cd chalkbag

# Open in browser
open index.html
# or drag index.html into any browser window
```

No build step, no server required.

---

## 🧠 What I Practiced

- Multi-page site architecture and internal linking
- CSS layout with Flexbox and float-based image positioning
- Responsive design with media queries
- HTML form construction (radio, checkbox, select, textarea, fieldset)
- Accessible, semantic HTML structure
- Separation of concerns across multiple CSS files
- Print stylesheet design
- Embedding and attributing third-party media (YouTube iframes)
- Vanilla JavaScript DOM event handling

---

## 🧑‍💻 Author

**Ben Collins**
Digital Arts @ UNC Wilmington | Minor in Computer Science | UX/UI Design Focus

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-blue?style=flat-square)](https://github.com/BenDCollins/chalkbag-website)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/bencollins49/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat-square&logo=github)](https://github.com/BenDCollins)

---

> *Chalkbag is a fictional company created for educational purposes. All product links and embedded videos belong to their respective owners.*
