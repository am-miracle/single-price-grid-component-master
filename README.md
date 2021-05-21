# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Single price grid component solution](#frontend-mentor---single-price-grid-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
  - [Author](#author)
  - [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

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

### What I learned

I learnt how to use superscript eg. per month (i was able to move it up )
I learnt how to use flex,grid and pixels
I learnt how to make a website responsive (mobile webite-desktop)

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<h1><p><span>&dollar;29</span><span><sup>per month</sup></span></p></h1>
```
```css
section{
    min-height: 100vh;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: hsl(204, 43%, 93%);
    padding: 100px 30px;
}
```
```deskop design
@media only screen and (min-width: 768px){
     .container{
         grid-template-columns: 1fr 1fr;
     }
     .item-1{
         grid-area: 1/ 1/ 2/ 3;
     }
     .item-2,.item-3{
         grid-row: 2;
     }
 }


If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.


### Continued development

-flex
-grid
-units

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.


## Author

- Website - [Jude Miracle](https://www.your-site.com)
- Frontend Mentor - [@andreas=15](https://www.frontendmentor.io/profile/andreas=15)
- Twitter - [@Dare_dev](https://www.twitter.com/Dare_dev)

## Acknowledgments

youtube vidoes really helped