# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![image](https://github.com/Nospiel-code/frontend-mentor-product-preview-card/assets/130290610/999881c3-8310-48d8-b86a-b7f8da6983e0)


### Links

- Solution URL: https://github.com/Nospiel-code/frontend-mentor-product-preview-card
- Live Site URL: https://nospiel-code.github.io/frontend-mentor-product-preview-card/

## My process

After doing 5 challenges on my own I decided to do this one as a code along, to see how a professional would solve this.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Using a youtube walkthrough this time, there was a lot I learned during this challenge.

Every Page should have a **main** - in this exercise it is not necessary but was included for good practice

An **article** is used when something can be a "stand-alone" piece of content. In other words can a certain content be taken out of a website and still make sense without outside information.

**BEM naming convention** uses a double underscore to indicate which elements belong together. It is used if it is unique to that element. 
*See button for difference*

The **h1** is used because there is no other content on this page. Every page should have just one h1.

The **button** class is not named product__button because it is it's own component and would like the same if it is used somewhere else.

I learned about pre-defined **CSS reset sylesheets**. Here we are using the on from [Josh Comeau](https://www.joshwcomeau.com/css/custom-css-reset/).

A way to **name colors** following the principles of font-weight; 100 (lightest color )to 900 (darkest). This helps in case we need another color we can add one in between depending depending on the value.

**Pixels should not be used for font-sizes**, this is mainly for accessibility. If a user has set the base font size of their browers to a different size, if we use rems the font changes the size based on the users settings. With pixels the size stays the same because pixels are an absolute unit.

How to set a **localy scoped custom property**. These are just available inside a certain scope. In this example just inside the article. This improves maintainability, e.g. if there need to made some changes afterwards. Defining these properties for certain classes makes it easier to find and gives the CSS a better structure.

How to use the **HTML strikethrough element** to render a text with a strikethrough. For accessibility we included spans which contain text for screen readers. Altough the text is crossed out when using the strikethrough a screen reader doesn't distinguish a text like this from a normal one.

I also learned about the **:is() pseudo-class** which allows us to simplify groupings of selectors.

**Data attributes** allow us to store extra information on standard, semantic HTML elements. We used it here to put the shopping card icon with a ::before pseudo-class in before the text of the button.

If the **HTML picture element** is used, it allows us the set an alternative source. In this case we have a picture for the mobile view and one for the desktop, so we can set the source for the desktop picture and set the media to a min-width. When we reach the min-width the image source is changend.

### Continued development

The next challenges I want to again on my own, using all the new knowledge I gathered during this challenge.

### Useful resources

- [Kevin Powell Solution Walkthrough](https://www.youtube.com/watch?v=B2WL6KkqhLQ&t=15s&ab_channel=KevinPowell) - This solution is the exact same as in this video.

## Author

- Website - [Kevin Powell](https://www.kevinpowell.co/)
- Twitter - [@KevinJPowell](https://www.twitter.com/KevinJPowell)

