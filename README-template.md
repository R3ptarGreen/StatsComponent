# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./images/Screenshot%20Stats%20preview%20card%20component.png)
![](./images/Captura%20de%20pantalla2.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- CSS Responsive

### What I learned

I learnd how to use "background-image" a litle bit more 
comfortable with some layer to make funy opacity.

The most dificult part was the responsive mobile, specially the layout, I tried to do it with grid display and I failed. So that's explain why I use flex display.


```css
@media (max-width: 800px){
      .container{
        width: 280px;
        height: 670px;
        display: flex;
        flex-direction: column-reverse;
    }
    .info{
        width: 280px;
        height: 500px;
        padding: 2rem;
        padding-top: 0;
        padding-bottom: 0.5rem;
    }
    .benefits h1{
        font-size: 1.4rem;
        width: 100%;
        margin-bottom: 1rem;
        color:white;
        text-align: center;
    }
    .benefits{
        width: 100%;
        margin-top: 2rem;
        color: hsla(0, 0%, 100%, 0.75);
    }
    .benefits p{
        text-align: center;
        font-size: 14px;
    }
    .numbers{
        margin-top: 0;
        grid-template-columns: auto;
        place-items: center;
        text-transform: uppercase;
        text-align: center;
    }
    .numbers p{
        font-size: 12px;
        padding: 5px;
    }
    .image{
        width: 100%;
        height: 200px;
        background-image: url(./images/image-header-mobile.jpg);
        background-size: 100%;
    }
    .layer{
        width: 100%;
        height: 100%;
        opacity: 0.6;
        background-color: hsl(277, 98%, 26%); 
    }
}
```

### Continued development

I would like continued development grid display

### Useful resources

- [Wh3scools](https://www.w3schools.com/) - This page is awesome if you want to find specific things, I recommended a lot.

## Author

- Frontend Mentor - [@R3ptarGreen](https://www.frontendmentor.io/profile/yourusername)

## Acknowledgments

I'm studying by myself in FreeCodeCamp and I'm improving my skills with Frontend Mentor

