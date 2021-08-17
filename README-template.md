# Frontend Mentor - Launch countdown timer solution

This is a solution to the [Launch countdown timer challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/launch-countdown-timer-N0XkGfyz-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover states for all interactive elements on the page
- See a live countdown timer that ticks down every second (start the count at 14 days)
- **Bonus**: When a number changes, make the card flip from the middle



**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

i learn from this test the advance javascript methodologies.
done design with HTML5,CSS3, SCSS

To see how you can add code snippets, see below:

```html
   <div class="bg-gradient">
        <h1>WE'RE LAUCHING SOON</h1>
        <div id="CDT"></div>
    </div>
    <footer style="flex-direction: column;">
        <div class="social-items">
            <img src="./images/icon-facebook.svg" alt="">
            <img src="./images/icon-pinterest.svg" alt="">
            <img src="./images/icon-instagram.svg" alt="">
        </div>
        <div class="attribution " style="margin-top: 15px;">
            Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. Coded by <a href="#">Raul Sanz</a>.
        </div>
```
```css
@import url('https://fonts.googleapis.com/css2?family=Red+Hat+Text&display=swap');
body {
    background:hsl(234, 17%, 12%);
    text-align: center;
    height: 100vh;
    background-repeat: no-repeat;
    font-family: 'Red Hat Text', 'sans-serif';
    font-size: 14px;
}

.bg-gradient {
    height: 80%;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    background-image: url('../images/bg-stars.svg');
}

h1 {
    margin: 0;
    color: #eee;
    -moz-text-shadow: 0 3px 3px #000000;
    -webkit-text-shadow: 0 3px 3px #000000;
    text-shadow: 0 3px 3px #000000;
    font-size: 30px;
    margin: 0 0 10px;
    line-height: 1;
    text-align: center;
    font-family: 'Red Hat Text', 'sans-serif';
}

h2 {
    margin: 0;
    color: #eee;
    -moz-text-shadow: 0 3px 3px #000000;
    -webkit-text-shadow: 0 3px 3px #000000;
    text-shadow: 0 3px 3px #000000;
    font-size: 18px;
}

#CDT {
    font-size: 60px;
    color: #F15D8F;
    margin: 70px 0 100px;
    .number-wrapper {
        margin: 10px;
        position: relative;
    }
    .number {
        display: inline-block;
        *display: inline;
        -moz-background-clip: padding;
        -webkit-background-clip: padding-box;
        background-clip: padding-box;
        padding: 0 12px;
        height: 80px;
        line-height: 80px;
        background: #2B2C44;
        text-align: center;
        border-radius: 5px;
        &:before {
            content: "";
            position: absolute;
            bottom: 0;
            right: 0;
            border-top: 29px solid hsl(234, 17%, 12%);
            border-left: 0px solid transparent;
            border-right: 27px solid transparent;
            transform: rotate( -46deg);
            transform-origin: 25% -85% 0;
        }
        &:after {
            content: "";
            position: absolute;
            bottom: 0;
            right: 0;
            border-top: 29px solid hsl(234, 17%, 12%);
            border-right: 0px solid transparent;
            border-left: 27px solid transparent;
            transform: rotate( 45.65deg);
            transform-origin: -50% -340% 0;
        }
    }
    .line {
        position: absolute;
        width: 100%;
        height: 1px;
        top: 52%;
        left: 0;
        background: #000;
        -moz-box-shadow: 0 1px 0 rgba(255, 255, 255, 0.2);
        -webkit-box-shadow: 0 1px 0 rgba(255, 255, 255, 0.2);
        box-shadow: 0 1px 0 rgba(255, 255, 255, 0.2);
    }
}

.caption {
    font-size: 12px;
    position: absolute;
    bottom: -30px;
    left: 0;
    text-align: center;
    width: 100%;
    color: #777;
}

footer {
    height: 20%;
    display: flex;
    justify-content: center;
    align-items: center;
    background-image: url('../images/pattern-hills.svg');
    background-repeat: no-repeat;
    background-size: cover;
    .social-items {
        display: flex;
        width: 180px;
        height: 35px;
        justify-content: space-between;
    }

}

```
```js
function CountdownTimer(elm, tl, mes) {
    this.initialize.apply(this, arguments);
}
```

 
**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development



**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

Done the work with proper flow and learn advance things durring working on this work.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
