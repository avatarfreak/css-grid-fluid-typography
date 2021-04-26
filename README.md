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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

- #### **_Mobile screen min-width: 375px_**

  ![Alt](/screenshot/mobile.jpg "Mobile min-width(375px)")
  <br /><br />

- ### **_Tablet screen min-width: 768px_**

  ![Alt](/screenshot/tablet.jpg "Tablet min-width(768px)")
  <br /><br />

- ### **_Desktop screen min-width: 1140px_**

  ![Alt](/screenshot/desktop.jpg "Desktop min-width(1140px)")
  <br /><br />

### Links

- Solution URL: [https://github.com/avatarfreak/css-grid-fluid-typography.git](https://github.com/avatarfreak/css-grid-fluid-typography.git)
- Live Site URL: [https://avatarfreak.github.io/css-grid-fluid-typography/](https://avatarfreak.github.io/css-grid-fluid-typography/)

## My process

### Built with

- Semantic HTML5 markup
- sass
- Flex-box
- CSS Grid
- Mobile-first workflow

### What I learned

It was great learning. Sometimes even the simplest things is hard to conquer.Initially, I was bit off-track regarding styling, not knowing what to choose? I could have easily opt for any css framework but afterthought decided to go with basic workflow using flex-box and css-grid. In order to hone my skills.  
Here in a nutshell, I got an opportunity to brainstorm css grid, flex-box and fluid typography.

Look below the things I was able to implemented:

- For **_Responsive image media_** `<Picture></Picture>` elements is used.

```html
<picture>
  <source media="(min-width: 768px)" srcset="picture.jpg" />
  <img src="picture.jpg" alt="picture" />
</picture>
```

- For **_Responsive Font_** `calc(min-font-size + (max-font-size - min-font-size) * ((100vw - min-view-port) / (max-view-port - min-view-port))); `

```css
font-size: calc(15px + (20 - 15) * ((100vw - 375px) / (1440 - 375)));
```

### Useful resources

- [CSS Grid Layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout) - This article helped me to reinforce ideas about css grid layout.

## Author

- Website - [dave](https://www.pigoat.com)
- Frontend Mentor - [@avatarfreak](https://www.frontendmentor.io/profile/avatarfreak)
- github - [avatarfreak](https://github.com/avatarfreak)
