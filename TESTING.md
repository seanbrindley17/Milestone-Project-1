# Testing

Return to the [README.md](README.md).

## Contents 

* Code Validation
    * HTML
    * CSS

* Browser Compatability

* Responsiveness

* Accessibility 

* Lighthouse Audit

* Defensive Programming

* User Story Testing

## Code Validation 

### HTML

I used the [W3C HTML Validator](https://validator.w3.org/nu/) to validate all of my HTML files in this project.

| Page | W3C URL | Screenshot | Notes |
| :---: | :---: | :---: | :---: |
| Home Page | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fseanbrindley17.github.io%2Fmilestone-project-1%2F) | ![screenshot of h1 validator error](/readme-documentations/screenshots/html%20h1%20validator%20error.jpg) | Warning for using more than one h1 element on a page. |
| Home Page | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fseanbrindley17.github.io%2Fmilestone-project-1%2F) | ![screenshot of W3C validation pass](/readme-documentations/screenshots/w3c%20html%20validator%20pass.jpg) | Fixed by changing a the 2nd h1 element on the home page into a h2 element. Result: Pass. No errors or warnings. |

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

I used the web accessibility evaluation tool [WAVE]() to test my project for accessibility issues.

| Page | Summary | Details | Contrast | Notes |
| :---: | :---: | :---: | :---: | :---: |
| Home | ![screenshot of home page summary](/readme-documentations/screenshots/accessibility%20screenshots/home%20page%20summary.jpg) | ![screenshot of home page details](/readme-documentations/screenshots/accessibility%20screenshots/home%20page%20details.jpg) | ![screenshot of home page contrast](/readme-documentations/screenshots/accessibility%20screenshots/home%20page%20contrast.jpg) | The link to my Github page in the footer did not have an aria-label which would have been confusing for screen readers and it was also opening in the same tab. The two pieces of text above my name are in a p element instead of h3. This has been fixed. Warning is for home link in the nav bar being close to the page title which is also a link. Everything else on the page is as intended. |
| About Me | ![screenshot of about me summary](/readme-documentations/screenshots/accessibility%20screenshots/about%20me%20summary.jpg) | ![screenshot of about me details](/readme-documentations/screenshots/accessibility%20screenshots/about%20me%20details.jpg) | ![screenshot of about me contrast](/readme-documentations/screenshots/accessibility%20screenshots/about%20me%20contrast.jpg) | Error is the footer link error as described and fixed above. Warning is for following a h1 with a h3 without a h2 intermediately between. This has been fixed. Everything else is as intended.