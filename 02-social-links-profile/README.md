# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./img/02%20social%20links%20profile-frontend%20mentor.png)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

Learned to make look alike buttons with anchor tags, i was facing difficulties making them the same width but later i realized i should make them block element and this solved the problem

```css
li a {
  display: block;
  background-color: hsl(0, 0%, 20%);
  margin: 20px 80px;
  padding: 20px 0;
  border-radius: 8px;
  font-weight: 600;

  transition: background-color 0.15s, color 0.15s;
}
li a:hover {
  background-color: hsl(75, 94%, 57%);
  color: hsl(0, 0%, 12%);
}
```

## Author

- Author - Saroj Shrestha
- Twitter - [@AliG08134014](https://www.twitter.com/AliG08134014)
