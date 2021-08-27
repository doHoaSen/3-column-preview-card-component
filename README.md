# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- See hover states for interactive elements

### Screenshot

<center>
  
![Screenshot-desktop](/images/Screenshot-desktop.png)
  
![Screenshot-mobile](/images/Screenshot-mobile.png)

</center>


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
I designed Mobile version first to simplify my code. I used to make desktop design but this time, I tried to code simply. I am quite satisfied with my result. 

Mobile version -> desktop version with responsive design.


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

 This is second time to practice responsive design and I think I am quite developing my skills. Process with making mobile design and then revising with desktop design is much more convenient.

Here are some snippets that I learned from this challenge:

>To add favicon, use <link>tag

```html
<link rel="icon" type="image/png" sizes="32x32" href="images/favicon-32x32.png">
```
>I used CSS grid box to make layout convenient. This is very simple way to layout the design.

```css
.main-box{
    width: 70%;
    margin: 0 auto;
    padding: 5% 0;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: 1fr;
    grid-template-areas: "box1 box2 box3";
  }

  .box1{
    grid-column-start: 1;
  }

  .box2{
    grid-column-start: 2;
  }

  .box3{
    grid-column-start: 3;
  }
}
```



### Continued development

Use CSS grid box more often to layout beautiful design easily.



## Author

- Website - [Amelia Kang](https://www.your-site.com)
- Frontend Mentor - [@doHoaSen]
(https://www.frontendmentor.io/profile/doHoaSen)



