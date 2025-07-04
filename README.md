# Frontend Mentor - Advice generator app solution

![](./design/desktop-preview.jpg)


This is a solution to the [Advice generator app challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/advice-generator-app-QdUG-13db). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

<h2 align="center">Links</h2>

- Live Site URL: [[https://advice-generator-11.netlify.app/](https://advice-generator-11.netlify.app/)<br>

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Generate a new piece of advice by clicking the dice icon

## My process

### Built with

- Semantic HTML5 markup
- Mobile-first approach
- Vanilla JavaScript
- Flex Layout
- BEM naming convention
- [SASS](https://sass-lang.com/documentation/modules) - Sass modules

### Useful resources


- [SASS Architecture](https://sass-guidelin.es/#architecture)
- [Mobile-first approach](https://www.freecodecamp.org/news/taking-the-right-approach-to-responsive-web-design/)
- [CSS Guidelines](https://cssguidelin.es/#bem-like-naming)
- [BEM naming convention](https://css-tricks.com/bem-101/)
- [BEM naming examples](https://getbem.com/naming/)


- [Delay, Sleep, Pause, & Wait in JavaScript](https://www.sitepoint.com/delay-sleep-pause-wait/)
- [How to create a simple CSS loading spinner & make it accessible](https://codeburst.io/how-to-create-a-simple-css-loading-spinner-make-it-accessible-e5c83c2e464c)
- [Material Design Box Shadows](https://codepen.io/sdthornton/pen/wBZdXq)

- [Solving Sticky Hover States with @media (hover: hover)](https://css-tricks.com/solving-sticky-hover-states-with-media-hover-hover/)

## Author

- Frontend Mentor - [@melvinaguilar](https://www.frontendmentor.io/profile/melvinaguilar)

## Acknowledgments

When using `sass` in order to build this solution

- Install `sass` if not yet installed:

```bash
npm install -g sass
```

- Run build command from command line:

```bash
sass assets/sass/main.scss assets/css/style.css
```

- If you want to edit the code and test, in the root folder of this repository, run this command from the command line:

```bash
sass --watch assets/sass/main.scss assets/css/style.css
```

## File structure

```
.
├── assets
│   ├── css
│   │   ├── style.css
│   │   └── style.css.map
│   ├── images
│   │   ├── favicon-32x32.png
│   │   ├── icon-dice.svg
│   │   ├── pattern-divider-desktop.svg
│   │   └── pattern-divider-mobile.svg
│   ├── js
│   │   └── main.js
│   └── sass
│       ├── abstracts
│       │   ├── _animations.scss
│       │   ├── _mixins.scss
│       │   └── _variables.scss
│       ├── base
│       │   ├── _page.scss
│       │   └── _reset.scss
│       ├── component
│       │   ├── _attribution.scss
│       │   ├── _buttons.scss
│       │   ├── _screen-reader.scss
│       │   └── _spinner.scss
│       ├── layout
│       │   └── _card.scss
│       └── main.scss
├── design
│   ├── active-states.jpg
│   ├── desktop-design.jpg
│   ├── desktop-preview.jpg
│   ├── mobile-design.jpg
│   └── screenshot.png
├── index.html
└── README.md
```
