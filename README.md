# Frontend Mentor - Easybank landing page solution

This is a solution to the [Easybank landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/easybank-landing-page-WaUhkoDN). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Links

- Live Site URL: [Easybank](https://effortlessbanking.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- SASS (SCSS)
- Flexbox
- Desktop-first workflow

### What I learned


```scss
@mixin respond-to($breakpoint) {
  @if $breakpoint == desktop {
    @media (min-width: 1024px) { @content; }
  } @else if $breakpoint == tablet {
    @media (min-width: 768px) { @content; }
  } @else if $breakpoint == mobile {
    @media (max-width: 767px) { @content; }
  }
}
```