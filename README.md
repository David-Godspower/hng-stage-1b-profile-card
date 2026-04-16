# HNG14 Stage 1B - Testable Profile Card

A clean, accessible, and high-fidelity Profile Card component built for the HNG14 Frontend Track. This project focuses on semantic HTML, responsive design, and precise time-handling logic.

## 🚀 Live Demo
- **Live URL:** [[LIVE LINK](https://hng-stage-1b-profile-card.vercel.app/)]

## 🛠️ Tech Stack
- **HTML5:** Semantic structure for SEO and accessibility.
- **Tailwind CSS:** Modern utility-first styling for a polished UI.
- **Vanilla JavaScript:** Efficient, zero-dependency logic for real-time updates.

## ✨ Key Features
- **Precise Epoch Clock:** Displays the current time in milliseconds (`Date.now()`), updating every 10ms to ensure 100% accuracy for automated tests.
- **Semantic Tags:** Utilizes `<article>`, `<figure>`, `<nav>`, and `<section>` to provide a clear document outline.
- **Accessibility (a11y):** - Optimized for keyboard navigation with visible focus rings.
  - WCAG AA compliant color contrast.
  - ARIA-live regions for dynamic time updates.
- **Responsive Layout:** Adaptive design that shifts from a vertical stack on mobile to a horizontal side-by-side layout on desktop.

## 📝 Decisions & Trade-offs
- **Vanilla JS over React:** To ensure a 100% lighthouse score and zero build-time overhead, I chose Vanilla JavaScript for this specific component.
- **High-Frequency Refresh:** I set the timer to a 10ms interval to provide a "live" feel and ensure that any automated testing bot captures a unique, valid timestamp.
- **SVG Social Icons:** Used inline SVGs for social links to ensure high-definition scaling and reduce external network requests.

## 📖 How to Run Locally
1. Clone the repository:
   ```bash
   git clone [https://github.com/ajaladavid/hng-stage-1b-profile.git](https://github.com/ajaladavid/hng-stage-1b-profile.git)
2. Open `index.html` in your browser.
3. No build steps required.


## Author
- **David Godspower Ajala**
- Computer Engineering Student, LAUTECH.
- HNG14 Internship - Frontend Track - Stage 1A