Front-end Test Project
======================

## Project brief
Convert the following parts of X-Plosion web site to HTML/CSS/JS. **Do not code the whole website, only the following 2 parts from the home page!**

- 3 blocks in the sidebar - http://screencast.com/t/VDe4tkzo7E8H
- News area - http://screencast.com/t/B31RvB5ZyFsQ

![X-Plosion](xplosion.jpg)

## Requirements
1. Create initial structure. Use gulp and node-sass. Use mobile-first approach.
2. Use HTML5 / SASS
3. Use bower as third parties lib manager
4. Create page called Home and place the elements on it
5. Use CSS3 PIE to add CSS3 support to IE8
6. Add Colorbox (http://www.jacklmoore.com/colorbox/) as a Bower dependency and open sample photos in the news section as an image group / gallery like follows:
  * When the page loads open the first photo in colorbox automatically (without user clicking on the image).
  * Go through all 4 images in 2 seconds interval but without using a built in slideshow functionality (Hint: Check *Event Hooks* example on the Colorbox homepage.)
  * Close Colorbox when the last image from the gallery is reached.
7. Do not use bootstrap/foundation
8. Your markup should look fine on mobile devices

## Download PSD
[xplosion.zip](xplosion.zip?raw=true) (2MB)

## Supported browsers
Ensure that the elements work and display correctly in the following browsers:

- Firefox (latest version)
- Google Chrome (latest version)
- Internet Explorer 11
- Internet Explorer 8

## Coding Standards
When working on the project follow our coding standards:

- [HTML Coding Standards](https://github.com/xhtmlized/html-coding-standards)
- [CSS Coding Standards](https://github.com/xhtmlized/css-coding-standards)
- [JavaScript Coding Standards](https://github.com/xhtmlized/js-coding-standards)

Ensure that your editor can load settings from .editorconfig file, otherwise use the same coding style as specified in it.

## Project Delivery
Create a public repo on your Github account and share the project URL with us once it’s done. Please, do not use XHTMLized or X-Plosion words in your repository name (use generic name like *test*).

## Quality Assurance

What you need to do to get high QA score? Simply get **Yes** for all these questions:

### General

- Are all requirements met?

### Precision

- Is reasonable pixel precision achieved?

### Browser check

- Does page display and work correctly in supported browsers?

### Valid HTML

- Is page valid?

### Semantic Markup

- Are the correct tags being used?

### Coding Standards

- Does page follow HTML coding standards?
- Does page follow CSS coding standards?

### Optimization

- Are image files sufficiently compressed?
- Are CSS sprites being used for images?

### Accessibility

- Are ALT attributes for images provided?
- Is proper heading structure in place?
