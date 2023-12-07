# Frontend Mentor - Order summary card solution

This is my solution to the [Order summary card challenge on Frontend Mentor](https://kwokkw.github.io/order-summary-component-main/). 

## Table of contents

- [Frontend Mentor - Order summary card solution](#frontend-mentor---order-summary-card-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Acknowledgments](#acknowledgments)
  - [Time estimate](#time-estimate)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

How to plan your HTML (1): Product Preview Card - [Grace Snow](https://fedmentor.dev/posts/html-plan-product-preview/)
- Build out a order summary card component
  - Landmarks (main, footer)
  - The card
    - Two containers inside the card, one for the image, one for the text 
  - Card image, [picture element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/picture) 

```html
<picture>
    <!-- largest image -->
    <source srcset="/media/images/decorative-image-3.jpg"
      media="(min-width: 60rem)">
    <!-- medium image -->
    <source srcset="/media/images/decorative-image-2.jpg"
      media="(min-width: 40rem)">
    <!-- smallest image (default) -->
    <img src="/media/images/decorative-image-1.jpg" alt="">
</picture>
```


### The challenge

Users should be able to:

- See hover states for interactive elements

### Links

- Solution URL: [github repo](https://github.com/kwokkw/order-summary-component-main)
- Live Site URL: [live site](https://kwokkw.github.io/order-summary-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- With extra focus on:
  - image sizing with object-fit
  - buttons vs anchors
  - flexbox (possibly CSS grid)
  - heading order
  - mobile-first styling

### What I learned

If the images on the page are purely decorative and don't add meaningful content to the page, it's appropriate to leave the alt attribute empty `alt=""`. This signifies that the image is decorative, and it allows assistive technologies like screen readers to ignore the image, reducing unnecessary noise for users who rely on those technologies.

### Acknowledgments

[Melvin Aguilar](https://www.frontendmentor.io/profile/MelvinAguilar)

## Time estimate

Start at 2:35pm on 12/2/2023
Finished at 22:41pm on 12/5/2023 