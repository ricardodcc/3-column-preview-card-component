# Frontend Mentor - 3-column preview card component

This is a solution to the [3-column preview card component](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges helps you to improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)

## Overview

### Screenshot

![](design/desktop-preview.jpg)


### Links

- Solution URL: (https://www.frontendmentor.io/solutions/desktop-responsive-component-w-min-and-max-width-v-q1wDCVwD)
- Live Site URL: (https://ricardodcc.github.io/3-column-preview-card-component/)

## My process
- First of all, I started this small project by organizing the Sass folder. In this folder, will be all the sass files that compose my style properties. So for that, I created:
  - A main file that contains all the imports of the other files;
  - A homepage.scss file where you can find all the styles for the component of this challenge;
  - A utils folder that contains such files as:
    - extends.scss, mixins.scss, and variables.scss for the implementation and declaration of the extends/mixins and variables that will be needed for the component implementation.     

- After that I created the index.html and the style.css file to write the HTML structure respecting the HTML5 "rules" and then just tipped ```scss --watch Sass/main.scss style.css``` and then when saving new info into any Sass it will automatically convert that into CSS language.

- In this challenge, I went for a 3-column grid because it was the first thing that came up in my head looking into the final design. After that, I tried to organize my code into a section that restricts the width of the usable safe for this challenge. 

- Behind that, I have 3 div that have the same elements, and the way that I used to modify the color, a:link was giving a different class (sedans, suvs, and luxury) to each column. Finishing, I also gave a grid-item class to each column in order to give the padding.   

### Built with

- Semantic HTML5 markup
- CSS custom properties, and variables
- SASS extends, mixins, and variables