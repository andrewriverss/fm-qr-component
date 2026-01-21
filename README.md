# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - QR code component solution](#frontend-mentor---qr-code-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
  - [Author](#author)

## Overview

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [Solution URL here](https://www.frontendmentor.io/solutions/qr-code-component-4rlAxSsY3i)
- Live Site URL: [Live site URL here](https://andrewriverss.github.io/fm-qr-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

For this project instead of taking the approach of using random paddings and margins, I've prefer to make some elements a flex containers so the spacing and gap between the image and texts are more precise. And have added a text-wrapper with some properties that gives my code a more similar look to the original design.

```css
.text-wrapper {
  padding: 0 0.625rem 1.25rem;
  display: flex;
  flex-direction: column;
  gap: 1rem;
}
```

### Continued development

I will continue to refine the speed of development and the ability to recognise when to use Flexbox.

### Useful resources

- [A more modern CSS Reset](https://piccalil.li/blog/a-more-modern-css-reset/) - This helped me to establish the base CSS Reset code and I just added margin 0 & padding 0.

## Author

- Website - [Andres Rios](https://andrewriverss.github.io/portfolio/)
- Frontend Mentor - [@andrewriverss](https://www.frontendmentor.io/profile/andrewriverss)
