This is my portfolio page
## Table of contents

- [Overview]
  - [The challenge]
  - [Screenshot]
  - [Links]
- [My process]
  - [Built with]
  - [Continued development]
  - [Useful resources]
- [Author]
- [Acknowledgments]


## Overview

### The challenge

 Users should be able to:

 - View the optimal layout for the website depending on their device's screen size
- See hover states for all interactive elements (nav section) on the page
- Hover and feel how website animation changes the details
- Visualize what page he/she is on the page
- See and able to navigate to an ‘About me’ page


### Screenshot
chrome-extension://mcbpblocgmgfnpjjppndjkmgjaogfceg/fsCaptured.html#

### Links
## [Website Preview](https://josh-adey.github.io/portfolio/)


## My process

### Built with
HTML 5 Divs
CSS3
CSS Flexbox
CSS Grid  
Javascript


### What I learned
   ```html divs and nesting
<div class="container">
     <div class="nav-wrapper">
        <div class="left-side">
           <div class="nav-link-wrapper  active-nav-link">

```CSS animation
.img-darken{
	transition: 1s;
	filter:  brightness(10%);
}

```CSS hover-state
.nav-link-wrapper:hover{
border-bottom: 1px solid black;
 }

 ```js animation
const portfolioItems = document.querySelectorAll(".portfolio-item-wrapper")
      
      portfolioItems.forEach(portfolioItem => {
           portfolioItem.addEventListener('mouseover', () => {
               portfolioItem.childNodes[1].classList.add('img-darken');
           })
……
})

### Continued development
  I hope to grow my skills in Javascript functions and DOMs.

### Useful resources
 Jordan Hughes’s HTML5_CSS Dev tutorial on Udemy
## Author
Name-  Adeoye Joshua (my git hub link)
Twitter- themanJosh


## Acknowledgments
Credit goes to Jordan Hughes. 
