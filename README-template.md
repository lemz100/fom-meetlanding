# Frontend Mentor - Meet landing page solution

This is a solution to the [Meet landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

```less
.hero-images {
    width: 100vw;
    display: contents;
    .hero-right {
        order: 2;
        position: relative;
        left: 127px;
        top: 57px;
    }
    .hero-left {
        position: relative;
        left: -180px;
    }
}
```
```html
    <section class="content">
        <figure class="hero-images">
          <img src="./assets/desktop/image-hero-left.png" alt="left hero" class="hero-left">
          <img src="./assets/desktop/image-hero-right.png" alt="right hero" class="hero-right">
        </figure>
        <article class="text-content">
          <p class="hero-header">Group Chat for Everyone</p>
          <p class="hero-desc">Meet makes it easy to connect with others face-to-face virtually and collaborate across any device.</p>
          <div class="links">
            <a class="blue" href="#">
              <p class="link-text">
                <span class="text">Download</span> <span class="version">v1.3</span>
              </p>
            </a>
            <a class="purple" href="#"><p class="link-text">What is it?</p></a>
          </div>
        </article>
    </section>
```

Figured out how to re-position the hero images as if there were 3 children in the hero section by using display: contents. Manipulated the page without touching the HTML.


## Author

- Frontend Mentor - [@lemz100](https://www.frontendmentor.io/profile/lemz100)
