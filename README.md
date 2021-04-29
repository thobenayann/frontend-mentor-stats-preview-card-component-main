# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Stats preview card component solution](#frontend-mentor---stats-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
  - [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

- Desktop screenshot :
  
![desktop-screenshot](images\desktop-screenshot.jpg)

- Mobile screenshot :
  
![mobile-screenshot](images\mobile-screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://github.com/thobenayann/frontend-mentor-stats-preview-card-component-main)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- HTML
- CSS (without pre-processor)
- Flexbox

### What I learned

I learned how to change the background color of an image to CSS.

```html
<section class="imageSection">
  <img class="imageSection__img" src="images\image-header-desktop.jpg" alt="working people illustration">
</section>
```
```css
.imageSection {
    background-color: hsl(277, 64%, 61%);
    ...
}

.imageSection__img {
    mix-blend-mode:multiply;
    filter : opacity(75%);
    ...
}
```

## Author

- Website - [Yann Thobena](https://thobena-yann-developpeur-web.netlify.app/)
- Frontend Mentor - [@thobenayann](https://www.frontendmentor.io/profile/thobenayann)
- Linkedin - [Yann Thobena](https://www.linkedin.com/in/yannthobena/)
