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

![](/screenshots/snap.png)

### Links

- Live Site URL: [(https://abandonedwaffle.github.io/QR-CODE-/)]

## My process

### Built with

- HTML5
- CSS
- Flexbox

### What I learned

While doing this project I had to use flexbox to position the elements properly on the page. Also I realized the importance of having a proper HTML structure for CSS.

```html

<main>

    <img src="images/image-qr-code.png" alt="qr-code-image">

    <h1>Improve your front-end<br>skills by building projects</h1>

    <p>Scan the QR code to visit Frontend<br> Mentor and take your coding skills <br>to the next level</p>
  
    
  </main>

```
```css
body{
    background-color:  hsl(212, 45%, 89%);
    font-family: 'Outfit', sans-serif;
    display:flex; 
    flex-direction:column; 
    justify-content:center;
    min-height:100vh;
    align-items: center;
    margin: 0;
    
}

img {
    max-width:100%;
    display: block;
    border-radius: 10px;
}

main{
    max-width: 325px;
    text-align: center;
    padding: 20px 15px;
    background-color: white;
    border-radius: 20px;
}

```



### Continued development

I think I have realized that I need to improve my understanding of some CSS principles such as grid as this project can be made using grid too. 



### Useful resources

- [CSS-Tricks](https://css-tricks.com/) - This helped me a lot. I really liked this webiste for CSS and will use it going forward.


## Author
- Ritesh Diwan
- Frontend Mentor - [@abandonedwaffle](https://www.frontendmentor.io/profile/abandonedwaffle)



## Acknowledgments

Thanks to front-end-mentor for this challenge. I will keep moving forward doing the challenges as they give a sense of achievement. 


