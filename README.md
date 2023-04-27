# Frontend Mentor - Fylo Data Storage Component Solution

This is a solution to the [Fylo Data Storage Component Challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

This is my solution to the fylo data storage component challenge on [Frontend Mentor](https://www.frontendmentor.io/home). It was built with HTML and CSS properties.

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

This is what my solution looks like on mobile devices and desktop

![](/images/desktop_solution.png)

<div align="center">

![](/images/mobile_solution.png)

</div>


### Links

- Solution URL: [My solution on Frontend Mentor](https://www.frontendmentor.io/solutions/fylo-data-storage-component-solution-MuYoSyGMTZ)
- Live Site URL: [My live solution](https://itsale-o.github.io/fylo-data-storage-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

With this project I learned how to build one of those dialog bubbles from scratch, using only CSS properties.

```css
.bubble {
        border-radius: 10px 10px 0 8px;
        z-index: 1;
        top: 20px;
        left: 300px;
    }
    
    .bubble:before {
        content: "";
        position: absolute;
        border-left: 10px solid transparent;
        border-right: 10px solid white;
        border-top: 10px solid white;
        border-bottom: 10px solid transparent;
        right: 0px;
        top: 50px;
    }
```

### Useful resources

- [W3 Schools](https://www.w3schools.com/) - It's an educatinal website that helps newbie coders. There are tutorials and references about everything you might need. It is very helpful  
- [Converting Colors](https://convertingcolors.com/) - Particullarly I like to call the colors on my CSS code by its HEX code (not always the best choice though). This website converts the code for you from any format you have to any format you like. By now, it is my favorite..

## Author

- Frontend Mentor - [@itsale-o](https://www.frontendmentor.io/profile/itsale-o)
- LinkedIn - [alessandra-santos-oliveira](https://www.linkedin.com/in/alessandra-santos-oliveira/)
- Twitter - [@itsale_o](https://www.twitter.com/itsale_o)
