# Frontend Mentor - Recipe Page Solution

This is my solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm).

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

### Screenshot

![](./design/assets/images/frontend%20mentor.png)

### Links

- Live Site URL: [Recipe Page](https://your-live-site-url.com)
- Solution URL: [Frontend Mentor Solution](https://your-solution-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- CSS Grid

### What I learned

During this project, I learned how to:
- Structure recipe content semantically with HTML5
- Style ordered and unordered lists with custom markers
- Create responsive layouts using Flexbox
- Implement CSS variables for consistent styling

Some code I'm proud of:

```css
:root {
    --color-text: hsl(30, 10%, 34%);
    --color-marker: hsl(14, 45%, 36%);
    --font-primary: 'Outfit', sans-serif;
}

.instructions li::marker {
    color: var(--color-marker);
    font-weight: 700;
}