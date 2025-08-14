# Frontend Mentor - Clipboard landing page solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![Screenshot of Completed Project](./design/Screenshot%20Completed%20Frontend%20Mentor%20Clipboard%20landing%20page.png)

### Links

- Solution URL: [GitHub Repository](https://github.com/Ankia-Fuls/fem-clipboard-landing-page)
- Live Site URL: [GitHub Pages](https://ankia-fuls.github.io/fem-clipboard-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- SASS Styling

### What I learned

I practiced a lot of CSS styling methods methods, especially a mix of flexbox and grid to get the desired layout. I tried to incorportate accessibility considerations into my design, including adding screenreader only paragraphs to give better context of what is happening on the page for those who cannot see. 

I also learned how to use a filter to color an SVG to get the desired hover state for the social media icons. The code below shows the filter that was used to get the desired color for this project, and the link to the site that generates this filter from a desired hex code is listed in the Useful resources section.

```css
filter: invert(57%) sepia(68%) saturate(423%) hue-rotate(122deg) brightness(92%) contrast(97%);
```

### Continued development

I would like to update this project in the future to make use of the BEM method of naming my classes since I am not happy with my current naming convention.

### Useful resources

- [Hex to filter](https://codepen.io/sosuke/pen/Pjoqqp) - This was a great tool to see what filter can be applied to an image to color it to a certain hex code.
- [Grid Auto Flow](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-auto-flow) - This helped me understand how to change the direction with which the grid fills in the HTML elements, which I used to organize the flow of the footer links.

## Author

- Frontend Mentor - [@Ankia-Fuls](https://www.frontendmentor.io/profile/Ankia-Fuls)
- GitHub - [@Ankia-Fuls](https://github.com/Ankia-Fuls)