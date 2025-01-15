# News homepage Website

![Design preview for the News homepage coding challenge](./design/desktop-preview.jpg)

## Overview

The site is a **news homepage** focused on topics like Web 3.0, technology trends, and gaming. It features a clean, modern design with a focus on usability and responsiveness. 

#### Key Code Features:
1. **Structure**: The site uses semantic HTML5 elements like `<header>`, `<main>`, `<section>`, `<footer>`, and `<nav>` to ensure proper document structure and better SEO.
2. **Responsive Design**: The layout adapts to different screen sizes using media queries and responsive images via the `<picture>` element.
3. **Accessibility**: ARIA roles and attributes (like `aria-expanded`, `aria-label`, and `aria-labelledby`) are used to improve accessibility for assistive technologies.
4. **Navigation**: Both desktop and mobile navigation are included, with a separate sidebar menu for smaller screens.

---

### Accessibility Features

Accessibility has been a priority throughout the site. Here are the key implementations:
- **Semantic Elements**: Proper use of HTML5 elements ensures logical content organization.
- **ARIA Attributes**:
  - `aria-expanded` and `aria-hidden` to indicate the state of the mobile navigation menu.
  - `aria-label` and `aria-labelledby` for descriptive labels on links, sections, and images.
- **Screen Reader Support**:
  - `sr-only` class hides visual elements but keeps them accessible to screen readers.
  - Navigation links and buttons are descriptive and provide context for their actions.
- **Keyboard Navigation**: The site is fully navigable via keyboard, with logical focus order and interactive elements like buttons and links.

---

### Handling Responsive Navigation with the Burger Menu

The responsive navigation is managed using a **burger menu** for mobile devices. Here’s how it works:
1. **Checkbox Input**: A hidden `<input type="checkbox">` element toggles the menu's visibility.
2. **ARIA States**: 
   - `aria-expanded` dynamically updates to reflect whether the menu is open or closed.
   - `aria-controls` links the toggle button to the corresponding navigation element for assistive technologies.
3. **CSS Styling**:
   - The sidebar (`<aside>`) is styled to be off-screen by default and slides into view when the checkbox is checked.
   - Media queries ensure the desktop navigation (`<nav class="desktop-nav">`) is displayed instead of the burger menu on larger screens.
4. **Progressive Enhancement**: The approach ensures that the menu is usable even if JavaScript is disabled.

This implementation ensures that the navigation is both **responsive** and **accessible** across a variety of devices and user needs.


### Links
Live Demo : [News homepage ](https://juliengdev-news-hompage.netlify.app/)

## My Process

### Built With
- TypeScript for enhanced type safety
- Semantic HTML5 markup
- SCSS for advanced styling
- Mobile-first workflow
- ARIA attributes for accessibility
- Real-time form validation
- Toast notification system

### Useful Resources	
	
  - [	Create a responsiv Menu burger](https://www.youtube.com/watch?v=dAIVbLrAb_U) - How To Build An Animated Hamburger Menu With Only CSS
  - [WAI-ARIA Practices](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Accessibility/WAI-ARIA_basics) -  Essential patterns for accessible web components.
  - [W3C Web Accessibility Initiative (WAI)](https://www.w3.org/WAI/) - Provides guidelines and best practices for creating accessible web content.

## Author

- Website - [Julien Gilbert Portfolio](https://juliengdev.github.io/julien-gilbert-portfolio/)
- Frontend Mentor - [@juliengDev](https://www.frontendmentor.io/profile/juliengDev)
- LinkedIn - [Julien Gilbert](https://www.linkedin.com/in/julien-gilbert-reactjs/)

Feel free to reach out if you have any questions or feedback about this project!