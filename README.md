# Don Promzzy - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Don Promzzy - Product preview card component solution](#don-promzzy---product-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
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

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./design/desktop-design.png)

### Links

- Solution URL: [Github Code](https://github.com/Don-Promzzy/product-card-challenge)
- Live Site URL: [Product-Card-Challenge](https://don-products-card.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Media Query
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

I add class to my header tag to add style, and the inherit CSS keyword causes my element between my product image and product content to take the computed value of the property from its parent element.

```html
  <div class="prod-price">
                <h1 class="new__price">$149.99</h1>
                <p class="old__price">$169.99</p>
            </div>
```
```css
.prod__image img {
    display: block;
    width: 300px;
    height: 200px;
    border-radius: 5px 5px 0 0;
}
```

### Continued development

In order to build more projects in the future, I'm going to start concentrating more on HTML semantic, CSS flexbox, and media query.

### Useful resources

- [HTML Divs](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/div) - The HTML element div> assists me in creating a generic container for flow content. It has no effect on the content or layout until it is styled with CSS.
- [CSS Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox) - CSS Flexbox property helped me to arrange items without using float. It makes arranging items in the document much easier. 

## Author

- Website - [Promise Imafidon](https://github.com/Don-Promzzy)
- Frontend Mentor - [@Don-Promzzy](https://www.frontendmentor.io/profile/Don-Promzzy)
- Twitter - [@Don_Promzzy](https://twitter.com/Don_Promzzy)

## Acknowledgments

First of all, I would like to thank the founder of Frontend Mentor and the challenge organizers for allowing us to participate in this contests in order to demonstrate our skills and gain more knowledge about the frontend world.
