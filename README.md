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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

This challenmge which was carried out will enable the users view the optimal layout depending on their device screen size.

### Screenshot

![Desktop View](project.screenshot/screenshot-desktop.jpeg)

_A screen shot of the desktop view_

![Mobile View](project.screenshot/screeshot-mobile.jpeg)

_A screen shot of the mobile view_

### Links

- Solution URL: [Add solution URL here](https://github.com/stephenikuomola/stats-preview-card-component)
- Live Site URL: [Add live site URL here](https://stephenikuomola.github.io/stats-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

Using the picture element to set different images at different breakpoints. See the code snippet below;

```html
<picture class="bg_img">
  <source media="(min-width: 729px)" srcset="images/image-header-desktop.jpg" />
  <img
    src="images/image-header-mobile.jpg"
    alt="three women at coffe shop working"
  />
</picture>
```

I also learnt about the mix-blend-mode which was applied to the image to give it the color. The code snippet for that can be seen below;

```css
.bg_img {
  background-color: var(--soft-violet);
}

.bg_img > img {
  filter: opacity(75%);
  mix-blend-mode: multiply;
  width: 100%;
  height: 100%;
}
```

### Continued Development

The use of this mix-blend mode is something I can't say I am very comfortable with, so it will be practised in more future projects.

### Useful resources

- [Kevin Powell](https://www.youtube.com/watch?v=TAA89nkEuhw) - This tutorial video was beneficial as its where I was able to figure out how to use the mix-blend-mode to make then image appear the way it did.
- [CSS-Tricks](https://css-tricks.com/almanac/properties/m/mix-blend-mode/) - This is a fantastic article which helped me as well when trying to figure out how to the mix-blend mode property works.

## Author

- Twitter - [@\_salutDami](https://www.twitter.com/stephenikuomola)
- Linkedin- [Ikuomola Stephen](https://www.linkedin.com/in/ikuomola-stephen/)
- Frontend Mentor - [@salutDami](https://www.frontendmentor.io/profile/stephenikuomola)
