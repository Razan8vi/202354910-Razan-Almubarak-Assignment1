# Technical Documentation

## 1. Overview

This document explains the technical structure and main design decisions used to build my personal portfolio website for SWE 363 Assignment 1.
The website was created using plain HTML, CSS, and JavaScript.
## 2. HTML Structure

The website uses  HTML elements such as `header`, `nav`, `main`, `section`, and `footer` to keep the page organized and easy to understand.

The website has three required sections:

* **About Me:** Includes a short introduction and tagline.
* **Projects:** Includes two project cards with titles, descriptions, and placeholder images.
* **Contact:** Includes a form with Name, Email, and Message fields.

Each section has a unique `id`, such as `about`, `projects`, and `contact`. The navigation links use these IDs to move to the correct section on the page.
The contact form uses `label`, `input`, `textarea`, and `button` elements. 

## 3. CSS and Responsive Design

All styling is placed in the external stylesheet `css/styles.css`. This keeps the HTML structure separate from the visual design.

The website uses CSS properties such as colors, margins, padding, borders, fonts, and the box model to create spacing and organize the content.

* The navigation links use Flexbox and can wrap on smaller screens.
* The project cards use Flexbox and wrap from two cards into one column when the screen becomes narrow.
* The contact form uses `flex-direction: column` to place the fields vertically.
The layout uses percentage widths, `max-width`, `min-width`, and Flexbox wrapping to support desktop, tablet, and mobile screens.

## 4. Visual Design

The website uses a dark plum background with pink accents for buttons, borders, and interactive elements. The colors were selected to create a clean and professional appearance.
## 5. JavaScript Features

The website includes two JavaScript interactions:

1. A time-of-day greeting that displays a different message in the header depending on the visitor's local time.
2. A confirmation message that appears when the contact form is submitted. The form fields are then reset without sending data to a server.

The JavaScript uses variables (`let` and `const`), conditional statements (`if`, `else if`, and `else`),
 and functions. These concepts were used to apply the JavaScript material covered in class.

## 6. Testing and Limitations

The website should be tested by opening `index.html` in a browser, resizing the browser window, checking the navigation links, and submitting the contact form.

The contact form is a front-end feature only. It displays a confirmation message but does not send data anywhere because no backend is included.