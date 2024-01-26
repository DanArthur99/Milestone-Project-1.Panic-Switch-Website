
# Panic Switch Band Website

![Panic Switch website shown on various websites](docs/readme-images/am-i-responsive-panic-switch-screenshot.jpg)

Deployed Website: [Panic Switch](https://danarthur99.github.io/Milestone-Project-1.Panic-Switch-Website/)

This project is a website for our band PANIC SWITCH, a thrash metal band based in Cheltenham, UK.

Consisting of five members, our style is a mixture of modern heavy metal along with more traditional thrash metal elements

## CONTENTS

* [Project Goal](#Project-Goal)

* [User Experience (UX)](#User-Experience-UX)
  * [User Stories](#User-Stories)

  * [Design](#Design)
    * [Colour Scheme](#Colour-Scheme)
    * [Typography](#Typography)
    * [Imagery](#Imagery)
    * [Wireframes](#Wireframes)
    * [Features](#Features)
    * [Accessibility](#Accessibility)

* [Technologies Used](#Technologies-Used)
  * [Languages Used](#Languages-Used)
  * [Frameworks & Other Libraries/Programs Used](#Frameworks--Other-LibrariesPrograms-Used)

* [Deployment & Local Development](#Deployment--Local-Development)
  * [Deployment](#Deployment)
  * [Local Development](#Local-Development)
    * [Forking a Repository](#Forking-a-Repository)
    * [Cloning a Repository](#Cloning-a-Repository)

* [Testing](#Testing)
  * [W3C Validator](#W3C-Validator)
  * [Lighthouse Testing](#Lighthouse-Testing)
  * [Wave Accessibiliy Testing](#Wave-Accessibility-TSesting)
  * [Bugs](#Bugs)
    * [Solved Bugs](#Solved-Bugs)
    * [Known Bugs](#Known-Bugs)
  * [Testing User Stories](#Testing-User-Stories)
  * [Other Testing](#Other-Testing)
  
* [Credits](#Credits)
  * [Code](#Code)

## Project Goal

Since our band does not currently have a live website, it was my idea to begin developing one.

The end goal was to have a fully functional (front-end) and aesthetically pleasing webpage that showcases our band, music, as well as good user interaction. This would including appropriate theming and imagery that matches the theme of the band, as well as links, both external and embedded, to our our music. 

I also thought it would be a good idea to add a sign up page that would sign users up to a (as of yet) fictional newsletter with their name, email and country. In turn, this would send them emails about upcoming gigs, new music, etc. (Please not that only the front end aspect of this section is functional. The sign up page at this point exists more as a proof of concept).

## User Experience (UX)

### User Stories

#### Overall Client Goals

* To have a website that is viewable on different screen sizes
* To have a website theme that is aesthetically eye catching and matches the theme of the band
* To have a website that is clearly and easily navigatable

#### First Time Visit Goals

* To have access to the bands current and latest music
* To have access to the upcoming gig schedule
* To be able to access the bands social media accounts

#### Returning Visitor Goals

* To be able to view the latest updates regarding the band
* To be able to view and book tickets to the bands upcoming shows
* To be able to sign up to an email list keeps me up to with the latest releases, gigs, or merchandise.

### Design

#### Wireframes

The wireframes for this site were created using [Figma](https://www.figma.com/)

##### Home Page Wireframes

###### Desktop

![Home Page Wireframe Desktop](docs/wireframes/home-screen-wireframe-desktop.png)

###### Mobile

![Home Page Wireframe Mobile](docs/wireframes/home-screen-wireframe-mobile.png)

##### Shows Page Wireframes

###### Desktop

![Shows Page Wireframe Desktop](docs/wireframes/shows-page-wireframe-desktop.png)

###### Mobile

![Shows Page Wireframe Mobile](docs/wireframes/shows-page-wireframe-mobile.png)

##### Sign Up Page Wireframes

###### Desktop

![Sign Up Page Wireframe Desktop](docs/wireframes/sign-up-wireframe-desktop.png)

###### Mobile

![Sign Up Wireframe Mobile](docs/wireframes/sign-up-wireframe-mobile.png)


#### Typography

The Website primarily uses 2 different fonts throughout. Both of which were obtained from Google Fonts. These fonts were:

* Rubik Glitch ('fantasy')
* Exo 2 ('sans-serif')

"Rubik Glitch" is a much more decorative font, so this was typically used for large headings, navigation links, and other large text.

"Exo 2" is a simpler font and is a bit easier to read, so this was generally used for larger paragraphs of text, such as the text on the 'About' page, and descriptive labels.

#### Colour Palette

Keeping in line with the theme of the band, the site uses a largely "colourless" palette , consisting predominantly of blacks, greys, and whites. There are a few exceptions however, such as the navbar elements and the footer elements, which use shades of blue and green, albiet slightly washed shades.

![Colour Palette 1](docs/readme-images/color-palette.png)
![Colour Palette 2](docs/readme-images/color-palette-2.png)

### Technologies Used

#### Languages

The programming languages used for this project were:

* HTML5
* CSS3
* JavaScript (used but not written by myself (see Credits section))

#### Frameworks & Other Libraries/Programs Used

* Git - Version Control
* Github - To save and store changes to the project
* [Bootstrap (v5.3.2)](https://getbootstrap.com/) - CSS and JS framework used. Used mainly for the navbar, grid structure, and button styling.
* [Google Fonts](https://fonts.google.com/)- Imported selected fonts into external stylesheet, namely "Rubik Glitch" and "Exo 2."
* [Figma](https://www.figma.com/) - Used to create the wireframes.
* [Coolors] (https://coolors.co/) - Used to create the colour palette image.
* [Favicon.io](https://favicon.io/) - To create favicon icons.
* [Am I Responsive?](https://ui.dev/amiresponsive) - Used to create the multi-screen image you see at the start of this document.
* [CloudConvert](https://cloudconvert.com/webp-converter) - To convert JPEG images into WEBP format.
* [Compress-Or-Die](https://compress-or-die.com/webp) - Image File Compressor.
* Chrome Developer Tools - Used for testing features and responsiveness.
  * Lighthouse - Extension of dev tools used. Gives a score on site performance, accessibiliity, search engine optimization, and best practices in code.
* [W3C Markup Validation Service](https://validator.w3.org/) - Used for testing HTML validation.
* [w3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) - Used for testing CSS validation.
* [Wave Web Accessibility Evaluation Tool](https://wave.webaim.org/extension/) - Used for testing webpage accessibility. 

### Features



### Accessibility

* All applicable features and element have the necessary aria-labels and alt attributes, these include the img element on the index page, the social media icons, band logo, and other textless buttons such as the spotify and amazon buttons. This is so that it is easily accessibile for people using screen readers.

* Semantic HTML has been used, i.e. the use of header, section, and footer, as well as nav elements, and correctly ordered and nested heading tags

* The color contrast is sufficient across the whole site, and text is easy to read and interpret.

## Deployment & Local Development

### Deployment

Github Pages was used to deploy the live website. The instructions to achieve this are below:

  1. Log in or Sign Up to Github.
  2. Find the repository for this project, DanArthur99 / Milestone-Project-1.Panic-Switch-Website.
  3. Click on the Settings link.
  4. Click on the Pages link in the left hand side navigation bar.
  5. In the Source section, choose main from the drop down select branch menu. Select Root from the drop down select   folder menu.
  6. Click Save. Your live Github Pages site is now deployed at the URL shown.

### Local Development

#### Forking a Repository

To fork the Panic Switch Website repository:

  1. Log in or Sign Up to Github.
  2. Go to the repository for this project, DanArthur99 / Milestone-Project-1.Panic-Switch-Website.
  3. Click the Fork button in the top right corner.

#### Cloning a Repository

To clone the Panic Switch Website repository:

  1. Log in or Sign Up to GitHub.
  2. Go to the repository for this project, DanArthur99 / Milestone-Project-1.Panic-Switch-Website.
  3. Click on the code button, select whether you would like to clone with HTTPS, SSH or GitHub CLI and copy the link shown.
  4. Open the terminal in your IDE and set your working directory to the location you want to use for the cloned repository.
  5. Type 'git clone' into the terminal window, and paste the link from step 3, then press enter.
  6. Your cloned repository should now be located in your chosen directory, ready for local development.


## Testing

### W3C Validator

#### Home Page

![Home Page W3C Validator](docs/testing/index-page-w3c-validation.png)

#### About Page

![About Page W3C Validator](docs/testing/about-page-w3c-validation.png)

#### Shows Page

![Shows Page W3C Validator](docs/testing/shows-page-w3c-validation.png)

#### Sign Up Page

![Sign Up Page W3C Validator](docs/testing/sign-up-w3c-validation.png)

#### Thank You Page

![Thank You Page W3C Validator](docs/testing/thank-you-w3c-validation.png)

#### 404 Page

![404 Page W3C Validator](docs/testing/404-page-w3c-validation.png)

#### Stylesheet

![Stylesheet W3C Validator](docs/testing/stylesheet-w3c-validation.png)

### Lighthouse Testing

#### Home Page

![Home Page Lighthouse Test](docs/testing/index-page-lighthouse-test.png)

* The main issue I am getting from the lighthouse test is performance issues, which is in part due to the embedded youtube video (iframe) that has to load in, as well the numerous animations on the page. When I originally tested the page on the lighthouse test, I was getting scores in the 30s. To fix this issue, I used code from a repository called Lite-YouTube-Embed, written by paulirish ([see Credits section](#Credits)), which allows the page to 'lazy-load' the embedded youtube video, and only loads in the iframe when the 'facade' is clicked.
* Other issues I was getting were due to image file sizes. In the end, I ended up converting all jpg images into webp format, then further compressing them so that the file sizes were not too big.

#### About Page

![About Page Lighthouse Test](docs/testing/about-page-lighthouse-test.png)

#### Shows Page

![Shows Page Lighthouse Test](docs/testing/shows-page-lighthouse-test.png)

* The performance for the shows page is scoring slightly lower. The largest contentful paint element is in part to blame, which takes longer to load in due to the fade-in animation.

![Shows Page Largest Contentful Paint](docs/testing/shows-largest-content-paint.png)

#### Sign Up Page

![Sign Up Page Lighthouse Test](docs/testing/sign-up-lighthouse-test.png)

* The performance is showing slightly below the rest of the criteria due to the largest contentful paint element, which is the band photo background at the top of the screen that uses a fade-in animation keyframe.

![Sign Up Page Largest Contentful Paint](docs/testing/sign-up-lcp.png)

#### Thank You Page

![Thank You Page Lighthouse Test](docs/testing/thank-you-lighthouse-test.png)

* The only reason the best accessibility section is scoring lower is because of the meta refresh redirect tag. This is intentional, as I wanted the user to be redirected to the homepage once 'signing up.'

![Thank You Page Lighthouse Accessibility Score](docs/testing/thank-you-lighthouse-accessibility.png)

#### 404 Page

![404 Page Lighthouse Test](docs/testing/404-page-lighthouse-test.png)

### Wave Accessibility Testing

#### Home Page

![Home Page Wave Test](docs/testing/index-page-wave-accessibility.png)

  * While no errors occurred, there is an alert for a redundant link. This however is intentional, as it is my design choice to have the band logo double as a link back to the home page no matter what page the user is on (the only exceptions to this are the thank you page and the 404 page).

![Redundant Link](docs/testing/redundant-link-image.png)

#### About Page

![About Page Wave Test](docs/testing/about-page-wave-accessibility.png)

  * Once again there are alerts for redundant links. However, this is part of my design choice.

![Redundant Links](docs/testing/two-redundant-links-image.png)

#### Shows Page

![Shows Page Wave Test](docs/testing/shows-page-wave-accessibility.png)

  * As before, the redundant links alerts also appear.

![Redundant Links](docs/testing/two-redundant-links-image.png)

#### Sign Up Page

![Sign Up Page Wave Test](docs/testing/sign-up-wave-accessibility.png)

  * Same redundant links alerts as previous.

![Redundant Links](docs/testing/two-redundant-links-image.png)

#### Thank You Page

![Thank You Page Wave Test](docs/testing/thank-you-wave-accessibility.png)
  * As with the lighthouse testing, the only reason an error is occuring is because of the meta refresh redirect tag, which is an intentional design choice of mine, as I wanted the user to be redirected to the home page.

![Refresh Wave Error](docs/testing/refresh-wave-error.png)

#### 404 Page

![404 Page Wave Test](docs/testing/404-page-wave-accessibility.png)

### Bugs

#### Solved Bugs

* One bug I came across was that the navbar would wrap strangely when the screen was shrunk down below a certain size, but before it switched to the drop down menu. One of the big things that would happen is the logo would wrap above the screen so that it was invisible.

  To get around this, I programmed the dropdown nav menu to appear at my own custom breakpoint, rather than the bootstrap provided once. This breakpoint was slightly larger than the tradition sm breakpoint, being 631px. This meant that the nav menu would turn into a dropdown menu before any screen wrap issue could occur

  These custom breakpoints were also used for other elements, and were implemented using the "d-custom-none" and "d-custom-maxwidth-none" class names.

![d-custom-none](docs/readme-images/d-custom-none.png)

![d-custom-maxwidth-none](docs/readme-images/d-custom-maxwidth-none.png)

![navbar d-custom-none](docs/readme-images/nav-d-custom-none.png)

* Another bug I encountered was that the text for the nav elements would go outside the lines of their containers when the screen shrunk to a certain size. 

  To fix this, I created a couple of extra media queries that would cause the font-size of the text to reduce at these specific breakpoints.

![Navbar Text Breakpoints](docs/readme-images/nav-text-breakpoints.png)

* One bug I encountered when the site was deployed was that a 405 method not allowed error would occur when attempting to submit the form, rather than taking me to the intended thank-you.html. To counteract this, I removed the method="post" attribute from the form element, and kept the action attribute value as thank-you.html, which then allowed me to submit the form and take the user to the thank you page without any issues.

#### Known Bugs

### Testing User Stories

### Other Testing

## Credits

### Code

* [Lite YouTube Embed repository](https://github.com/paulirish/lite-youtube-embed?tab=readme-ov-file) - author: paulirish
  * (This repository was used to reduce the performance issues I had when loading in the iframe on the home. The lite-youtube-embed.css and lite-youtube-embed.js files have been copied into my github repository) 
* [Image responsivity fix](https://stackoverflow.com/questions/25766783/how-to-make-my-image-responsive-width-and-height) - author: JasonK
  * (This code (accepted answer) was used to fix the responsivity issue on the cover art image load in)
* [Country list](https://gist.github.com/danrovito/977bcb97c9c2dfd3398a) - author: danrovito
  * (This code was copied into the sign-up form, and was used to display the country dropdown list)



