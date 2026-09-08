# Frontend Mentor - Blog Preview Card Solution

This is a solution to the [Blog Preview Card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). The project recreates a compact article card with an illustration, category label, publication date, article summary, and author details.

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)

## Overview

### The Challenge

Users should be able to:

- View the blog preview card on their device.
- Read the article category, publication date, title, description, and author information.
- See hover and focus states for the interactive elements on the page

### Links

- Challenge: [Frontend Mentor Blog Preview Card](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS)

## My Process

### Built With

- Semantic HTML5
- CSS3
- Flexbox
- Custom `@font-face` font loading
- Local image and font assets

### What I Learned

This project provided practice building a focused card component with HTML and CSS. Flexbox was used to center the card on the page and align the author avatar with the author name. I also used a reusable visual style for the card, including rounded corners, a high-contrast shadow, and spacing between content sections.

```css
.card {
  background-color: hsl(0, 0%, 100%);
  width: 320px;
  border-radius: 10px;
  box-shadow: 8px 8px 0 hsl(0, 0%, 7%);
  padding: 20px;
}
```

### Continued Development

Future improvements could include adding responsive sizing for smaller screens, clear keyboard focus styles for interactive elements, and a more meaningful interaction for the category label or article title.

### Useful Resources

- [Frontend Mentor](https://www.frontendmentor.io) - Provided the design challenge and assets.
- [MDN Web Docs: Flexbox](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Flexbox) - A useful reference for layout and alignment with Flexbox.
- [MDN Web Docs: `@font-face`](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face) - Helpful for loading local font files in CSS.

## Author

- Coded by Spiritualtechsolutions
