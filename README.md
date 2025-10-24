<h1 align="center">🌐 Dynamic Animated Landing Page</h1>

<p align="center">
  <img src="https://i.pinimg.com/1200x/c0/7a/d4/c07ad492ace4479ca1a5c152c64e7c64.jpg" width="100%" style="border-radius:15px; box-shadow:0 4px 20px rgba(0,0,0,0.2)">
</p>

<p align="center">
  <b>A modern, fully responsive, and animated landing page built using pure HTML, CSS, and JavaScript.</b><br>
  <b>Task Submission for CA Program – Techfest, IIT Bombay</b><br>
  <b>CA ID:</b> CA-071501592586
</p>

---

## 🧠 Project Overview

This landing page is designed to showcase **interactive design principles** using only **HTML, CSS, and JavaScript** — without any external frameworks.  
It includes:
- A responsive navigation bar  
- Animated hero section  
- About and features section  
- Contact form with validation  
- Smooth transitions and scroll animations  

The project focuses on **accessibility**, **modern UI design**, and **performance**.

---

## 🧩 Tech Stack Used (As in the Webpage)

| Technology | Purpose |
|-------------|----------|
| **HTML5** | Page structure and content |
| **CSS3** | Styling, layout, transitions, and animations |
| **JavaScript (ES6)** | Interactivity, validation, and dynamic behavior |
| **Google Fonts** | Typography styling |
| **Responsive Design Techniques** | Flexbox, Media Queries |
| **Intersection Observer API** | Scroll-triggered animations |

---

## ✨ Features

### 🌈 Modern User Interface
- Clean layout with smooth gradients  
- Neat typography and color contrasts for readability  
- CSS variables (`--primary-color`, `--accent-color`) for easy theme control  

### 📱 Fully Responsive Design
- Adapts to all screen sizes: mobile, tablet, and desktop  
- Navigation menu converts into a hamburger icon on small screens  

### 💫 Smooth Animations
- Scroll-based fade-in and slide-up animations  
- CSS transitions for button hover and image scaling effects  

### 📬 Contact Form
- JavaScript-based input validation  
- Animated submit button and success alert  

### ⚡ Performance Optimized
- Lightweight code (no frameworks)  
- Image compression and minimal CSS nesting  

---

## 🧠 Code Explanation (Section by Section)

### 🏗️ 1. HTML Structure

The **HTML** provides a semantic layout divided into meaningful sections:

```html
<header>
  <nav>
    <h1>Techfest Landing</h1>
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#features">Features</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>
</header>

<section id="hero">
  <h2>Welcome to Techfest</h2>
  <p>Experience innovation and creativity together.</p>
  <button>Explore More</button>
</section>
