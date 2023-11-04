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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

This is my take on Social Proof section challenge by Frontend Mentor

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size


## My process

 I tried to divide the provided design image into sections and decide where i should be using grid , and where flexbox, i that tried to build part by part testing the responsivnes of each part and each parts influence on the rest so this challenge that looked a quite easy took me quit a while.
 ** I changed the opacity to 1 for the background images so i could see what i was doing and decide to keep it so.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow


### What I learned
**Using media query in the root in order to change font size on smaller screens by
overwriting the existing defined variables in the root
  :root{
     --fs-300: .7rem;
          --fs-400:.9rem;
          --fs-500:1rem;
          --fs-600:1.125rem;
          --fs-700:1.25rem;
          --fs-800:1.5rem;
          --fs-900:2rem;
  }
**Using background to achive the needed layout as well as position properties 
    background: url(images/bg-pattern-top-desktop.svg) no-repeat top left,
                url(images/bg-pattern-bottom-desktop.svg)no-repeat bottom right;
    background-size: max(35%,500px),max(75%,300px);
**Usage of transform
    .product-ratings li:nth-child(1){
        transform: translateX(-3rem) ;
    }
    .product-ratings li:nth-child(3){
        transform: translateX(3rem) ;
    }
**



### Useful resources

- https://www.youtube.com/watch?v=rzD-cPhq02E  css transform nicely explained 
- https://www.youtube.com/watch?v=K27WULzr2P8&t=1s Kevin Powells take on this challenge

## Author

- Frontend Mentor - https://www.frontendmentor.io/profile/nenadvg95


## Acknowledgments
I want to acknowledge the whole Frontend community for being extremely helpful with feedbacks 