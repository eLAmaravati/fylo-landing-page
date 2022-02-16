# Frontend Mentor - Fylo landing page with two column layout solution

This is a solution to the [Fylo landing page with two column layout challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-landing-page-with-two-column-layout-5ca5ef041e82137ec91a50f5). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./desktop-design.jpg)

### Links

- Solution URL: [https://github.com/eLAmaravati/fylo-landing-page/](https://github.com/eLAmaravati/fylo-landing-page/)
- Live Site URL: [https://elamaravati.github.io/fylo-landing-page/](https://elamaravati.github.io/fylo-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- SaSS/SCSS
- Flexbox
- CSS Grid
- Mobile-first workflow
- Vanilla JavaScript
- [Bootstrap](https://getbootstrap.com/) - CSS Framework

### What I learned

```html
<form class="site-header__form form needs-validation" novalidate>
  <label for="email" class="visually-hidden form__label">Email Address:</label>
  <div class="form__input-wrapper">
    <input
      type="email"
      id="email"
      value="Enter Your Email"
      class="form__input form-control"
    />
    <div class="invalid-tooltip">Please check your email.</div>
    <div class="valid-tooltip">Looks good!</div>
  </div>
  <button type="submit" class="btn shadow form__button">Get Started</button>
</form>
```

```css
.col-image {
  order: 1;
  margin-bottom: 30px;
}

.col-content {
  order: 2;
}
```

## Author

- Website - [langitamaravati.com](https://www.langitamaravati.com)
- Frontend Mentor - [@eLAmaravati](https://www.frontendmentor.io/profile/eLAmaravati)
- Twitter - [@eLAmaravati](https://www.twitter.com/eLAmaravati)
