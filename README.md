# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [GitHub Repository](https://github.com/atrgz/QR-Code-Component)
- Live Site URL: [AGitHub Pages Site](https://atrgz.github.io/QR-Code-Component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

My main struggle while working in this project was positioning the elements. The project has helped me gain a better understanding of the position property, and the difference between setting that property to absolute or relative.

I found specially challenging center a div vertically, this code made the trick:

```css
.container {
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
}
```

### Useful resources

- [StackOverflow](https://stackoverflow.com/questions/14123999/center-a-div-horizontally-and-vertically) - I found the answer on how to center vertically in this post.


## Author

- Frontend Mentor - [@atrgz](https://www.frontendmentor.io/profile/atrgz)