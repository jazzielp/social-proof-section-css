# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the section depending on their device's screen size

### Screenshot

#### Desktop
![](./images/screenshot/Captura%20de%20pantalla%202024-02-09%20153031.png)

#### Mobile
![](./images/screenshot/Captura%20de%20pantalla%202024-02-09%20153114.png)
![](./images/screenshot/Captura%20de%20pantalla%202024-02-09%20153134.png)

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

* Learn how to use more than one image for the background-image and be able to position them

```css
body{
    background-image: url('./images/bg-pattern-top-mobile.svg'), url('./images/bg-pattern-bottom-mobile.svg');
    background-position: top left, bottom right ;
    background-repeat: no-repeat, no-repeat;
    
}
```

* Being able to practice more flexbox and use aling-self property (flex-start, flex-center, flex-end)

```css
    .cards-container__card--top {
        align-self: flex-start;
    }

    .cards-container__card--buttom {
        align-self: flex-end;
    }
```

* Being able to practice more of the grid and use the justify-self property (left, center, right)

```css
    .raited__card--center {
        justify-self: center;
    }

    .raited__card--right {
        justify-self: right;
    }
```
