# Summary-Result-Design
# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

The landing page of a result summary is given and we have to write the HTML and CSS code to make it.

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![Result_1_ss](https://user-images.githubusercontent.com/79708044/225706104-d967ff79-f794-4194-89ce-3d9770e08f51.jpg)

![Result_2_ss](https://user-images.githubusercontent.com/79708044/225706382-9d323cec-30b5-4409-b1f2-1ff9acbec29d.jpg)

### Links

- Solution URL: (https://github.com/adityalawand7/Summary-Result-Design))
- Live Site URL: (https://adityalawand7.github.io/Summary-Result-Design/)

## My process

I followed the following steps while completing this challenge:

- First I created the basic HTML structure like adding a main div and then adding 2 divs inside the main div.
- Then I started working on individual divs.
- I added the required components to each div.
- Once all the required componets were added, I started the CSS part.
- Once all the CSS was added, the last thing I did was adding box-shadow.

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

I learned a lot of new things from this challenge. Some of these are:

- Use of 'opacity' attribute can sometimes be troublesome as later on when I had to add text over the div in which I used opacity, the text would not be visible. I learned that a better option in such situation is 'rgba' attribute.

Code -->
```html
<div class="reactionBox">
  <img class="reactionImg" src="assets/images/icon-reaction.svg" alt="">
  <p class="rcn">Reaction</p>
  <div class="mrksScored">80 <span style="color:grey">/ 100</span></div>
</div>
```
```css
.reactionBox{
    background: rgba(255, 87, 87, 0.05);
}
```

- I learned how I can manipulate the box-shadow in any way I want.

Code -->
```css
.mainContainer{
  box-shadow: 3px 10px 15px 5px rgba(198, 197, 232, 0.2);
}
```

### Continued development

In this, I used only HTML and CSS which made it a static website. In the future, once I learn javascript, I plan to make it a responsive website.

### Useful resources

- [Resource 1](https://www.geeksforgeeks.org/set-the-opacity-only-to-background-color-not-on-the-text-in-css/) - This helped me with opacity issue. I liked the way they have explained the concept.


## Author

- Aditya Dadasaheb Lawand
