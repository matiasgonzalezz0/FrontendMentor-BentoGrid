# Frontend Mentor - Bento grid solution

This is my solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Solution](#solution)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to view all the content of the website in its correct layout.
To achieve this, on smaller screens, the cards are displayed vertically. On larger screens, users should see a Bento Grid layout with the contents of the page.

### Solution

#### Links

- Solution Site: [Bento Grid](https://matiasgonzalezz0.github.io/FrontendMentor-BentoGrid/)

#### Desktop Screenshots
![](./screenshots/desktop-1920x1080.png)

#### Mobile Screenshots
![](./screenshots/mobile-top.png) ![](./screenshots/mobile-bottom.png)

## My process

### Built with

- HTML5 markup
- CSS using the BEM naming convention
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I wanted to challenge myself with this project, so I decided to not use any CSS libraries or frameworks.
This forced me to recall a lot of raw CSS properties, especially grid-related ones for the Bento layout.

After setting up the HTML with SEO-friendly tags, I started naming classes. At first, I didnt follow any specific pattern, until I found out about BEM.
The vast majority of the classes (aside from a few common ones) follow that methodology.

Another key decision I had to make was whether I should start with a mobile-first or desktop-first approach. I chose mobile-first since it helped me focus on structuring the card content first, and then worry about layouts.

Lastly, when it came to media queries and breakpoints, I realized that many layout related issues didnt happen at standard devices widths, so I decided to base my breakpoints on where things actually broke instead.
One CSS function that helped a lot responsiveness was `clamp()`. I'd never used it before, but it's incredibly usefull for keeping elements at their appropiate size.


### Continued development

I tried to keep things simple while also making the HTML and CSS easy to follow (thanks to BEM). One area I could improve is to include more variables aside from colors, maybe for spacing, sizes, etc.

### Useful resources

- [CSS Tricks Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/) - Super helpfull guide/cheatsheet for everything grid-related. It helped me remeber key concepts in a very quick and comprehensive manner.
- [CSS Tricks Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Another guide by CSS Tricks, this one for Flexbox. Again, very clear and usefull.
- [Clamp Generator](https://clamp.font-size.app/) - This helped me calculate good `clamp()` values.

## Author

- GitHub - [matiasgonzalezz0](https://github.com/matiasgonzalezz0)
- Frontend Mentor - [@matiasgonzalezz0](https://www.frontendmentor.io/profile/matiasgonzalezz0)
