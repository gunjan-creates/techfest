# Dynamic & Animated Landing Page Submission

## 🌟 Project Overview

This project is a single-page, dynamic, and responsive landing page developed as a **Task Submission** for the **IIT Bombay Techfest Campus Ambassador (CA) Program**.

The design philosophy focuses on a modern, dark-themed aesthetic ("Dark Navy Blue" and "Bright Mint" accents) combined with engaging animations and robust, accessible JavaScript functionality.

## 🚀 Features

This single HTML file incorporates all three core technologies—HTML structure, CSS styling, and JavaScript interactivity—to deliver a polished user experience.

### 🎨 Design & Styling (CSS)

* **Modern Dark Theme:** Utilizes a custom color palette defined in CSS Root Variables (`:root`) for easy theme management.
    * `--primary-color`: Dark Navy Blue (`#0a192f`)
    * `--accent-color`: Bright Mint (`#64ffda`)
* **Sticky & Blur Header:** The navigation bar uses `position: sticky` and `backdrop-filter: blur(10px)` for a modern, semi-transparent effect.
* **Interactive Button Animation:** The submit button features a custom CSS `@keyframes pulse` animation to draw attention, which pauses on hover/focus.
* **Heading Decorator:** A small, animated line (`::after` pseudo-element) under the main section headings (`<h2>`) provides visual structure.

### 💻 Interactivity & Dynamics (JavaScript)

* **Responsive Navigation (Hamburger Menu):** A JavaScript-powered toggle to collapse and expand the navigation links on mobile devices (`@media (max-width: 768px)`). It also features a CSS-animated "X" transition on the toggle icon.
* **Scroll Fade-in Animation:** Implements the **Intersection Observer API** to detect when a section (`.hidden-section`) enters the viewport, triggering a smooth **fade-in and slide-up** transition.
* **Client-Side Form Validation:**
    * Checks for required fields (Name, Email, Message) and a valid email format.
    * Dynamically applies visual feedback (red borders, error messages) using the `.is-invalid` and `.is-visible` CSS classes.
    * Includes **Accessibility (ARIA)** attributes (`aria-invalid`, `aria-describedby`, `role="alert"`) for a better user experience with screen readers.
    * Displays a final status message (Success/Error) upon form submission attempt.

## 🛠️ Technologies Used

* **HTML5:** Semantic structure and content.
* **CSS3:** Styling, custom properties (`var()`), responsive design (`@media`), transitions, and `@keyframes` animations.
* **JavaScript (ES6+):** DOM manipulation, event handling, Intersection Observer API, and form validation logic.

## ⚙️ Setup & How to Run

Since the project is a single-file implementation using only front-end technologies, no server or build tools are required.

1.  **Save the Code:** Save the entire code block as a file named `index.html`.
2.  **Open in Browser:** Double-click the `index.html` file or drag it into any modern web browser (Chrome, Firefox, Edge, etc.).

## 🎯 CA Task Notes

This submission successfully demonstrates proficiency in:

1.  **Responsive Design:** The layout adjusts correctly for both desktop and mobile views, including a functional hamburger menu.
2.  **Modern CSS:** Effective use of custom properties (`var`), `backdrop-filter`, and complex animations (`@keyframes`, `transition`).
3.  **Advanced JavaScript:** Utilizes the non-traditional but highly performant **Intersection Observer API** for scroll-based animations, providing an efficient way to enhance the user experience.
