# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Social links profile solution](#frontend-mentor---social-links-profile-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot
[screenshots](./assets/webpage_live.png)

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

Here's an adjusted version for your "What I learned" and "Useful resources" sections:

### What I learned

In this project, I enhanced my understanding of several CSS properties and layout techniques:

- **Border-radius**: Applied rounded corners upto 50% to form circle and used width, height, and object-fit properties to create a perfectly circular profile picture while maintaining proper image proportions
```css
.image {
    width: 88px;
    height: 88px;
    border-radius: 50%;
    margin-bottom: 1.25rem;
    object-fit: cover;
  }
```
- **Gap property**: Used the gap property in the list container instead of applying margin-bottom to individual items, creating cleaner and more maintainable code
```css
.list {
    width: 100%;
    display: flex;
    flex-direction: column;
    gap: 1rem;
  }
  ```
- **CSS Transitions**: Implemented transform: translateY() with transitions to create a subtle floating effect when hovering over links
```css
.link {
    transform: translateY(0);
  }
  
.link:hover,
  .link:focus {
    transform: translateY(-5px);
  }
```
- **Semantic HTML**: Improved accessibility by using proper semantic elements and ensuring keyboard navigation

### Continued development

For future projects, I want to focus on:
- Expanding my knowledge of CSS Grid for more complex layouts
- Improving my understanding of accessibility features
- Learning more advanced CSS animations and transitions
- Implementing responsive design using modern techniques like clamp() and container queries

### Useful resources

- [MDN Web Docs - CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) - This comprehensive resource helped me understand the details of CSS properties like object-fit and the gap property. Their examples are clear and practical.
- [W3Schools - CSS Tutorial](https://www.w3schools.com/css/) - This site provided easy-to-follow examples for implementing hover effects and transitions. I particularly found their interactive examples helpful for understanding transform properties.
- [CSS-Tricks - A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This guide helped me properly implement the flexbox layout to structure my card component.
