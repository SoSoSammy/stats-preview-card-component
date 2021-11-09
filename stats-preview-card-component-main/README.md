# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
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

### Screenshot

![](./stats-preview-card-desktop.jpg)
![](./stats-preview-card-mobile.jpg)

## My process

### Built with

- Flexbox
- Mobile-first workflow

### What I learned

I learned how to use Flexbox to create a component of a professional website. Before I had only learned how to use Flexbox, but now I am working towards applying what I have learned.

I am proud of this CSS code. I was trying to figure out how to change the stats preview card with media queries, and this code helped me to achieve exactly what I was looking for.

```css
@media only screen and (min-width: 992px) {
  .container {
    flex-direction: row-reverse;
    margin: 100px 80px;
  }
}
```

I am also proud of this CSS code. I realized that I had to add a violet tint to the image, and I was able to research how to do it online and choose the best solution based on my situation.

```css
.img {
  position: relative;
  border-radius: 15px 15px 0 0;
}

/* Violet tint for the image */
.img:before {
  content: "";
  position: absolute;
  width: 100%;
  height: 100%;
  background: var(--soft-violet);
  z-index: 1;
  opacity: 0.5;
  border-radius: 15px 15px 0 0;
}
```

### Continued development

I will continue to utilize Flexbox to create more websites and web components. I will also figure out how to make the component fit the screen width so there is not a scroll bar.

### Useful resources

- [Three ways to tint image with CSS3: box-shadow, multiple backgrounds and pseudo elements.](https://cssfox.co/=maxim-aginsky/log/three-ways-to-tint-image-with-css3-box-shadow-multiple-backgrounds-and-pseudo-elements/) - This helped me with creating the violet tint for the image. I really liked how straightforward and simple the different solutions were.
- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/#flexbox-properties) - This is an amazing article which helped me understand the different aspects of Flexbox. I'd recommend it to anyone learning Flexbox.

## Author

- YouTube - [SoSoSammy](https://www.youtube.com/channel/UCoq37ApMC5MpwGke4YNjM3Q)
- Frontend Mentor - [@SoSoSammy](https://www.frontendmentor.io/profile/SoSoSammy)

