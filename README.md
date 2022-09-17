
# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)



## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./Frontend_Mentor_Product_preview_card_component.png)



### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

In this lesson i learned how to change the src of a picture depending on the size of the screen, i didn't even know this elements exist, very interesting and very easy to use:


```html
<picture class="card-image">
  <source media="(min-width: 1440px)" srcset="images/image-product-desktop.jpg" />
  <img src="images/image-product-mobile.jpg" alt="product image mobile" class="image-product">
</picture>

```


### Continued development

i'll definitely continue practicing how and where to use the landmarks for more accessibility, sometimes a don't know where to put them or simply forgot about them.



## Author

- Frontend Mentor - [@uvdevelop26](https://www.frontendmentor.io/profile/uvdevelop26)
- Twitter - [@betovillalbapy](https://www.twitter.com/betovillalbapy)



