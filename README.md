# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 
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

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./Screenshot%20Frontend%20Mentor%20Results%20summary%20component.png)


### Links

- Live Site URL: [Results summary component | Frontend Mentor](https://transcendent-gingersnap-38f0a6.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Grid

### What I learned

With this challenge I realised that even though Flexbox can accomplish what Grid can do in terms of one dimensional arrangement of components, Grid will always keep the specified space between elements while Flexbox will shrink or completely remove the space if the container doesn't have enough space for the arranged elements.
Below I have an example of a div where I used both of them to see the results when changing the height of the container element whose class is .summary:

```css
.summary {
  border-radius: 25px;
  padding: 30px;
  display: grid;
  grid-row-gap: 30px;
  /*display: flex;*/
  /*flex-direction: column;*/
  /*justify-content: space-evenly;*/
}
```


### Continued development

I'll have to explore more the specific uses of Flexbox and Grid as in this challenge.


### Useful resources

- [How to align items in the vertical direction inside a flex container](https://www.freecodecamp.org/learn/responsive-web-design/css-flexbox/align-elements-using-the-justify-content-property) 
- [How to add gap between rows of items inside a grid container](https://www.freecodecamp.org/learn/responsive-web-design/css-grid/create-a-row-gap-using-grid-row-gap)

## Author
- Frontend Mentor - [@Mamouty](https://www.frontendmentor.io/profile/Mamouty)
- LinkedIn - [Mahmoud Guefri](https://www.linkedin.com/in/mahmoud-guefri-6b0269193/)
