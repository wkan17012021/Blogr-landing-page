# Blogr landing page solution

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

Requested to do this FEM challenge as part of the apprenticeship program I was doing at the time. The aim was to learn about version control: git commands, opening a feature branch and making commits to it then finally merging into main. It was also to keep practicing html and css.

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

## My process

I thought this would be a couple of hours so I imported the BS5 library hoping that I could quickly build this out. It was helpful for the dropdown list navigation menu items. But for the rest of the markup and styling, it slowed me down and I ended up rewriting styles, looking up mapped BS classnames etc.

For the other copy sections, it was a case of using normal flow on mobile and flex on desktop. But, it didn't work out so well for the overlay images and media which appears off screen. Maybe I will come back to this in the future but for part of the learning journey, it feels like diminishing returns.

The pain points were:

- Haven't spent time on how SVGs work and not that sure on overlaying content. So, the image in the hero CTA section was not done
- The images that appear partly off the page, I don't know how that is done
- 'State of the Art Infrastructure' section with image offset and circles underlay as well as making the section responsive, not sure how that is done

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

## Author

wkan17012021

## Acknowledgments

There is a better solution here but I didn't want to lift the code as I don't know how the images work offset from other elements or the svg / circle overlays work:
https://codepen.io/wearepixeltocode/pen/BarxQPe
