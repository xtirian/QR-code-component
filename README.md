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
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./images/screenshots/mobile.png)

![](./images/screenshots/web.png)

### Links

- Solution URL: [GitHub Repository](https://github.com/xtirian/QR-code-component)
- Live Site URL: [Live Site](https://qrcode-xtirian.netlify.app/)

## My process

At first sight I draw in a paper the page dividing the divs an figured out how to mantain the effects. So I coded the HTML and then the CSS. 
The only issue I had wa to maintain the size of the card in the mobile and web version. The solution was add the property below:

```CSS
.card {
 max-width: 290px
 }
```

I choose to stay this in a static width so it don't grow too much when pass from mobile to web; and I preferred to use the 'max-width' instead the width in case of any device with frame below 375px

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first

### Continued development

I'd still learning about how to name classes and id, how to organize that and improve my workflow.

It's a simple things but when I'm writing the HTML, my mind give me insight to what to do in the CSS, so I go and code the CSS. I know this is wrong and sometimes this take my time alway while I just look for the code thinking about different ways to do the same thing.

## Author

- Website - [Matheus Fernandes](https://xtirian.netlify.app/)
- Frontend Mentor - [@xtirian](https://www.frontendmentor.io/profile/xtirian)
- LinkedIn - [@mf-cunha](https://www.linkedin.com/in/profile/mf-cunha/)

