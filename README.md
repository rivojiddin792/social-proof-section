# Frontend Mentor - Ricky's Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). 

<img src="./design/desktop-preview.jpg">

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

I feel more confident using CSS and Flexbox simultaneously. Executing the designs has also become much easier, as I can now visualize the HTML and CSS code structure after a 10-minute observation. This helps me organize myself ahead of time and lay out more efficient, cleaner code. 


### The challenge

Users should be able to:

- View the optimal layout for the section depending on the device's screen size

### Screenshot

<img src="./desktop social proof design.png"/>
<img src="./mobile social proof design.png"/>


### Links

- Live Site URL: https://riickyriick.github.io/social-proof/

## My process

- I structured my HTML semantically
I began by organizing key sections with semantic tags (<header>, <section>, <footer>). Use containers like <div>, <section>, or <figure> to group related content such as images, text, and buttons.
For better practice for SEO (Although I'm not so familiar with this yet). 


- I assigned unique class names
I created descriptive classes (.hero-section, .gallery-grid, .footer-container) for each section or element that needs styling. 
This makes targeting with CSS easier and more transparent.


- Layout planning
I decided how my layout will adapt to different screens. For example, my header might be a three-column grid, my gallery uses a grid with specific areas, and my footer content adjusts with media queries.


- Then, for my CSS, I added reset & variables
Set box-sizing: border-box, remove default margins, and define CSS variables for colors and sizes (:root {}) for consistency.


- I began styling major components
Apply CSS properties:

For the header: background-image, background-size, background-position, and height.

For content containers: use Grid or Flexbox for structure.

For images: set width 

For text and buttons: set fonts, sizes, spacing, and hover effects.


- I added media queries for better responsiveness for desktop, tablet, and mobile viewports, adjusting all:

Grid columns/rows

Font sizes

Padding and margins

Display properties (block, flex, grid) for stacking content vertically


- I continue to test and fine-tune my media queries
I used the browser tools to resize and see how the layouts reacted. Adjust CSS properties like background-size, element sizes, or grid areas until my design felt smooth and consistent across devices.


- Summary: 

I started with clean HTML and meaningful classes. I planned the layout with CSS Grid and Flexbox, then progressively refined it with media queries and testing. 

Focused on structure first, then style with responsiveness in mind.


### Built with

- Semantic HTML5 Markup
- Flexbox
- CSS Grid
- Desktop-first workflow

### What I learned

This project was a review of my skills so far, and it helped me better understand my progress.


## Author

--Website: (https://www.rarroyoharo.com)<a href="https://www.rarroyoharo.com" target="_blank">rarroyoharo.com</a> 
--Frontend Mentor - [@RiickyRiick]<a href="https://www.frontendmentor.io/profile/RiickyRiick" target="_blank">@RiickyRiick</a> 



