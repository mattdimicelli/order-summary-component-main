# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Order summary card solution](#frontend-mentor---order-summary-card-solution)
  - [Table of contents](#table-of-contents)
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

- Replicate the supplied model (images)
- See hover states for interactive elements

### Screenshot

![](./images/screenshot.png)



### Links

- Live Site URL: [https://mattdimicelli.github.io/order-summary-component-main/](https://mattdimicelli.github.io/order-summary-component-main/)

## My process

### Built with

- Semantic HTML5
- Flexbox
- Mobile-first workflow
- Media queries
- Google Fonts
- The New CSS Reset




### What I learned

- [The New CSS Reset](https://elad2412.github.io/the-new-css-reset/) eliminates all broswer-provided default styles besides the display property.

- In order for images to not exceed their containers, most developers use:
  ~~~css
  img {
      max-width: 100%;
  }
  ~~~
- In edge cases (eg. when a containers's edges are rounded), 
  ```css
  div {
    overflow: hidden;
  }
  ```
  will prevent the image from bleeding out of the container.

- Every HTML document should have one main landmark, and all page content should
  be contained by landmarks.  In this document I used HTML5 semantic elements
  as well as Aria attributes to achieve this.  Although the future will favor
  the use of the native HTML5 elements, for now, it is still a best practice to 
  include both.
