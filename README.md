# Frontend Mentor - Intro section with dropdown navigation solution

This is a solution to the [Intro section with dropdown navigation challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/intro-section-with-dropdown-navigation-ryaPetHE5). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the relevant dropdown menus on desktop and mobile when interacting with the navigation links
- View the optimal layout for the content depending on their device's screen size
- See hover states for all interactive elements on the page


### Links

- Solution URL: (https://www.frontendmentor.io/solutions/responsive-landing-page-using-css-grid-and-flexbox-wmG24Mp6i8)
- Live Site URL: (https://doileo.github.io/intro-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- JavaScript

### What I learned

Working on this project provided an excellent opportunity to learn how to create both a dropdown menu and an open menu for mobile viewing.

Here are the code snippets for JavaScript:

```js
const menu = document.querySelector('.menu');
const dropdown = document.querySelectorAll('.dropdown');

menu.addEventListener('click', function() {
    menu.parentElement.classList.toggle('open');
    document.body.classList.toggle('nav-open');
})
dropdown.forEach(function(item) {
    item.addEventListener('click',function() {
        item.parentElement.classList.toggle('link-open');
    })
})
```

### Continued development

For the future projects I will continue to focus on getting used with using the parent element.

## Author

- Website - [Doina](https://doileo.github.io/portfolio/)
- Frontend Mentor - [@Doileo](https://www.frontendmentor.io/profile/Doileo)
- Twitter - [DLeovchin](https://twitter.com/DLeovchin)
