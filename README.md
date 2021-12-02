
# Huddle landing page with single introductory section. Responsive landing page with semantic HTML.

## Table of contents

-   [The challenge](#the-challenge)
    -   [Screenshot](#screenshot)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Continued development](#continued-development)
    -   [Author](#what-i-learned)

## Overview

### The challenge

Users should be able to:

-   View the optimal layout for the page depending on their device's screen size
-   See hover states for all interactive elements on the page

### Screenshot

![](./src/design/solution_screenshot.png)

### Links

- [Live site](https://angeliquedf.github.io/huddle-landing-page-with-single-introductory-section-master/)
- [Solution repo](https://github.com/angeliquedf/huddle-landing-page-with-single-introductory-section-master)
- [Challenge page](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0)

## My process

-   Build the HTML with semantic markup.
-   Add CSS for styling and responsiveness.
-   Test the layout for browser inconsistencies.

### Built with

-   Semantic HTML5 markup
-   Reset CSS
-   CSS custom properties
-   Flexbox

### What I learned

- Applying rules to ``<body>`` that  prevent the display of scrollbars, since all elements had to fit in the viewport.
```
body {
    overflow: hidden;
    // ...
}
```
    
- Using SVG as a background image, resizing and stretching it to match the design.
```
body {
    background-image: url("./../images/bg-desktop.svg");
    background-size: 92vw 100vh;
    background-position: left top;
    background-color: var(--main-bg-color);
    background-repeat: no-repeat;
    -apple-background-size: 100% auto;
    background-attachment: fixed;
    // ...
}
```
    
### Continued development

- Get a better understanding of SVG.

## Author

-   Website - [Angélique D. Faye](https://adf.dev)
-   Frontend Mentor - [@angelique-df](https://www.frontendmentor.io/profile/angelique-df)
