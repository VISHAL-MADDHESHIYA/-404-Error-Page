# Custom 404 Error Page - Web Development Track

**Task:** Level 1 - Day 30 (Task 30)
**Track:** Web Development (HTML5 & CSS3)

## 📌 Project Overview
This project is a modern, responsive, and highly professional Custom 404 Error Page. It includes a friendly message, a custom animated SVG illustration (lost satellite in space), and a fully functional Call-to-Action (CTA) button that redirects the user back to the homepage. 

To demonstrate the redirect functionality in a real-world scenario, a minimal, modern homepage (`index.html`) is also included.

## ✨ Features
- **Perfect Centering:** Utilizes CSS Grid (`place-items: center`) to perfectly center the content vertically and horizontally on the viewport.
- **Responsive Typography:** Uses CSS `clamp()` for fluid font sizing that looks stunning on mobile, tablet, and desktop without needing complex media queries.
- **Custom SVG Illustration:** A pure inline SVG of a lost satellite orbiting a planet. No external image URLs are used.
- **Smooth Animations:** CSS keyframes are used to create a subtle floating effect for the satellite and twinkling stars.
- **Interactive CTA:** The "Back to Homepage" button features smooth hover transitions, a slight lift effect, and internal icon animation.
- **Redirection:** Clicking the button successfully redirects the user from `404.html` to `index.html`.

## 🛠️ Technologies Used
- **HTML5:** Semantic tags (`<main>`, `<header>`, `<nav>`, `<section>`, `<footer>`).
- **CSS3:** Flexbox, CSS Grid, CSS Variables (Custom Properties), Keyframe Animations, Media Queries.
- **SVG:** Inline scalable vector graphics for the illustration.

## 📁 File Structure
```text
├── index.html       # Homepage (Redirect destination)
├── 404.html         # Custom Error Page
├── style.css        # Common stylesheet for both pages
└── README.md        # Project documentation