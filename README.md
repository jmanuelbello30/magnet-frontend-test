# Magnet.cl - Interface test

This technical test requires an HTML and CSS page to be implemented based on a reference design.

## Description

### Project structure

The project is a static web page with a single HTML file: `index.html`.

This page requires some additional resources:
* style.css: A file where the styles for the site should be implemented.
* site.js - A non-editable helper that emulates the dynamic content of the page.
* img: A folder with all the images required by the site.
* Open Sans: This font is downloaded from Google Fonts and is already required in the HTML and CSS.

No additional dependencies can be added.

### General objectives

The layout is responsive, with a 3-column layout on desktop and a single column for mobile.
There is a single breakpoint to switch from 1 to 3 columns when the viewport is `768px` or wider. Additional breakpoints are not required.

**You don't** need to support screens narrower than `480px`, **but** the solution has to work on any screen wider than that.

In the `index.html` file, you can find some *template tags* (variables between `{ }`). They are used to provide the content of your page.
**Do not delete.

The only available tags are: `{navlinks}`, `{title}`, `{content1}`, `{content2}` and `{content3}`.