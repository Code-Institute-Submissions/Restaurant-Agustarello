# Testing
## Links
- I checked that each navbar link worked correctly, in both the mobile navbar and the expanded desktop navbar.
- I checked that the links of the social pages worked correctly both those in the navbar and those in the contacts section.
- I checked that the navbar logo works correctly by redirecting the user to the homepage.
- The button to view the restaurant menu opens a new tab where the pdf menu is displayed correctly.
- The back to the top button takes you back to the home smoothly.
- Tested Carousel right and left arrows and the right arrow moves to the next image and left arrow moves to the previous image as desired.

## Transition and Animation
- The background transition of the logo in the navbar works correctly.
- The underline-border transitions of the navbar links works correctly.
- The icon grow transitions in the navbar and contact section social links works correctly.
- The jumbotron animations work correctly, both fade-in(title) and sliding(subtitle).
- The background fade transition of the link to the restaurant menu view works correctly.
- The back-to-the-top button grow effect works properly.

## Responsive design
- Tested responsiveness of the wireframe using Dev Tools and confirmed basic structure looks and works well on all mobile decides from 320px, up to desktop size.
- After testing my work on responsive design control, I noticed that on 360px screens the main title was being cut off. 
<br></br>
![360px screen bug](Readme-img/resp-des-test-2.png)
<br></br>
<br></br>
I found that the expanded navigation bar on screens below 580px in height cropped social icons. I solved both problems with specific media queries.
<br></br>
![580px screen bug](Readme-img/resp-des-test-1.png)
<br></br>
<br></br>
I also noticed that in some types of notebook screens the footer content went outside the margin. I used media queries to create three different footer font sizes at 768px, 992px and 1440px.
<br></br>
![footer bug](Readme-img/resp-des-test-3.png)
- Once these changes were optimized I finally tested the project with [Google Mobile-Friendly test](https://search.google.com/test/mobile-friendly).The test gave excellent results

## Accessibility
I tested the color choice of the site with [a11y](https://color.a11y.com/),  a Color Contrast Accessibility Validator,  and the test result was very positive.
![color contrast validator](Readme-img/color-contrast-validator.png)

## HTML validator
After testing the site, the report reported 5 warnings and 1 error.
![html validator screenshot](Readme-img/html-validator.png)
I considered the warnings to be unimportant and fixed the reported error by adding name attribute to `<map>`