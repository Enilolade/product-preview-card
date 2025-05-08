# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Useful resources](#useful-resources)
- [Author](#author)

## Overview

A responsive product preview card component with mobile and desktop layouts. The card displays product details, an image, and a call-to-action button.

### Screenshot

![Mobile Design](./screenshots/mobile.png)  
![Desktop Design](./screenshots/desktop.png)

### Links

- Solution URL: [Add your solution URL here](#)
- Live Site URL: [Add your live site URL here](#)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Responsive design using media queries
- Mobile-first approach
- Google Fonts: Montserrat and Fraunces

### What I learned

While working on this project, I practiced:

- Structuring HTML components cleanly and semantically.
- Using custom fonts with `@import` from Google Fonts.
- Applying `box-sizing`, `flexbox`, and `media queries` for responsive design.
- Styling buttons and adding hover effects for improved UX.

One challenge I faced was keeping the footer at the bottom of the screen on larger screen sizes (`min-width: 768px`). Despite using `position: absolute` and trying to adjust placement with `top: 100%` or `bottom: 0`, it still doesn't consistently stick to the bottom unless there's enough content on the page. I plan to explore using **Flexbox layout on the body or main wrapper** as a potential fix.

## Useful resources

- [CSS Tricks: Flexbox Footer](https://css-tricks.com/couple-takes-sticky-footer/) – Helped me understand different approaches to sticky footers.
- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS) – My go-to reference for all CSS-related questions.
- [Google Fonts](https://fonts.google.com/) – For adding and customizing fonts.

## Author

- Frontend Mentor – [@yourusername](https://www.frontendmentor.io/profile/yourusername)
