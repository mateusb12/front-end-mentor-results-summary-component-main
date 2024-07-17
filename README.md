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
- **Bonus**: Use the local JSON data to dynamically populate the content

### Screenshot

![Screenshot](./screenshot.png)

### Links

- Solution URL: [GitHub Repository](https://github.com/mateusb12/front-end-mentor-results-summary-component-main)
- Live Site URL: [Live URL](https://mateusb12.github.io/front-end-mentor-results-summary-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

- `<div>` is a block-level element; it covers the entire horizontal space.
- `<span>` is an inline element; it occupies only the necessary space.

- I can use CSS Attribute Selectors to target specific <tags> that have a custom attribute

```css
.summary-item[data-type="reaction"] {
    background-color: #fff6f5;
}
```
- Here is a good css reset
```css
* {
    margin: 0;
    padding: 0;
    font: inherit;
    box-sizing: border-box;
    font-family: var(--font-family-default), serif;
    font-size: var(--fs-400);
    color: var(--light-lavender);
}

img, svg{
    display: block;
    max-width: 100%;
    height: auto;
}
```

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.
I want to keep learning on
- Absolute vs Relative positioning

## Author

- Frontend Mentor - [@mateusb12](https://www.frontendmentor.io/profile/mateusb12)
- Twitter - [@matbessam](https://www.twitter.com/matbessam)
