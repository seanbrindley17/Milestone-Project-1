# Milestone-Project-1

## Contents 
* UX
    * Project Goal
    * User Stories
* Design
    * Wireframes
    * Colours
    * Fonts
    * Software Used

* Credits
    * Code Used From Other Sources

---

## UX

### Project Goal

The goal of this project is to create a static portfolio page that I can use as a base to begin to build up a proper portfolio of my work created during this diploma and beyond. I will be creating a **home** page, an **about me** page and a **contact** page to satisfy the 3 page requirement for this project.

### User Stories 

#### First Time Visitors

* I want interested people visiting for the first time to see a clear and concise site.

* I want potential employers to be able to easily locate the navigation buttons to take them to the relevant pages.

* I want anyone using the site with a mouse to be able to see when they're hovering over a nav button.

* I want visitors to see which programming languages I am associated with on my home page.

#### Returning Visitors 

* I want people who return to the site to find contact information be able to quickly find the information they are looking for.

---

## Design 

### Wireframes

Wireframes were created on balsamiq for mobile, tablet and desktop displays.

![homepage wireframe](/readme-documentations/wireframes/homepage%20v2.png)

![about me page wireframe](/readme-documentations/wireframes/about%20me%20v3.png)

![contact me page wireframe](/readme-documentations/wireframes/contact%20v2.png)

### Colours 

I decided to go for a silvery grey colour for the background and used gradient code from (link to credit here) to create it.

The buttons were then adapted from the gradient code found in the link above to create a gold colour gradient used in the buttons.

### Fonts

For my title and nav buttons I used "Vast Shadow" from google fonts.

For the smaller body text I used GFS Neohellenic, also from google fonts.

For the large central body text I used Arvo, from google fonts.

### Software Used

#### Coding Languages Used

HTML & CSS

#### Software and Programs Used

* VSCode - IDE used to create website and style.
    * Google Fonts - Location of fonts used.
    * Font Awesome - Location of icons used.
    * Bootstrap - Framework used to assist in building the site.

* W3 Schools - For extra help with remembering how to use bits of code correctly.

* balsamiq - Used to create wireframes.

## Bugs/Issues 

* I found that I had unexplained blank space below the footer and to the right that the background had got to but the space doesn't appear within the body element when checking it on Chrome dev tools. 

![space below footer that doesnt appear in the body tag](/readme-documentations/screenshots/space%20below%20footer%20bug%2025-03-24.jpg)

Fix: Found on stackoverflow [here](https://stackoverflow.com/questions/19148836/my-site-shows-white-space-on-right-in-mobile-chrome-but-not-desktop-chrome). Adding the below code to my style.css fixed the issue I was having. 
```css 
html, body {
    overflow-x: hidden;
}
```


* I had a lot of trouble with inexplicably being unable to style the nav buttons using bootstrap, until I realised while looking in dev tools and not seeing any bootstrap styling that I had put the wrong code from bootstrap in my head element.

## Credits 

### Code Used From Outside Sources

* To create the silver gradient main background and the background effect on the nav buttons while hovering, I used code from [this page](https://www.julienthibeaut.xyz/blog/creating-metallic-effect-with-css) by Julien Thibeaut. This code was adapted to create the static state of the gold nav buttons as well.

* To make the hover effect appear on the nav buttons, I used code from [hover.css (line 1247)](https://github.com/IanLunn/Hover/blob/master/css/hover.css) by Ian Lunn
