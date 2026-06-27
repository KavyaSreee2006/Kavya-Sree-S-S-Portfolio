# Kavya Sree S S - Personal Portfolio Website

A premium, modern, and fully responsive single-page portfolio website built to showcase my academic history, software engineering projects, internship experience, and professional certifications. 

This website is built with clean, semantic **HTML5**, modern **CSS3** (incorporating glassmorphism, fluid responsive layouts, and interactive micro-animations), and vanilla **JavaScript** for interactions.

## 🚀 Live Demo & Local Preview

You can open the site locally in your default web browser by double-clicking:
👉 **[index.html](./index.html)**

---

## 🎨 Key Features

*   **🌓 Dark & Light Modes**: Includes a floating theme toggle with smooth CSS color transitions. The system automatically remembers user theme preferences using `localStorage`.
*   **✍️ Dynamic Typewriter Effect**: Highlights primary technical roles (*Full Stack Developer*, *CSE Student*, *IoT Enthusiast*, *Problem Solver*) dynamically in the Hero section.
*   **🔍 Interactive Projects Filter**: Allows visitors to filter project cards (All, Web, IoT) on the fly with smooth scaling transitions.
*   **📌 Active Navigation Scroll Observer**: Automatically highlights the active navigation menu item as the user scrolls through different sections.
*   **📱 Mobile Optimized**: A responsive glassmorphic navigation bar with a mobile drawer/hamburger menu.
*   **📧 Interactive Contact Form**: A functional contact form layout with input validation, visual loading states, and custom success banners.

---

## 📁 Project Structure

```text
portfolio/
├── assets/
│   └── avatar.jpg      # Profile photo (extracted from original resume PDF)
├── index.html          # Semantic HTML markup & SEO metadata
├── styles.css          # CSS custom variables, theme mappings, layout, & keyframes
├── script.js           # Navigation drawer, typewriter, project filter, & form validation
└── README.md           # Project documentation
```

---

## 🛠️ Tech Stack

*   **Structure**: HTML5 (Semantic elements)
*   **Styling**: CSS3 (CSS Variables, Flexbox, Grid, custom animations)
*   **Interactions**: Vanilla JavaScript (ES6)
*   **Icons**: Feather Icons (via CDN link)
*   **Typography**: Google Fonts (Plus Jakarta Sans & Fira Code)

---

## 💻 How to Run Locally

### Option 1: Direct File Launch
Double-click `index.html` in your file explorer to open the site directly in any modern browser.

### Option 2: Live Server (VS Code Extension)
1. Open the `portfolio` directory in VS Code.
2. Click **Go Live** in the bottom right corner (requires the *Live Server* extension).

### Option 3: Python local server
If you have Python installed, open your terminal inside the folder and run:
```bash
python -m http.server 8000
```
Then navigate to `http://localhost:8000` in your web browser.

---

## 🌐 Free Deployment (Hosting)

Since this is a static website (HTML/CSS/JS), it can be hosted for free in under two minutes:

### 1. Netlify (Drag & Drop)
1. Visit [Netlify Drop](https://app.netlify.com/drop).
2. Drag the entire `portfolio` folder and drop it into the upload box.
3. Your site will instantly go live with a custom shareable link!

### 2. GitHub Pages
1. Push this folder to a new repository on your GitHub account (e.g., named `portfolio`).
2. Go to **Settings** > **Pages** inside the repository.
3. Under **Build and deployment**, set the source branch to `main` (or `master`) and folder to `/ (root)`.
4. Save, and within a minute your site will be live at `https://<username>.github.io/portfolio/`.

---

## 🔧 Personalization & Customization

*   **Change Accent Colors**: Open `styles.css` and modify variables under `:root` (for Dark mode) and `[data-theme="light"]` (for Light mode):
    ```css
    --primary-color: #38bdf8; /* Change this hex code to modify the main accent */
    --accent-color: #c084fc;  /* Change this to modify the secondary/typewriter color */
    ```
*   **Update Projects**: Search for `<div class="project-card card" ...>` in `index.html` to add or edit project descriptions, technology tags, and links.
*   **Update Profile Image**: Replace `assets/avatar.jpg` with your own profile headshot.
