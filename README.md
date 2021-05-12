# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

- Build out the project to the designs provided

### Links

- Solution URL: [Solution on Frontend Mentor](https://www.frontendmentor.io/solutions/awesome-profile-card-eCn2U6SXd)
- Live Site URL: [Github Pages Link](https://landon345.github.io/frontendmentor-profile-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

In this project, I learned how to add more than one background image and position them accordingly. I also learned about relative position for my profile image.

```html
<div class="card">
  <div class="bg-img">
    <img src="./images/image-victor.jpg" alt="Victor" class="profile" />
  </div>
  <div class="white">
    <div class="profile-info">
      <div class="name-age">
        <h3 class="name">Victor Crest <span class="age">26</span></h3>
      </div>
      <p class="location">London</p>
    </div>
    <div class="line"></div>
    <div class="stats">
      <div class="follow whole-stat">
        <h3 class="stat">80K</h3>
        <p class="description">Followers</p>
      </div>
      <div class="likes whole-stat">
        <h3 class="stat">803K</h3>
        <p class="description">Likes</p>
      </div>
      <div class="photos whole-stat">
        <h3 class="stat">1.4K</h3>
        <p class="description">Photos</p>
      </div>
    </div>
  </div>
</div>
```

```css
body {
  font-family: "Kumbh Sans", sans-serif;
  background-color: hsl(185, 75%, 39%);
  background-image: url("./images/bg-pattern-top.svg"),
    url("./images//bg-pattern-bottom.svg");
  background-repeat: no-repeat;
  background-position: -650px -500px, right -650px bottom -600px;
  font-size: 18px;
}
```

### Useful resources

- [CSS tricks for background position](https://css-tricks.com/almanac/properties/b/background-position/) - This helped me position my background images.

## Author

- Website - [Landon Schlangen](https://www.landonschlangen.com)
- Frontend Mentor - [@Landon345](https://www.frontendmentor.io/profile/Landon345)
- LinkedIn - [Profile](https://www.linkedin.com/in/landon-schlangen-a3989a16b/)

## Acknowledgments

I complete this one on my own in about 1 hour.
