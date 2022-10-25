# Frontend Mentor - Order summary card solution

![ScreenShot](./scrsht/MacBook%20Pro%2016.jpeg)

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./scrsht/iPhone%2014%20Pro.jpeg)
**Mobile version**

![](./scrsht/MacBook%20Pro.jpeg)
**Desktop version**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- SASS

### What I learned

The media query's and the Shadow Box.

```css
.btn-payment {
  box-shadow: 0 1.6rem 1rem hsl(225deg, 100%, 94%);

@media screen and (min-width: 576px) {
  .container {
    background-color: hsl(225deg, 100%, 98%);
    background-image: url(../img/pattern-background-desktop.svg);
    background-size: cover;
  }
}
@media screen and (max-width: 575px) {
  .container {
    background-color: hsl(225deg, 100%, 98%);
    background-image: url(../img/pattern-background-mobile.svg);
    background-size: cover;
  }
}
```

### Useful resources

- [msn web docs\_](https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow) - This arrticle helped whit the `box-shadow` property.
- [msn web docs\_](https://developer.mozilla.org/en-US/docs/Web/API/MediaQueryList) - The background has to change deppend on the device screen, so this article helps to use de `MediaQuerysList.media` property.

## Author

- Website - [crRoG](https://crrog.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/home)
- Twitter - [@crrog](https://www.twitter.com/crrog)
