# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - QR code component solution](#frontend-mentor---qr-code-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
  - [Author](#author)

## Overview

### Screenshot

![Screenshot of QR code component](./screenshot.jpg)

### Links

- Solution URL: [https://github.com/yourusername/qr-code-component](https://github.com/yourusername/qr-code-component)
- Live Site URL: [https://yourusername.github.io/qr-code-component/](https://yourusername.github.io/qr-code-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Outfit](https://fonts.google.com/specimen/Outfit) font

### What I learned

During this project, I learned how to:
- Use CSS custom properties for consistent color theming.
- Apply a mobile-first approach for responsive design.
- Center content both vertically and horizontally using Flexbox.
- Implement a clean card UI with rounded corners and subtle shadows.
- Use Google Fonts and follow a provided style guide for typography.

Here is a snippet of the CSS custom properties and responsive container:

```css
:root {
  --white: hsl(0, 0%, 100%);
  --slate-300: hsl(212, 45%, 89%);
  --slate-500: hsl(216, 15%, 48%);
  --slate-900: hsl(218, 44%, 22%);
}

.qr-container {
  background: var(--white);
  border-radius: 20px;
  box-shadow: 0 8px 24px rgba(31, 50, 81, 0.10);
  padding: 1.5rem 1rem 2.5rem 1rem;
  max-width: 320px;
  width: 90vw;
  text-align: center;
  display: flex;
  flex-direction: column;
  align-items: center;
}
```

### Continued development

In future projects, I want to:
- Explore using CSS Grid for more complex layouts.
- Improve accessibility by adding ARIA labels and better focus states.
- Experiment with subtle CSS animations for enhanced UI feedback.

### Useful resources

- [Frontend Mentor QR Code Component Challenge](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H) - The official challenge page.
- [MDN Web Docs - Responsive Design](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design) - Great resource for learning about responsive layouts.
- [Google Fonts - Outfit](https://fonts.google.com/specimen/Outfit) - The font used in this project.

## Author

- Website - [Your Name](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)
