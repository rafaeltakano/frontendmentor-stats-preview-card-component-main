# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [https://rafaeltakano.github.io/frontendmentor-stats-preview-card-component-main/](https://rafaeltakano.github.io/frontendmentor-stats-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned that I can use pseudo-elements for images overlays

```scss
&__img {
  background-image: url('../../images/image-header-mobile.jpg');
  background-size: cover;
  border-top-left-radius: 0.5rem;
  border-top-right-radius: 0.5rem;
  height: 17.5rem;
  position: relative;
  margin-bottom: 2.5rem;
  width: 100%;

  &::before {
    content: '';
    position: absolute;
    inset: 0;
    background-color: $--accent-transparent;
    border-top-left-radius: 0.5rem;
    border-top-right-radius: 0.5rem;
    filter: brightness(0.3) contrast(1) saturate(5);
  }
}
```

## Author

- LinkedIn - [Rafael Takano](https://www.linkedin.com/in/rafaeltakano1/)
- Frontend Mentor - [@rafaeltakano](https://www.frontendmentor.io/profile/rafaeltakano)
