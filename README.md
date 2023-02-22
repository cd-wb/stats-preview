# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

![](./images/desktop.png)	

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- add a color to the image  

### Links

- Solution URL: [Solution URL](https://github.com/cd-wb/stats-preview)
- Live Site URL: [live site URL](https://cd-wb.github.io/stats-preview/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile workflow

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
      <picture class="img">
        <source srcset="images/image-header-desktop.jpg" media="(min-width:1000px)">
        <img src="images/image-header-mobile.jpg" alt="">
        <div class="color"></div>
      </picture>
```
```css
img{
    height: 100%;
    mix-blend-mode: multiply;
}
.img{
    background-color: hsl(277, 64%, 61%);
    position: relative;
}
.color{
    background-color: hsl(277, 64%, 61%);
    width: 100%;
    height: 100%;
    position: absolute;
    top: 0;
    left: 0;
    opacity: 0.2;
}   
```

## Author

- Frontend Mentor - [Abdessamad](https://www.frontendmentor.io/profile/cd-Wb)
