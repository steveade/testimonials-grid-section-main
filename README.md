# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Project Screenshot](./screenshot.png)

### Links

- Solution URL: [](https://github.com/steveoncaffeine/testimonials-grid-section-main)
- Live Site URL: [](https://steveoncaffeine.github.io/testimonials-grid-section-main/)

## My process

### Built with

- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

While working on this project, I used CSS grid for the first time and I learnt about the following grid properties:

- `grid-template-rows`
- `grid-template-columns`
- `grid-row`
- `grid-column`

I also got more familiar with the mobile first workflow and also media  queries. Here's a snippet of code I'm really proud of:

```css
@media screen and (min-width: 1201px) {
    section {
        display: flex;
        justify-content: center;
        align-items: center;
        width: 100vw;
        height: 100vh;
    }

    .grid-container {
        display: grid;
        grid-template-columns: repeat(4, 290px);
        grid-template-rows: 310px 290px
    }

    .daniel-card {
        grid-column: 1 / span 2;
        grid-row: 1
    }

    .jonathan-card {
        grid-column: 3;
        grid-row: 1;
    }

    .kira-card {
        grid-column: 4;
        grid-row: 1 / span 2;
        width: 263px;
    }

    .jeanette-card {
        grid-column: 1;
        grid-row: 2 / span 1;
    }

    .patrick-card {
        grid-column: 2 / span 2;
        grid-row: 2;
    }
}
```

### Continued development

In future projects, I'd like to focus on writing more semantic HTML code, reducing my reliance on brute forcing problems (trial and error) and writing cleaner code.

### Useful resources

- [A Complete Guide to CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/#prop-grid-template-columns-rows) - This is an in-depth article helped me get familiar with how css grid works very quickly. I'd recommend it to anyone still learning this concept.
- [GRID: A simple visual cheatsheet for CSS Grid Layout](https://grid.malven.co/) - This is a very helpful cheatsheet with simple visualizations for very useful grid properties. This helped me build the layout for this project extremely quickly.

## Author

- Frontend Mentor - [@steveoncaffeine](https://www.frontendmentor.io/profile/steveoncaffeine)
- Twitter - [@steveoncaffeine](https://www.twitter.com/steveoncaffeine)
