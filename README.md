# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

- See hover states for interactive elements

### Links

- Solution URL: [solution URL here](https://github.com/novanAfnd/frontend-mentor-order-summary-component)
- Live Site URL: [live site URL here](https://novanafnd.github.io/frontend-mentor-order-summary-component/)

## My process

### Built with

- Semantic HTML5 markup
- BEM Convention
- Flexbox
- Mobile-first workflow

### What I learned

I learned about the BEM convention. Then I found a problem. The problem is that when using HTML elements that are nested too deep, the naming of the BEM becomes confusing. So I made my own version of the BEM convention like this.

```html
<div class="card__plan">
  <div class="plan__plan-description">
    <img class="plan-description__image" src="images/icon-music.svg" alt="" />
    <div class="plan-description__text">
      <p class="text__upper-text">Annual Plan</p>
      <p class="text__lower-text">$59.99/year</p>
    </div>
  </div>
  <div class="plan__plan-change">
    <p class="plan-change__text">Change</p>
  </div>
</div>
```

The CSS looks like this.

```css
.card__plan {
}

.plan__plan-description {
}

.plan-description__image {
}

.plan-description__text {
}

.text__upper-text {
}

.text__lower-text {
}

.plan__plan-change {
}

.plan-change__text {
}
```

I don't know if this is the correct writing or not. But I tried to make it easy to understand for myself.

### Continued development

I will continue to learn about code naming standards. whether it's an ID or class in HTML, a variable in JS and so on. Because with good naming the code will be easy to maintain.

### Useful resources

- [CSS :hover Selector](https://www.w3schools.com/cssref/sel_hover.php) - this helped me learn about hover in CSS.

## Author

- Website - [Novan Afandi](https://kosmikkoding.my.id/)
- Frontend Mentor - [@novanAfnd](https://www.frontendmentor.io/profile/novanAfnd)
