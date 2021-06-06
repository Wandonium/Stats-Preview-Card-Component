# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshots

![](./images/mobile-screenshot.png)


![](./images/desktop-screenshot.png)

### Links

- Solution URL: [Solution on Frontend Mentor](https://www.frontendmentor.io/solutions/css-flexbox-html5-mobile-first-design-media-queries-google-fonts-M8ANFy1bT)
- Live Site URL: [Live Site on Github](https://wandonium.github.io/Stats-Preview-Card-Component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

How to use both min-width and max-width limits on css media queries to target specific device measurements for responsive design.

```css
@media screen and (min-width: 376px) and screen (max-width: 760px) {

    .card-body h2, .card-body p { 
        padding: 0 3rem;
    }

    .card-body ul {
        margin-top: 1rem;
    }
}
```

How to use the border-radius css property on specific corners of a div and use the background-blend-mode property for backgrounds on images.

```css
.image {
    position: relative;
    width: 100%;
    height: 30%;
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
    background-image: url('images/image-header-mobile.jpg');
    background-color: hsl(277, 64%, 61%);
    background-size: cover;
    background-blend-mode: multiply;
}
```

## Author

- Website - [Hillary Wando](http://hillarywando.com/)
- Frontend Mentor - [@Wandonium](https://www.frontendmentor.io/profile/Wandonium)
- Twitter - [@hillarywando](https://www.twitter.com/hillarywando)
