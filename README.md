# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](images/screenshotnew.PNG)


### Links

- [Solution URL](https://github.com/pnrmmt/frontendmentor-newbie1)
- [Live Site URL](https://pnrmmt.github.io/frontendmentor-newbie1/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned the features such as max-height, max-width, grid and flex and responsive design in CSS.

```css
.grid{

    max-width: 700px;
    display: grid;
    grid-template-columns: 1fr 1fr;
    background-color: #ffff;
    border-radius: 15px;
    overflow: hidden;
}
```


```css
@media only screen and (max-width:628px){
    .grid{
        grid-template-columns: 1fr;
    }

    .img img {
        max-height: 450px;
        width: 100%;
        object-fit: cover;
    }
    .card-content{
        display: block;
    }
    .category, .name, .des, .price {
        padding-bottom: 23px;
    }
}


```


