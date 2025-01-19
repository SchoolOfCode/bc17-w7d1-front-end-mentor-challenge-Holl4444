# Frontend Mentor - Product preview card component solution
\
This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.\
\
\
![Design preview for the Product preview card component coding challenge](./design/desktop-preview.jpg)



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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![image](https://github.com/user-attachments/assets/9b3eb492-4210-48e2-8d41-7f8ffe9130e2)
![image](https://github.com/user-attachments/assets/ff3407e6-4d57-4e66-95e4-377082a56f26)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

Starting with the mobile version to keep in line with mobile first development.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

- Mobile-first workflow


### What I learned

Trying to stick to semantic HTML for anything except 100% style required divs.

![image](https://github.com/user-attachments/assets/656195f9-5d33-49f1-8df5-2c2f3840cea4)

Using hgroup for the first time.
```html
          <hgroup>
            <h4>PERFUME</h4>
            <h1 class="fraunces">Gabrielle Essence Eau De Parfum</h1>
          </hgroup>
```
Learning about css variables
```css
:root {
  --primary-background: hsl(30, 38%, 92%);
  --soft-green: hsl(158, 36%, 37%);
  --hover: hsl(156, 42%, 18%, 100%);
  --dark-blue: hsl(212, 21%, 14%);
  --dark-grey: hsl(228, 12%, 48%);
  --white: hsl(0, 0%, 100%);
}
```
and getting more familiar with importing fonts.

```css
@font-face {
  font-family: 'MonserratBold';
  src: url(Fonts/Montserrat-Bold.ttf);
  font-weight: 700;
}
```
a nifty trick for most browsers:\
\
![image](https://github.com/user-attachments/assets/564869f2-e516-4150-91e3-734381ce177c)

[check if you can use it](https://caniuse.com/css-all)\
\
using dev tools to check :hov\
\
![image](https://github.com/user-attachments/assets/3e147bdc-0150-4cfe-b352-12f30acd2daa)



### Continued development




### Useful resources

- [freeCodeCamp](https://www.freecodecamp.org/news/css-button-style-hover-color-and-background/#:~:text=To%20change%20the%20button's%20styles,background%2Dcolor%20of%20the%20button.) - gave me the inspiration to try transitioning the button pseudoclasses.
- [SheCodes](https://www.shecodes.io/athena/34209-how-to-create-root-variables-for-colors-in-css#:~:text=Here's%20an%20example%20of%20how,var(%2D%2Dprimary%2Dcolor)%3B%20%7D) - Clear how to for colour variables.
- [customFonts](https://www.youtube.com/watch?v=lDip-1VnaOA) - good video on font customisation.


## Author

Holly4444

## Acknowledgments

"https://www.frontendmentor.io?ref=challenge"
