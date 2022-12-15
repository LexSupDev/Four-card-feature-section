# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Four card featured section](./images/screenshot.png)

- Solution URL: [Frontend Mentor Solution](https://www.frontendmentor.io/solutions/)
- Live Site URL: [GitHub Pages](https://lexsupdev.github.io/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- SCSS

### What I learned

Turns out that :after on an \<img\> tag simply isn't supported by most browsers. (apparently it is supported by Opera, but not much else)

The best solution I can give you is to either wrap your \<img\> in a \<div\> or similar, and put the :after on that, or abandon the \<img\> tag entirely and use a background-image instead.

```html

```
```css

```

### Continued development

I think i will add some animation.
### Useful resources

- [https://lildude.co.uk/after-css-property-for-img-tag](https://lildude.co.uk/after-css-property-for-img-tag) - This helped me to understand why pseudo-elements didn't work with img.

## Author

- Frontend Mentor - [@lexsupdev](https://www.frontendmentor.io/profile/LexSupDev)

