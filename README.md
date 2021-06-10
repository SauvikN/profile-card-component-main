# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Useful resources](#useful-resources)
-   [Author](#author)

## Overview

### The challenge

-   Build out the project to the designs provided

### Links

-   Solution URL: [Github Solution](https://github.com/SauvikN/profile-card-component-main.git)
-   Live Site URL: [Netlify Live Site](https://cocky-elion-50ed08.netlify.app/)

## My process

I first added the HTML tags to give structure to the website and so that i can properly use the CSS box model. Then I added CSS styles using a mobile-first design and then made it desktop friendly using media queries.

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox
-   CSS Grid
-   Mobile-first workflow

### What I learned

```css
body {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    background-color: hsl(185, 75%, 39%);
    min-height: 100vh;
    font-family: "Kumbh Sans", sans-serif;
    background-image: url("images/bg-pattern-top.svg"),
        url("images/bg-pattern-bottom.svg");
    background-repeat: no-repeat;
    background-position: right 48vw bottom 40vh, left 42vw top 50vh;
}
```

### Useful resources

-   [Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web/CSS/background-image) - great stuff.

## Author

-   Frontend Mentor - [@SauvikN](https://www.frontendmentor.io/profile/SauvikN)
-   GitHub - [@SauvikN](https://github.com/SauvikN)
