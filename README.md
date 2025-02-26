# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
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

### Screenshot

![Desktop View](./design/desktop-design.jpg)  
![Mobile View](./design/mobile-design.jpg)

### Links

- Solution URL: (https://github.com/zardrick/qr-code-component)
- Live Site URL: (https://zardrick.github.io/qr-code-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

This challenge helped me practice responsive design techniques, specifically ensuring a **portrait layout** on smaller screens. I also improved my understanding of **media queries** and how to adapt component sizes dynamically. Below is an example of a media query I used:

```css
@media (max-width: 600px) {
    .component-container {
        width: 80%;
        max-width: 320px;
        height: 75vh;
        max-height: 500px;
        gap: 20px;
    }
```

### Continued development

I plan to continue improving my responsiveness skills by working on more **mobile-first designs** and experimenting with **CSS Grid** in future projects.

### Useful resources

- [MDN Web Docs - Media Queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries) - Helped me refine my media query logic.
- [CSS Tricks - Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Helped me structure the layout efficiently.

## Author

- Frontend Mentor - [@zardrick](https://www.frontendmentor.io/profile/zardrick)
- Github - [@zardrick](https://github.com/zardrick)
- Twitter - [@zardrick1](https://x.com/zardrick1)

## Acknowledgments

Special thanks to the **Frontend Mentor community** for providing great challenges that help improve coding skills. Also, thanks to those who reviewed and gave feedback on my solution!

