# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
- [Author](#author)


## Overview

The aim of this challenge was to create a responsive product preview card component that looks good both on large and smaller screens. 
I used Visual Studio Code as my code editor and the design images provided by Frontend Mentor. 

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Click on the link for desktop version](./final-project-screenshot-desktop.jpg).
![Click on the link for mobile version](./final-project-screenshot-mobile.jpg).


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

After writing the HTML markup, I proceeded styling the various components in the CSS file. 
The class [.container] was given the display value of flex in order to lay out the two cards (one with the product image and the other with the product description) in a row on the main axis, next to each other.
Both images (mobile and desktop product image) were added in the HTML document; the [.mobile-image] class was given the display value of none for larger screen size whilst for smaller screen size the @media CSS rule was used so the dispaly value for the mobile image was set to flex.
With media query I was able to change the size and style of the card components to fit smaller screen sizes for a better User Experience: the two cards containing the product image and product description are not positioned in a row anymore, but rather in a column, with the image displaying on top and the description below.


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Media query


## Author

- Frontend Mentor - [@lullich](https://www.frontendmentor.io/profile/lullich)