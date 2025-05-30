# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

Recipe page for desktop and mobile made with flex box and media query.

### Screenshot

Desktop
![](/screenshot.png)

Mobile
![](/screenshot-mobile.png)

### Links

- Solution URL: [https://github.com/nunu114/recipe-page-solution.git](https://github.com/nunu114/recipe-page-solution.git)
- Live Site URL: [https://recipe-page-nunu.netlify.app/](https://recipe-page-nunu.netlify.app/)

## My process

1. Looking through the design example and start planning how to get my solution to look similar to the design
2. Write the structure of the page using HTML
3. Design the page each section from top to bottom in mobile screen size
4. Write media query for desktop screen size

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I had a hard time styling the list item and i spent quite some time searching for ways to fix my problem. Thankfully I found it and able to finish the design.

Here's an example:
I wanted to change the color of the bullet point and align the text in the middle of it.

```css
.ingredients li::marker {
    color: var(--brown800);
}

.ingredients p {
    display: inline-block;
    vertical-align: middle;
}
```

### Continued development

Continue learn responsive design.

### Useful resources

- [Align list](https://stackoverflow.com/questions/6550069/bullets-center-with-unordered-list) - This helped me to align my text inside the list item.
- [Change bullet color of lists](https://www.w3schools.com/howto/howto_css_bullet_color.asp) - This helped me for changing the color of the list style/bullet in a list.
- [Mobile-first design](https://www.w3schools.com/css/css_rwd_mediaqueries.asp) - This helped me for applying the mobile-first design technique using breakpoints for media query.

## Author

- Website - [Nurika](https://github.com/nunu114)
- Frontend Mentor - [@nunu114](https://www.frontendmentor.io/profile/nunu114)
