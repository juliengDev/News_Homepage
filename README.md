# News Homepage Website

![Design preview for the News homepage coding challenge](./design/desktop-preview.jpg)

## Overview

The site is a **news homepage** focused on topics like **Web 3.0**, **technology trends**, and **gaming**. It features a **clean, modern design** with a focus on **usability and responsiveness**.

🔍 **Key Features:**
- **Semantic HTML5 Structure** for better accessibility & SEO  
- **Responsive Design** with adaptive layouts  
- **Accessible Navigation** with ARIA attributes  
- **Dynamic Content Display** for an engaging user experience  
- **Mobile-friendly Burger Menu** for seamless navigation  

---

## ♿️ Accessibility Focus

Ensuring an inclusive and accessible experience:  
- **Semantic Elements** for logical document structure  
- **ARIA Attributes** for better screen reader support  
  - `aria-expanded` and `aria-hidden` for the mobile menu state  
  - `aria-label` and `aria-labelledby` for better navigation context  
- **Keyboard Navigation** with intuitive focus management  
- **Screen Reader Support** with hidden but accessible content  

---

## 🏗 Handling Responsive Navigation with the Burger Menu

The mobile navigation is managed through an **accessible burger menu**:

1. **Checkbox Input**: A hidden `<input type="checkbox">` toggles visibility  
2. **ARIA States**:  
   - `aria-expanded` updates dynamically  
   - `aria-controls` links the button to the menu  
3. **CSS Styling**:  
   - Sidebar (`<aside>`) is off-screen by default  
   - Media queries ensure proper display on different devices  
4. **Progressive Enhancement**: Works even if JavaScript is disabled  

This ensures a **fully responsive and accessible** navigation experience.

---

## 🛠 Built With

- **TypeScript** for type safety and maintainability  
- **Semantic HTML5** for structured content  
- **SCSS (BEM methodology)** for organized styling  
- **Mobile-first Workflow** for optimal responsiveness  
- **ARIA Attributes** for better accessibility  
- **Real-time Form Validation** for a seamless user experience  
- **Toast Notification System** for instant user feedback  

---

## 🚀 Live Demo

🔗 [News Homepage](https://juliengdev-news-hompage.netlify.app/)

---

## 📦 Installation

To set up the project locally, follow these steps:

1. **Clone the repository**  
   ```bash
   git clone https://github.com/juliengDev/news-homepage.git
   cd news-homepage

2. **Install dependencies**  
   ```bash
   npm install

3. **Start the development server**
   ```bash
   npm run dev

4. **Build for production**
   ```bash
   npm run build

5. **Preview the production build**
   ```bash
   npm run preview
---

## 📚 Useful Resources

- 📌 GitHub Repository: [News Homepage](https://github.com/juliengDev/news-homepage)  
- 🎥 [Create a Responsive Burger Menu](https://www.youtube.com/watch?v=dAIVbLrAb_U) - How to build an animated hamburger menu with only CSS  
- 📖 [WAI-ARIA Practices](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Accessibility/WAI-ARIA_basics) - Essential patterns for accessible web components  
- 🌍 [W3C Web Accessibility Initiative (WAI)](https://www.w3.org/WAI/) - Best practices for creating accessible web content  

---

## 👨‍💻 Author

- 🌐 **Portfolio** - [Julien Gilbert](https://juliengilbert.com/)  
- 🏆 **GitHub** - [@juliengDev](https://github.com/juliengDev)  
- 💼 **LinkedIn** - [Julien Gilbert](https://www.linkedin.com/in/julien-gilbert-reactjs/)  

---

🎯 *Feel free to reach out if you have any feedback or questions!* 🚀