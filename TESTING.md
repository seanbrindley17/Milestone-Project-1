# Testing

Return to the [README.md](README.md).


## Code Validation 

### HTML

I used the [W3C HTML Validator](https://validator.w3.org/nu/) to validate all of my HTML files in this project.

| Page | W3C URL | Screenshot | Notes |
| :---: | :---: | :---: | :---: |
| Home Page | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fseanbrindley17.github.io%2Fmilestone-project-1%2F) | ![screenshot of h1 validator error](/readme-documentations/screenshots/html%20h1%20validator%20error.jpg) | Warning for using more than one h1 element on a page. |
| Home Page | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fseanbrindley17.github.io%2Fmilestone-project-1%2F) | ![screenshot of W3C validation pass](/readme-documentations/screenshots/w3c%20html%20validator%20pass.jpg) | Fixed by changing a the 2nd h1 element on the home page into a h2 element. Result: Pass. No errors or warnings. |
| About Me | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fseanbrindley17.github.io%2Fmilestone-project-1%2Faboutme.html) | ![screenshot of about me errors](/readme-documentations/screenshots/html%20validator%20screenshots/about%20me%20page%20validator%20errors.png) | Errors for incorrect usage of ul elements and having 2 closing body tags | 
| About Me | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fseanbrindley17.github.io%2Fmilestone-project-1%2Faboutme.html#textarea) | ![screenshot of no warnings on about me page](/readme-documentations/screenshots/html%20validator%20screenshots/about%20me%20page%20pass.jpg) | Fixed by replacing invalid ul tags with p elements and removing the errant closing body tag. |
| Projects | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fseanbrindley17.github.io%2Fmilestone-project-1%2Fprojects.html) | ![screenshot of no errors on projects page](/readme-documentations/screenshots/html%20validator%20screenshots/projects%20page%20html%20pass.jpg) | No errors or warnings. |
| Contact | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fseanbrindley17.github.io%2Fmilestone-project-1%2Fcontact.html) | ![screenshot of no errors on contact page](/readme-documentations/screenshots/html%20validator%20screenshots/contact%20page%20html%20pass.jpg) | No errors or warnings. |
| Submit Form Confirmation | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fseanbrindley17.github.io%2Fmilestone-project-1%2Fcontact.html#textarea) | ![screenshot of error in submit form page](/readme-documentations/screenshots/html%20validator%20screenshots/submit%20form%20error.jpg) | Warning for using more than one h1 element on a page. |
| Submit Form Confirmation | ![W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fseanbrindley17.github.io%2Fmilestone-project-1%2Fcontact.html#textarea) | ![screenshot of no errors on submit form confirmation page](/readme-documentations/screenshots/html%20validator%20screenshots/submit%20form%20html%20pass.jpg) | Fixed by changing the 2nd h1 element into a h2 element. |


### CSS 

I used the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) to validate my CSS style sheet for this project.

| File | W3C URL | Screenshot | Notes |
| :---: | :---: | :---: | :---: |
| style.css | [W3C](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fseanbrindley17.github.io%2Fmilestone-project-1%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en) | ![screenshot of css validation error](/readme-documentations/screenshots/w3c%20css%20validator%20error.jpg) | Syntax error in some css animation code. |
| style.css | [W3C](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fseanbrindley17.github.io%2Fmilestone-project-1%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en) | ![screenshot of css validator pass](/readme-documentations/screenshots/w3c%20css%20validator%20pass.jpg) | No errors found. Pass. |


## Browser Compatibility

I tested the site on these browsers to check for any combatibility issues.

| Browser | Home | About Me | Projects | Contact | Notes |
| :---: | :---: | :---: | :---: | :---: | :---: |
| Chrome | ![screenshot of homepage on chrome](/readme-documentations/screenshots/browser%20responsiveness%20screenshots/chrome/chrome%20home%20page.jpg) | ![screenshot of about me page on chrome](/readme-documentations/screenshots/browser%20responsiveness%20screenshots/chrome/chrome%20about%20me%20page.jpg) | ![screenshot of projects page on chrome](/readme-documentations/screenshots/browser%20responsiveness%20screenshots/chrome/chrome%20projects%20page.jpg) | ![screenshot of contact page on chrome](/readme-documentations/screenshots/browser%20responsiveness%20screenshots/chrome/chrome%20contact%20page.jpg) | All work as intended. |
| Edge | ![screenshot of home page on Edge](/readme-documentations/screenshots/browser%20responsiveness%20screenshots/edge/edge%20home%20page.jpg) | ![screenshot of about me page on edge](/readme-documentations/screenshots/browser%20responsiveness%20screenshots/edge/edge%20about%20me%20page.jpg) | ![screenshot of projects page on edge](/readme-documentations/screenshots/browser%20responsiveness%20screenshots/edge/edge%20projects%20page.jpg) | ![screenshot of contact page on edge](/readme-documentations/screenshots/browser%20responsiveness%20screenshots/edge/edge%20contact%20page.jpg) | All work as intended. |


## Accessibility 

I used the web accessibility evaluation tool [WAVE](https://wave.webaim.org/) to test my project for accessibility issues.

| Page | Summary | Details | Contrast | Notes |
| :---: | :---: | :---: | :---: | :---: |
| Home | ![screenshot of home page summary](/readme-documentations/screenshots/accessibility%20screenshots/home%20page%20summary.jpg) | ![screenshot of home page details](/readme-documentations/screenshots/accessibility%20screenshots/home%20page%20details.jpg) | ![screenshot of home page contrast](/readme-documentations/screenshots/accessibility%20screenshots/home%20page%20contrast.jpg) | The link to my Github page in the footer did not have an aria-label which would have been confusing for screen readers and it was also opening in the same tab. The two pieces of text above my name are in a p element instead of h3. This has been fixed. Redundant link warning is for home link in the nav bar being close to the page title which is also a link.  Everything else on the page is as intended. |
| About Me | ![screenshot of about me summary](/readme-documentations/screenshots/accessibility%20screenshots/about%20me%20summary.jpg) | ![screenshot of about me details](/readme-documentations/screenshots/accessibility%20screenshots/about%20me%20details.jpg) | ![screenshot of about me contrast](/readme-documentations/screenshots/accessibility%20screenshots/about%20me%20contrast.jpg) | Error is the footer link error as described and fixed above. Warning is for following a h1 with a h3 without a h2 intermediately between. This has been fixed. Redundant link warning is for home link in the nav bar being close to the page title which is also a link. Everything else is as intended. | 
| Projects | ![screenshot of projects summary](/readme-documentations/screenshots/accessibility%20screenshots/projects%20summary.jpg) | ![screenshot of projects details](/readme-documentations/screenshots/accessibility%20screenshots/project%20details.jpg) | ![screenshot of projects contrast](/readme-documentations/screenshots/accessibility%20screenshots/projects%20contrast.jpg) | Error is the footer link error as described and fixed in the Home section. Suspicious alt text warning was because my alt text was too generic, this has been fixed. Redundant link warning is for home link in the nav bar being close to the page title which is also a link. Everything else is as intended. |
| Contact | ![screenshot of contact summary](/readme-documentations/screenshots/accessibility%20screenshots/contact%20summary.jpg) | ![screenshot of contact details](/readme-documentations/screenshots/accessibility%20screenshots/contact%20details.jpg) | ![screenshot of contact contrast](/readme-documentations/screenshots/accessibility%20screenshots/contact%20contrast.jpg) | Error is footer link error as described and fixed in the Home section. Empty form label error is because the submit button had a label which was not necessary and had no content, this has been removed. Fixed heading level warning by changing h3 element to h2. Redundant link warning is for home link in the nav bar being close to the page title which is also a link.  Everything else is as intended. |


## Lighthouse Audit 

| Page | Desktop | Mobile | Notes |
| :---: | :---: | :---: | :---: |
| Main | ![screenshot of lighthouse audit for desktop](/readme-documentations/screenshots/lighthouse%20screenshots/desktop%20lighthouse%20audit.jpg) | ![screenshot of lighthouse audit for mobile](/readme-documentations/screenshots/lighthouse%20screenshots/mobile%20lighthouse%20audit.jpg) | Good performance on desktop. Seems to argue with my Kaspersky firewall however which is reducing the score in best practices and mobile performance when tested. |


## User Story Testing 

| User Story | Screenshot |
| :---: | :---: |
| As a new site user, I would like to know what the site is about so I can understand what the purpose of the site is for. | ![screenshot of home page](/readme-documentations/screenshots/user%20story%20screenshots/what%20the%20site%20is%20about.jpg) |
| As a new site user, I would like to be able to locate the navigation elements to take me to the relevant page quickly and easily. | ![screenshot of navbar](/readme-documentations/screenshots/user%20story%20screenshots/navigation.jpg) |
| As a new site user, I would like to see a clear and concise website. | ![screenshot of full font page](/readme-documentations/screenshots/user%20story%20screenshots/full%20front%20page.jpg) |
| As a returning site visitor, I would like to be able to immediately navigate to the page which is most relevant for me. | ![screenshot of navbar](/readme-documentations/screenshots/user%20story%20screenshots/navigation.jpg) |
| As a returning site visitor, I would like to see the programming languages associated with the creator if I feel like I could work with the creator. | ![screenshot of programming language icons](/readme-documentations/screenshots/user%20story%20screenshots/programming%20language%20icons.jpg) |


## Defensive Programming 

| Page | Expectation | Test | Result | Fix | Screenshot |
| :---: | :---: | :---: | :---: | :---: | :---: |
| Main | The Contact page is expected to open when the user clicks on the Give Me A Shout button | Tested the feature by clicking the Give Me A Shout Button | The feature behaved as expected | Test passed | ![screenshot of contact page](/readme-documentations/screenshots/defensive%20testing%20screenshots/contact%20page.jpg) |
| Contact | If a user attempts to submit a query from the contact page without inputting a name, valid email address or query, they will not be able to | Tested by clicking the submit button while having each of the fields empty, one at a time | The feature behaved as expected | Test Passed | ![screenshot of contact page with error message](/readme-documentations/screenshots/defensive%20testing%20screenshots/submit%20form%20required%20fields.jpg) |
| All pages | The Github icon in the footer is expected to open my Github profile in a new tab | Tested by clicking the Github icon on all pages | The feature behaved as expected | Test Passed | ![screenshot of my Github profile page](/readme-documentations/screenshots/defensive%20testing%20screenshots/github%20profile.jpg) |
| All pages | The page title at the top is expected to function as a home button | Tested by clicking the title on all pages | The feature behaved as expected | Test Passed | ![screenshot of page title](/readme-documentations/screenshots/defensive%20testing%20screenshots/page%20title.jpg) |


## Bugs/Issues 

### Main Display Bug

* I found that I had unexplained blank space below the footer and to the right that the background had got to but the space doesn't appear within the body element when checking it on Chrome dev tools. 

![space below footer that doesnt appear in the body tag](/readme-documentations/screenshots/space%20below%20footer%20bug%2025-03-24.jpg)

Fix: Found on stackoverflow [here](https://stackoverflow.com/questions/19148836/my-site-shows-white-space-on-right-in-mobile-chrome-but-not-desktop-chrome). Adding the below code to my style.css fixed the issue I was having initially. 
```css 
html, body {
    overflow-x: hidden;
}
```

* However, following on from this previous issue, I found that certain display ratios of width to height would give me the duplicated background display at the bottom shown below. 

    ![comparison of the issues that differing heights has on the background](/readme-documentations/screenshots/differing%20heights%20background%20issue.jpg)

* I was unable to solve this issue so I compensated by using a background image from [Pixabay](https://pixabay.com/illustrations/circular-slabs-metal-iron-837510/) as a replacement for my gradient colours. This was styled to make it sit central using code from [CSS Tricks](https://css-tricks.com/perfect-full-page-background-image/).

### Footer

* I had a lot of trouble getting the footer to stay at the bottom of the screen, especially on pages with less content. Eventually I came across a solution from [30 Seconds Of Code](https://www.30secondsofcode.org/css/s/footer-at-the-bottom/) which showed how using flexbox can get a footer to stay sat at the bottom.

### Bootstrap

* I initially had a lot of trouble with inexplicably being unable to style the nav buttons using bootstrap, until I realised while looking in dev tools and not seeing any bootstrap styling that I had put the wrong code from bootstrap in my head element.