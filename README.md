# Frontend Mentor - Social media dashboard with theme switcher

![Design preview for the Social media dashboard with theme switcher coding challenge](./design/desktop-preview.jpg)

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

![Design preview for the Social media dashboard with theme switcher coding challenge](./design/desktop-preview.jpg)

Users should be able to:

- Toggle color theme to their preference
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./design/desktop-design-step-1.jpg)

### Links

- Solution URL: [Solution URL](https://github.com/akshaymagrani/webDev-j1-Social-media-dashboard-theme-change)
- Live Site URL: [Live site URL](https://web-dev-i-multi-step-form.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

I learnt to define the ```@mixins``` which are like functions in SASS and utilize them with the help of ```@include``` later in the code. 

To see how you can add code snippets, see below:

```css
@mixin card{
    padding: 1em;
    margin: 1em;
    border-radius: 5px;
    text-align: center;
    max-width: 275px;
    min-width: 275px;
    position: relative;
    cursor: pointer;
    display: flex;
}
/* later in the code */
.card{
    background-color: $Card-L-BG;
    @include card;
}
...
.border-top-in {
    position: absolute;
    background: linear-gradient(to left, hsl(37, 97%, 70%), hsl(329, 70%, 58%));
    height: 5px;
    width: 100%;
    top: 0;
    left: 0;
    z-index: 1;
    border-top-left-radius: 5px;
    border-top-right-radius: 5px;
}
```

### Continued development

I would like to perform this in future:

1. Connecting the front-end with actual data from social-media accounts.
2. Using more SASS commands.

## Author

- Website - [Akshay Magrani](https://www.your-site.com)
- Frontend Mentor - [@akshaymagrani](https://www.frontendmentor.io/profile/akshaymagrani)
