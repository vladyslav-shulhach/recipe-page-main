# Frontend Mentor - Recipe Page solution

This project is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). These challenges are designed to enhance coding skills through building practical, real-world projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### Screenshot

![Screenshot of the project](./preview.png)

### Links

- Solution URL: [here](https://www.frontendmentor.io/solutions/recipe-page-solution-qXhAmi9siQ)
- Live Site URL: [here](https://recipe-page-main-six-blond.vercel.app/)

## My process

### Built with

- Semantic HTML
- CSS
- Flexbox
- Mobile Version


### What I learned

**`li::marker`:**
   - This pseudo-element targets the list item markers (`<li>`). It lets you change the way the list bullets look, for example, by changing their colour or size.

   ```css
   li::marker {
    color: var(--brown-800);
    font-size: 0.8rem;
    font-weight: var(--bold-font-weight);
    }
   ```

**`:not(:last-of-type)`:**
  - This selector is a combination of (`:not`) and (`:last-of-type`). It selects all elements except the last-of-type in the parent element. That is useful for styling elements that are not the last of a group.

**`:nth-child()`:**
  - The `:nth-child()` selector allows you to target elements based on their order within a parent. It is particularly useful when you want to style specific items without adding extra classes. In this case, the selector is used to apply styles to the second child of elements with the `.nutrition__cell` class.

   ```css
   .nutrition__cell:nth-child(2) {
       font-weight: bold; /* Makes the second cell text bold */
       color: var(--brown-800); /* Changes the text color to a predefined brown shade */
   }
   ```


## Author

- Frontend Mentor - [Vladyslav Shulhach](https://www.frontendmentor.io/profile/Vladyslav-Shulhach)
