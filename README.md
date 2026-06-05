# Frontend Mentor - Social links profile solution

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
 
- [Author](#author)


## Overview

### The challenge

### Screenshot

![Preview](/assets/images/screenshot.png)

### Links

- Solution URL: [Social_Link_Profile](https://github.com/David-VB03/Social_Links_Profile)
- Live Site URL: [Pendiente](https://google.com/)

## My process

### Built with

- Semantic HTML5 markup
- BEM Notation
- CSS variables
- Mediaqueries

- CSS Flexbox
### What I learned

I learned how to improve my variables's names in css and using another html tags with a property classes
and learning how to add accesibility for people with disabilities .
I built the components with css flexbox and used to code a unordered list to group the links.
And Finally I use css pseucode for css transitions when mouse is hovered by seomthing element and 
when I whould use relative unites like px,em,rem .
To see how I could to create the main profile, see below:


```css
.container{
   display: flex;
   flex-direction: column;
   align-items: center;
   margin-block-start: 1rem;
   margin-block-end: auto;
    
}
.container__content{
    min-width: 80%;
    max-width: 23rem;
    display: flex;
    flex-direction: column;
    padding: 0.9rem;
    background-color: var(--gray-800-color);
    color: var(--white-color);
    gap: 0.7rem;
    text-align: center; 
    border-radius: 0.5rem;
   text-align: center;
}

ul> li>a:hover{
    
    background-color: var(--green-color);
    color: var(--gray-900-color);
    cursor:pointer;
}
```



### Continued development

Please, Leave down a comment or feedback about my project , Thanks.



### Useful resources

- [HTML Docs](https://developer.mozilla.org/en-US/docs/Web/HTML) - This helped me for template my html
- [CSS Docs](https://developer.mozilla.org/en-US/docs/Web/CSS) - This helped me for understand how work a property or class in css


## Author

- Frontend Mentor - [@DavidVb](https://www.frontendmentor.io/profile/David-VB03)
- Linkedln - [@Davidvb-03](https://www.linkedin.com/in/rey-david-velasquez-baylon-340943247/)


