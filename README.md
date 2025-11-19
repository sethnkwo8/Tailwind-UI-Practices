# Tailwind UI Practice

A collection of reusable UI components and full website pages built with Tailwind CSS.
This project is for practicing responsive design, layout structure, and component-based UI building.

## 📁 Project Structure

- `components/` – individual UI elements like cards, pricing, navbar, etc.
- `UIs/` – full UI pages such as landing page, dashboard, and auth pages.
- `output.css` – compiled Tailwind stylesheet (DO NOT EDIT).
- `input.css` – Main Tailwind input file (imports tailwind).

---

## 🚀 Technologies
- HTML
- Tailwind CSS (v4 or CLI)
- Ionicons (icons)

---

## 🛠️ Setup & Development

### 1. Install TailwindCSS (no config for v4)
```bash
npm install -D tailwindcss
```
### 2. Build Tailwind (watch mode)

Run this ONCE at the project root:
```bash
npx tailwindcss -i ./input.css -o ./output.css --watch
```

This will:
 - Scan all HTML files (components, UIs, pages)
 - Generate a single output.css
 - Rebuild automatically whenever you change HTML or CSS

## 📁 Linking Tailwind in Your HTML

Each component/UI page should include:
```html
<link rel="stylesheet" href="../../output.css">
```
(Adjust path depending on folder depth)

## ✨ Custom Utilities
You can add your custom classes in input.css using Tailwind’s utility system, for example:
```css
@import "tailwindcss";

@utility features-card {
  @apply shadow-md w-full md:w-64 lg:w-72 p-8 rounded-lg flex flex-col;
}

@utility pricing-card {
  @apply w-64 h-96 rounded-xl shadow-lg hover:shadow-2xl hover:scale-105 transition-all;
}
```

## 🔥 Components Included
- Navbar  
- Hero Section  
- Card  
- Testimonial cards
- Statistics sections
- Pricing cards
- Contact Form  
- Features Grid  
- FAQ  
- Buttons

## 🖥 Full UIs Included
- Landing Page  
- Dashboard UI  
- Authentication Pack Pages (Login Page, Sign Up Page, Forgot Password Page, Reset Password Page, Verify Email)

## 📌 Purpose
- Improve Tailwind CSS fundamentals  
- Practice responsive UI design  
- Build a portfolio-ready collection of components  
- Prepare for React component architecture 

## 🤝🏿 Contributing
Feel free to fork, improve components, or add new UI pages.
Pull requests are welcome!

## 📜 License
MIT License
