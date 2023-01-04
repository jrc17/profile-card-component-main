# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
- [The challenge](#the-challenge)
- [Links](#links)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

Build a profile card component using HTML and CSS

### The challenge

- Build out the project to the designs provided

### Links

- Solution URL: (https://github.com/jrc17/profile-card-component-main)
- Live Site URL: (https://jrc17.github.io/profile-card-component-main/)

### Built with

- HTML5
- CSS
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Instead of using percentage to position the backgroung image, use vh and vw, to position the images relative to the viewport and they won't shift.

```css:
body {
  background-color: #19a2ae;
  font-family: "Kumbh Sans", sans-serif;
  line-height: 1;
  min-height: 100vh;

  display: grid;
  place-content: center;
  justify-items: center;
  gap: 1rem;

  background-image: url("images/bg-pattern-top.svg"),
    url("images/bg-pattern-bottom.svg");
  background-repeat: no-repeat;
  background-position: bottom 40vh right 50vw, top 40vh left 50vw;
}
```

## Author

- Frontend Mentor - [@jrc17](https://www.frontendmentor.io/profile/jrc17)

## Acknowledgments

Positioning the background image was tricky. I referred to
Hatem Henchir's solution (https://www.frontendmentor.io/solutions/profile-card-component-solution-rwvbQN2j8s), to do this.
