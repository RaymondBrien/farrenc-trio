# Testing

Return back to the [README.md](README.md) file.

Throughout the development of this site, rigorous testing has been a bedrock for ensuring a seamless user experience. Throughout its development every facet of the site has been maticulously scrutinised, from functionality to responsiveness. This thorough examination not only ensures the robustness of the website across multiple devices (with a mobile-first approach being given first priority) but also instills confidence to our users that it functions seamlessly across browsers for all our potential users. With a dedicated approach to quality assurance, I am confident that the website is a testament to a thorough and effective testing regimen, ensuring users encounter a smooth and reliable online environment.

### Throughout the testing process all the following goals were assigned:
Layout, each page's content's order of appearance, navigation elements and page structure in accordance with the site's primary goals (enabling the trio to be contacted, providing relevant information for music promoters and establishing an online presence); 
Navigation (for clarity, visibility within the structure, intuitive design and a smooth user experience); 
Visibility of all elements on the page, particularly paying attention to avoid overstimulation for the user; 
Suitable color choices and contrast for clear visual recognition and accessibility requirements; 
Ensuring responsivity of all elements is functional with clarity being the primary goal across multiple devices and screen sizes.

#### Below is a list of the features this site holds:
(More detailed feature descriptions listed in the features section of the [README.md](README.me)).

Navbar (responsive and changing layout depending on screen size for optimum visibility and clear navigation across devices);

Numerous unobtrusive fontawesome icons with clear relationships between the icon and its attributed meaning for intuitive user experience and ease of navigation;

Multiple call-to-action internal links on each page to direct the user directly to the contact.html page;

A fixed header element for ease of navigation, no matter where you are on any page, so that the navbar is always available;

News sections and contact tips separated out with the use of borders (for tips) and fieldsets (for news) to differentiate content from the page's main focus and provide further clarity within each page;

Footers which provide further opportunities to direct the user to the contact page, along with direct links which open in a new tab to the trio's social media platforms;

A functional contact page which is only submittable with the correctly formatted required fields, taking the user to a confirmation page which, after 10 seconds, after acknowledging the user's submitted form for good user experience, automatically redirects the user back to the home page after 10 seconds, informing the user as it does so to establish user trust and ease of mind;

Responsive photos on each page of the site which do not obstruct each page's content and provide a sense of ease to the user, with a consistent appearance across the site;

Structured content on each page adhering in general to the rule of thirds where appropriate for suitable visual clarity and user experience;

An interactive gallery slideshow to avoid page clutter (instead of simply listing all the photos at once) which allows the user to initiate engagement themselves with the site for a positive user expeirence;

A responsive table which allows for the target audience of festival promoters and music-specific users to find repertoire in clearly definied categories, each with an attributed icon for clear content navigation;

Colors, font family, font sizes, and icons were consistent across all pages for intuitive design;

With all the aforementioned elements of testing and functionality in mind during the testing phase, we are confident that the project provides a straightforward way for users to achieve their primary goals in accordance with the target audience's reviewed goals and the site's primary goals;

External links to social media pages of the trio which open in a new tab;
Testamonial;

News section;

Contact page;

Repertoire tables categorised as either classical or contemporary repertoire, with durations and instrumentation;

Contact form with required fields and field format requirements;

Confirmation of receipt of contact form submission;

Hero image;

Favicon png's (also used as the logo);



## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

| Page | W3C URL | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fraymondbrien.github.io%2Ffarrenc-trio%2Findex.html) | ![screenshot](documentation/html-validation-home.png) | Section lacks header h2-h6 warning. Fixed. |
| Contact | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fraymondbrien.github.io%2Ffarrenc-trio%2Fcontact.html) | ![screenshot](documentation/html-validation-contact.png) | obsolete iframe warnings. Fixed. |
| Services | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fraymondbrien.github.io%2Ffarrenc-trio%2Fservices.html) | ![screenshot](documentation/html-validation-quizservices.png) | Pass: No Errors |
| Gallery | [W3C] (https://validator.w3.org/nu/?doc=https%3A%2F%2Fraymondbrien.github.io%2Ffarrenc-trio%2Fgallery.html) | ![screenshot](documentation/html-validation-gallery.png) | Duplicate IDs found, and fixed. |
| Confirmation | [W3C] (https://validator.w3.org/nu/?doc=https%3A%2F%2Fraymondbrien.github.io%2Ffarrenc-trio%2Fconfirmation.html) | ![screenshot](documentation/html-validation-confirmation.png) | Pass: No Errors |


### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

| File | Jigsaw URL | Screenshot | Notes |
| --- | --- | --- | --- |
| style.css | [Jigsaw](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fraymondbrien.github.io%2Ffarrenc-trio%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en) | ![screenshot](documentation/css-validation-style.png) | Pass: No Errors |


## Browser Compatibility


Use this space to discuss testing the live/deployed site on various browsers.

Consider testing at least 3 different browsers, if available on your system.

Recommended browsers to consider:
- [Chrome](https://www.google.com/chrome)
- [Firefox (Developer Edition)](https://www.mozilla.org/firefox/developer)
- [Opera](https://www.opera.com/download)

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Home | Contact | Confirmation | Services | Gallery | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Chrome | ![screenshot](documentation/browser-chrome-home.png) | ![screenshot](documentation/browser-chrome-homecontact.png) | ![screenshot](documentation/browser-chrome-confirmation.png) | ![screenshot](documentation/browser-chrome-services.png) | ![screenshot](documentation/browser-chrome-gallery.png) | Works as expected |
| Firefox | ![screenshot](documentation/browser-firefox-home.png) | ![screenshot](documentation/browser-firefox-contact.png) | ![screenshot](documentation/browser-firefox-confirmation.png) | ![screenshot](documentation/browser-firefox-services.png) | Works as expected | | ![screenshot](documentation/browser-firefox-gallery.png) | Works as expected |
| Opera | ![screenshot](documentation/browser-opera-home.png) | ![screenshot](documentation/browser-opera-contact.png) | ![screenshot](documentation/browser-opera-confirmation.png) | ![screenshot](documentation/browser-opera-services.png) | | ![screenshot](documentation/browser-opera-gallery.png) | Minor differences |


## Responsiveness

The minimum requirement is for the following 3 tests:
- Mobile
- Tablet
- Desktop

I've tested my deployed project on multiple devices to check for responsiveness issues.

| Device | Home | Contact | Confirmation | Services | Gallery | Notes |
| --- | --- | --- | --- | --- | --- |
| Mobile (DevTools) | ![screenshot](documentation/responsive-mobile-home.png) | ![screenshot](documentation/responsive-mobile-contact.png) | ![screenshot](documentation/responsive-mobile-confirmation.png) | ![screenshot](documentation/responsive-mobile-services.png) | ![screenshot](documentation/responsive-mobile-gallery.png) | Works as expected |
| Tablet (DevTools) | ![screenshot](documentation/responsive-tablet-home.png) | ![screenshot](documentation/responsive-tablet-contact.png) | ![screenshot](documentation/responsive-tablet-confirmation.png) | ![screenshot](documentation/responsive-tablet-services.png) | ![screenshot](documentation/responsive-tablet-gallery.png) | Works as expected |
| Laptop | ![screenshot](documentation/responsive-laptop-home.png) | ![screenshot](documentation/responsive-laptop-contact.png) | ![screenshot](documentation/responsive-laptop-confirmation.png) | ![screenshot](documentation/responsive-laptop-services.png) | ![screenshot](documentation/responsive-laptop-gallery.png) | Works as expected |
| XL Monitor | ![screenshot](documentation/responsive-desktop-home.png) | ![screenshot](documentation/responsive-desktop-contact.png) | ![screenshot](documentation/responsive-desktop-confirmation.png) | ![screenshot](documentation/responsive-desktop-services.png |![screenshot](documentation/responsive-desktop-gallery.png) | Scaling starts to have minor issues |
| iPhone 10 | ![screenshot](documentation/responsive-iphone-home.png) | ![screenshot](documentation/responsive-iphone-contact.png) | ![screenshot](documentation/responsive-iphone-confirmation.png) | ![screenshot](documentation/responsive-iphone-services.png) | ![screenshot](documentation/responsive-iphone-gallery.png) | Works as expected |
| iPad Pro 12.9 inch | ![screenshot](documentation/responsive-ipad-home.png) | ![screenshot](documentation/responsive-ipad-contact.png) | ![screenshot](documentation/responsive-ipad-confirmation.png) | ![screenshot](documentation/responsive-ipad-services.png) | ![screenshot](documentation/responsive-ipad-gallery.png) | Works as expected |


## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page | Mobile | Desktop | Notes |
| --- | --- | --- | --- |
| Home | ![screenshot](documentation/lighthouse-home-mobile.png) | ![screenshot](documentation/lighthouse-home-desktop.png) | Some minor warnings |
| Contact | ![screenshot](documentation/lighthouse-contact-mobile.png) | ![screenshot](documentation/lighthouse-contact-desktop.png) | Some minor warnings |
| Confirmation | ![screenshot](documentation/lighthouse-confirmation-mobile.png) | ![screenshot](documentation/lighthouse-confirmation-desktop.png) | Some minor warnings |
| Services | ![screenshot](documentation/lighthouse-services-mobile.png) | ![screenshot](documentation/lighthouse-services-desktop.png) | Some minor warnings |
| Gallery | ![screenshot](documentation/lighthouse-gallery-mobile.png) | ![screenshot](documentation/lighthouse-gallery-desktop.png) | Slow response time due to large images |

## User Story Testing
⚠️

<!-- Testing user stories is actually quite simple, once you've already got the stories defined on your README.

Most of your project's **features** should already align with the **user stories**,
so this should as simple as creating a table with the user story, matching with the re-used screenshot
from the respective feature.
 -->

| User Story | Screenshot |
| --- | --- |
| As a new site user, I would like to ____________, so that I can ____________. | ![screenshot](documentation/feature01.png) |
| As a new site user, I would like to ____________, so that I can ____________. | ![screenshot](documentation/feature02.png) |
| As a new site user, I would like to ____________, so that I can ____________. | ![screenshot](documentation/feature03.png) |
| As a returning site user, I would like to ____________, so that I can ____________. | ![screenshot](documentation/feature04.png) |
| As a returning site user, I would like to ____________, so that I can ____________. | ![screenshot](documentation/feature05.png) |
| As a returning site user, I would like to ____________, so that I can ____________. | ![screenshot](documentation/feature06.png) |
| As a site administrator, I should be able to ____________, so that I can ____________. | ![screenshot](documentation/feature07.png) |
| As a site administrator, I should be able to ____________, so that I can ____________. | ![screenshot](documentation/feature08.png) |
| As a site administrator, I should be able to ____________, so that I can ____________. | ![screenshot](documentation/feature09.png) |
| repeat for all remaining user stories | x |

## Bugs

There are no remaining bugs that I am aware of.

## Unfixed Bugs

- JS Uncaught ReferenceError: `carousel` is undefined directly in the FancyApp's code.

    ![screenshot](documentation/js-test.png)

    The site is still fully functional with the included java-script code. The code was directly sourced from [FancyApps - Carousel](https://fancyapps.com/carousel/getting-started/). I solved the issue by including the attributed jshint esversion: 11 for clarity. 


Some examples:

- On devices smaller than 375px, the page starts to have `overflow-x` scrolling.

    ![screenshot](documentation/unfixed-bug01.png)

    - Attempted fix: I tried to add additional media queries to handle this, but things started becoming too small to read.

- For PP3, when using a helper `clear()` function, any text above the height of the terminal does not clear, and remains when you scroll up.

    ![screenshot](documentation/unfixed-bug02.png)

    - Attempted fix: I tried to adjust the terminal size, but it only resizes the actual terminal, not the allowable area for text.

- When validating HTML with a semantic `section` element, the validator warns about lacking a header `h2-h6`. This is acceptable.

    ![screenshot](documentation/unfixed-bug03.png)

    - Attempted fix: this is a known warning and acceptable, and my section doesn't require a header since it's dynamically added via JS.

⚠️⚠️⚠️⚠️⚠️ START OF NOTES (to be deleted) ⚠️⚠️⚠️⚠️⚠️

If you legitimately cannot find any unfixed bugs or warnings, then use the following sentence:

🛑🛑🛑🛑🛑 END OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

There are no remaining bugs that I am aware of.
