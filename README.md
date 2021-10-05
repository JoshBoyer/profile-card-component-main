# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: https://github.com/JoshBoyer/profile-card-component-main.git
- Live Site URL: https://joshboyer.github.io/profile-card-component-main/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I used the pseudo-elements before and after to place the background images. Took some trial and error to get them close, but happy with how they turned out.

```css
&::before {
  content: url("/images/bg-pattern-top.svg");
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translateX(-100%) translateY(-90%);
  z-index: -1;
}
&::after {
  content: url("/images/bg-pattern-bottom.svg");
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translateX(-5%) translateY(1%);
  z-index: -1;
}
```

## Author

- Frontend Mentor - https://www.frontendmentor.io/profile/JoshBoyer
