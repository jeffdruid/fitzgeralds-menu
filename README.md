# Fitzgerald Bar Drinks Menu

This project aims to create a digital menu for Fitzgerald's Bar, being accessible via a QR code.

![Main Pages](assets/media/main-hero.PNG)

<img src="assets/media/qr-code.png" alt="QR code" width="150" height="150">

## Table of Contents

1. [Introduction](#introduction)
1. [Technologies Used](#technologies-used)
1. [User Stories](#user-stories)
1. [Features](#features)
    - [Index](#index)
    - [Menu](#menu)
    - [Navbar](#navbar)
    - [About](#about)
    - [Contact](#contact)
1. [Wireframe](#wireframe)
1. [Testing](#testing)
    - [Validator Testing](#validator-testing)
        - [HTML](#html)
        - [CSS](#css)
    - [Accessibility](#accessibility)
    - [Responsiveness](#responsiveness)
    - [Manual Testing](#manual-testing)
        - [Cross-browser Compatibility](#cross-browser-compatibility)
        - [Responsiveness and Device Compatibility](#responsiveness-and-device-compatibility)
        - [Link Validation](#link-validation)
        - [Text and Font Readability](#text-and-font-readability)
        - [Acceptance Test](#acceptance-test)
        - [Desktop](#desktop)
        - [Tablet](#tablet)
        - [Mobile](#mobile)
    - [Bugs](#bugs)
    - [UI Improvements](#ui-improvements)
1. [Deployment](#Deployment)
    - [Cloning & Forking](#cloning--forking)
    - [Local Deployment](#local-deployment)
    - [Remote Deployment](#remote-deployment)
1. [Credits](#credits)
    - [Source Code](#source-code)
    - [Icons](#icons)
    - [Videos](#videos)
    - [Images](#images)
    - [Useful links](#useful-links)

## Introduction

Fitzgerald's Bar currently lacks a digital drinks menu, causing inconvenience for customers who have to physically go to the bar to view available drinks. This project aims to solve this problem by providing an interactive, user-friendly digital drinks menu accessible via QR code.

## Technologies Used

- HTML5
- CSS3

## User Stories
|Story No.|Story Description|Acceptance Criteria|
| ----- | ----- | -----|
|1| As a customer, I want to be able to access Fitzgerald's drinks menu digitally via QR code.| I know I am done when the menu page is displayed after scanning the QR code.|
|2| As a customer, I want to be able to navigate between different sections of the digital menu.| I know I am done when the navigation links for menu sections (Menu, About, Contact) are clickable and take me to the respective sections.|
|3| As a customer, I want to be able to see the list of available drinks. |I know I am done when the menu page displays the list of available drinks.|
|4| As a customer, I want to be able to view additional information about each available drink. |I know I am done when I can hover or click each drink to reveal more information.|
|5| As a customer, I want to be able to find links to social media platforms. |I know I am done when I see visible and clickable icons leading to social media profiles.|
|6| As a customer, I want to be able to access more information about the bar. |I know I am done when I click on "About" page in the navigation section and the page displays details about the bar's history, ambiance and features.|
|7| As a customer, I want to be able to contact the bar. |I know I am done when I complete and submit the contact form with the required fields (name, email and message).|

## Wireframe
![Wireframe - All pages](assets/media/Wireframe%20P1.png)
![Wireframe - Index](assets/media/wireframe-index.png)
![Wireframe - Menu](assets/media/wireframe-menu.png)
![Wireframe - Contact](assets/media/wireframe-contact.png)
![Wireframe - About](assets/media/wireframe-about.png)

## Features

- ### Index

![Menu Hero](assets/media/feat-menu-hero.PNG)
*Clicking on the "MENU" heading navigates the user to the meu.html page. Background video starts playing once the page loads, it is set to autoplay, mute and loop.*

- ### Menu
    |||
    |-|-|
    |Display various drinks available at Fitzgerald's bar.|![Menu page](assets/media/feat-menu-page.png)|
    |Each card have an image of the drinks with name, alcohol percentage and price.|![Gallery](assets/media/feat-gallery.PNG)| 
    |Cards have overlays providing additional details upon hover/clicked (mobile).|![Overlay](assets/media/feat-overlay.PNG)|
    |Contains links to social media platforms.|![Footer](assets/media/feat-footer.PNG)|

- ### Navbar
    |||
    |-|-|
    |Provides site's title and navigation links for the menu, about and contact pages.|![Navbar on Mobile](assets/media/feat-navbar-mobile.PNG)|
    |Menu active, showing the current page the user is on.|![Menu Active](assets/media/feat-menu-active.png)|
    |Menu icon, displayed on mobile devices.|![Menu Icon](assets/media/feat-nav-toggle.PNG)|

- ### About
    |||
    |-|-|
    |About active, showing the current page the user is on.|![About Active](assets/media/feat-about-active.png)|
    |Contains information about the bar.|![About Page](assets/media/feat-about-page.PNG)|

- ### Contact
    |||
    |-|-|
    |Contact active, showing the current page the user is on.|![Contact Active](assets/media/feat-contact-active.PNG)|
    |Contains a contact form for users to send messages.|![Contact Page](assets/media/feat-contact-page.png)|
    |Contains a form where users are able to enter their name, email and message, allowing them to contact the bar.|![Form](assets/media/feat-form.PNG)|
    |Displays location of the bar using embedded map.|![Google maps](assets/media/feat-google-maps.PNG)|

## Testing

### Validator Testing

- #### HTML
    - [W3C Validator - Index](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjeffdruid.github.io%2Ffitzgeralds-menu%2Findex.html)
    ![W3C Results - Index](assets/media/test-index.png)
    - [W3C Validator - Menu](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjeffdruid.github.io%2Ffitzgeralds-menu%2Fmenu.html)
    ![W3C Results - Menu](assets/media/test-menu.png)
    - [W3C Validator - About](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjeffdruid.github.io%2Ffitzgeralds-menu%2Fabout.html)
    ![W3C Results - About](assets/media/test-about.png)
    - [W3C Validator - Contact](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjeffdruid.github.io%2Ffitzgeralds-menu%2Fcontact.html)
    ![W3C Results - Contact](assets/media/test-contact.png)

- #### CSS
    - [Jigsaw Validator - CSS](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fjeffdruid.github.io%2Ffitzgeralds-menu%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
    ![Jigsaw Results - CSS](assets/media/test-css.png)

### Accessibility

 Lighthouse results from Google Devtools

![Menu Performance](assets/media/perf-menu.png)
![Gallery Performance](assets/media/perf-gallery.png)
![About Performance](assets/media/perf-about.png)
![Contact Performance](assets/media/perf-contact.png)

### Responsiveness

Screenshots of the various device breakpoints for responsive design.

Viewport - Desktop: 1600x992px / Laptop: 1280x802px / Tablet: 768x1024px / Mobile: 320x480px.

![Responsive Page - Index](assets/media/resp-menu.PNG)
![Responsive Page - Menu](assets/media/resp-menu-page.PNG) 
![Responsive Page - About](assets/media/resp-about.PNG) 
![Responsive Page - Contact](assets/media/resp-contact.PNG) 

### Manual Testing

The manual testing conducted on the page includes the following aspects:

- #### Cross-browser Compatibility

    - Verified the functionality of the page across different web browsers to ensure it works properly and it is consistent.

- #### Responsiveness and Device Compatibility

    - Verified that the project displays correctly and functions appropriately across various device sizes, ensuring a good user experience.

- #### Link Validation

    - Verified all internal and external links to ensure they direct users to the intended destinations and open correctly without issues.

- #### Text and Font Readability

    - Verified that all text content and fonts used on the page are legible, clear, and easy to understand.

 The manual testing confirms that the page operates smoothly across multiple browsers, adapts well to different devices, ensures accurate link navigation, and maintains clear readability for users interacting with the content.

- #### Acceptance Test
    Verified that appropriate error messages prompt the user to fill the missing fields.

    - Prevents user to submit a form without name. 
    ![Form Name](assets/media/feat-form-name-required.PNG) 

    - Prevents user to submit a form without email.
    ![Form Email](assets/media/feat-form-email-required.PNG) 

    - Prevents user to submit a form without a message.
    ![Form Message](assets/media/feat-form-message-required.PNG)

- #### Desktop
    |Safari - Version 16.6|Chrome - Version 120.0.6099.71|Firefox - Version 120.0.1|
    | ------------- | ------------- |------------- |
    |![Index Page - Safari - Desktop](assets/media/browser-safari-index.png)|![Index Page - Chrome - Desktop](assets/media/browser-chrome-index.png)|![Index Page - Firefox - Desktop](assets/media/browser-firefox-index.png)|
    |![Menu Page - Safari - Desktop](assets/media/browser-safari-menu.png)|![Menu Page - Chrome - Desktop](assets/media/browser-chrome-menu.png)|![Menu Page - Firefox - Desktop](assets/media/browser-firefox-menu.png)|
    |![Contact Page - Safari - Desktop](assets/media/browser-safari-contact.png)|![Contact Page - Chrome - Desktop](assets/media/browser-chrome-contact.png)|![Contact Page - Firefox - Desktop](assets/media/browser-firefox-contact.png)|
    |![About Page - Safari - Desktop](assets/media/browser-safari-about.png)|![About Page - Chrome - Desktop](assets/media/browser-chrome-about.png)|![About Page - Firefox - Desktop](assets/media/browser-firefox-about.png)|

- #### Tablet
    |Safari - Version 15.6.1|Chrome - Version 119.0.6045.194|Firefox - Version 120.1.0|
    | ------------- | ------------- |------------- |
    |![Index Page - Safari - Tablet](assets/media/browser-safari-tablet-index.png)|![Index Page - Chrome - Tablet](assets/media/browser-chrome-tablet-index.png)|![Index Page - Firefox - Tablet](assets/media/browser-firefox-tablet-index.png)|
    |![Menu Page - Safari - Tablet](assets/media/browser-safari-tablet-menu.png)|![Menu Page - Chrome - Tablet](assets/media/browser-chrome-tablet-menu.png)|![Menu Page - Firefox - Tablet](assets/media/browser-firefox-tablet-menu.png)|
    |![Contact Page - Safari - Tablet](assets/media/browser-safari-tablet-contact.png)|![Contact Page - Chrome - Tablet](assets/media/browser-chrome-tablet-contact.png)|![Contact Page - Firefox - Tablet](assets/media/browser-firefox-tablet-contact.png)|
    |![About Page - Safari - Tablet](assets/media/browser-safari-tablet-about.png)|![About Page - Chrome - Tablet](assets/media/browser-chrome-tablet-about.png)|![About Page - Firefox - Tablet](assets/media/browser-firefox-tablet-about.png)|

- #### Mobile
    |Safari - Version 17.1.1|Chrome - Version 119.0.6045.194|Firefox - Version 120.1.0 |
    | ------------- | ------------- |------------- |
    |![Index Page - Safari - Mobile](assets/media/browser-safari-mobile-index.png)|![Index Page - Chrome - Mobile](assets/media/browser-chrome-mobile-index.png)|![Index Page - Firefox - Mobile](assets/media/browser-firefox-mobile-index.png)| 
    |![Menu Page - Safari - Mobile](assets/media/browser-safari-mobile-menu.png)|![Menu Page - Chrome - Mobile](assets/media/browser-chrome-mobile-menu.png)|![Menu Page - Firefox - Mobile](assets/media/browser-firefox-mobile-menu.png)|
    |![Contact Page - Safari - Mobile](assets/media/browser-safari-mobile-contact.png)|![Contact Page - Chrome - Mobile](assets/media/browser-chrome-mobile-contact.png)|![Contact Page - Firefox - Mobile](assets/media/browser-firefox-mobile-contact.png)|
    |![About Page - Safari - Mobile](assets/media/browser-safari-mobile-about.png)|![About Page - Chrome - Mobile](assets/media/browser-chrome-mobile-about.png)|![About Page - Firefox - Mobile](assets/media/browser-firefox-mobile-about.png)|

### Bugs
  - Background video not playing on safari
    ![Index Page - Tablet](assets/media/browser-safari-tablet-index.png)
  - Card overlay not working on safari
  - Google maps not being clickable.
        
    ![Fitzgerald's pin on Google Maps](assets/media/feat-google-maps.PNG)
    
    From:
    ```ruby
        #contact iframe {
            z-index: -999;
        }
    ```
    To:
    ```ruby
        #contact iframe {
            z-index: 2;
        }
    ```
    Fixed the issue by adjusting the `z-index` property for the map's `<iframe>`. Changing the `z-index` from `-999` to `2` brought the map to the front, allowing users to interact with it. This prevents the map to be hidden behind other elements on the page, in this case margins or oother content from the contact form.

### UI Improvements
- Extra space between navbar and form in the contact page on mobile devices.
    |Before|After|
    |---|---|  
    |![Contact page - Mobile](assets/media/browser-safari-mobile-contact.png)|![Alt text](assets/media/feat-about-fix-margin.png)|

- Make landing page more intuitive
    TODO
    - ![Index Page - Tablet](assets/media/browser-firefox-tablet-index.png)

- Add Youtube clip in the about section
    - ![Alt text](assets/media/feat-about-youtube.png)

- Add address in the contact section
    - ![Contact Us Page - Desktop](assets/media/browser-safari-contact.png)
    TODO

- Open social links in another tab
    - Added `target="_blank"` to all social links. This ensures that when the user click on these links, they open in a separated tab.
    ![Alt text](assets/media/feat-footer-fix-links.png)

### Future Improvements
- Search function
- Feedback and Review
- Social sharing

## Deployment

### Cloning & Forking
#### Forking a Repository
1. Visit [Fitzgerald's Menu](https://github.com/jeffdruid/fitzgeralds-menu).
2. Click on the "Fork" button located in the top-right corner of the page.
3. Optionally, you can provide a description for your fork.
4. Select "Create fork". You will be redirected to your newly created forked repository.

#### Cloning a Repository
1. Navigate to the repository on Github and click the "Code" button located above the list of files.
2. Click on thee "Code" button and copy the repository's URL.
3. Open your Terminal application on your computer and change the directory to where you want the cloned directory.
4. Enter the command "git clone" followed by the repository's URL. This downloads a copy of the repository into your local machine.

### Local Deployment
1. Sign up for [Gitpod](https://www.gitpod.io/) using your GitHub account.
2. Install the Gitpod browser extension to access Gitpod from GitHub. You can find the extension [here](https://www.gitpod.io/docs/browser-extension/).
3. Go to the [Fitzgerald's Menu](https://github.com/jeffdruid/fitzgeralds-menu).
4. Click on the "GitPod" button above the list of files in the repository on GitHub. This opens Gitpod workspace using the repository.

### Remote Deployment
To deploy the site on GitHub Pages after forking or cloning:

1. Go to your repository on GitHub.
2. Click on the "Settings" tab on the top of your repository.
3. In the left sidebar, click on the "Pages" tab.
4. Under the "Build and Deployment" section, select "main" from the source drop-down list and click on the "Save" button.
5. The page will display the link to the deployed website. You wil see a green success message indicating that your site is published at the specific URL.

You can access the live link here : [Fitzgerald's Menu](https://jeffdruid.github.io/fitzgeralds-menu/index.html)

## Credits

### Source code 

- [Stack Overflow - Changing hover to touch for mobile devices](https://stackoverflow.com/questions/22559756/changing-hover-to-touch-click-for-mobile-devices)
    - Overlay effect on mobile and tablet devices on click.
- [W3Schools - Pseudo classes](https://www.w3schools.com/css/css_pseudo_classes.asp)
    - Use of :active pseudo-class in the overlay card.
- [CodePen - Card Overlay](https://codepen.io/sstromick/pen/qBOeypG)
    - Overlay effect on mobile and tablet devices.
- [Love Running - Navigation Bar](https://github.com/Code-Institute-Solutions/love-running-v3)
    - Navigation Bar on desktop.
- [MDN - Using CSS Transitions](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_transitions/Using_CSS_transitions)
    - Transition effects on toggle navigation bar.
- [W3CSchools - Transitions](https://www.w3schools.com/css/css3_transitions.asp )
    - Transition effects on toggle navigation bar.
- [CSS Tricks - Full-page background video styles](https://css-tricks.com/full-page-background-video-styles)
    - Index page's background video effect.
- [We Tech Talk - Creating a Masonry](https://www.youtube.com/watch?v=-isQPqqnIBo)
    - Menu gallery.
- [Formspree - Form Submission](https://formspree.io/)
    - Form submission.
- [Animate.css](https://github.com/animate-css/animate.css/blob/main/source/attention_seekers/flash.css)
    - Flash animation Menu page.

### Videos
- [Cover Girls](https://www.youtube.com/watch?v=89UkgFiritU&t=1s)

### Images

- [Pexels - Thiago Miranda](https://images.pexels.com/photos/1478386/pexels-photo-1478386.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1)
- [Pexels - Thgusstavo Santana](https://images.pexels.com/photos/2286972/pexels-photo-2286972.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1)
- [Pexels - Guillaume Meurice](https://images.pexels.com/photos/1932514/pexels-photo-1932514.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1)
- [Pexels - Wallace Chuck](https://images.pexels.com/photos/2565587/pexels-photo-2565587.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1)
- [Pexels - Mwabonje Ringa ](https://images.pexels.com/photos/1694853/pexels-photo-1694853.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1)
- [Pexels - Victor Cayke](https://images.pexels.com/photos/17409432/pexels-photo-17409432/free-photo-of-cans-of-beer-in-dew.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1)
- [Pexels - Raynnier Gomez ](https://images.pexels.com/photos/15901846/pexels-photo-15901846/free-photo-of-cold-corona-beer.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1)
- [Pexels - Brett Jordan](https://images.pexels.com/photos/5017804/pexels-photo-5017804.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1)
- [Pexels - S. von Hoerst](https://images.pexels.com/photos/9550788/pexels-photo-9550788.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1)
- [Pexels - ТАРКОС ](https://images.pexels.com/photos/7220272/pexels-photo-7220272.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1)
- [Pexels - Brett Jordan ](https://images.pexels.com/photos/11930130/pexels-photo-11930130.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1)

### Icons

- [FontAwesome](https://fontawesome.com/)

### Useful Links

- [Flipsnack - Menu design ideas: 10 mouth-watering menu fonts](https://blog.flipsnack.com/menu-design-ideas-10-menu-fonts/)
- [NicePage - Black/White Theme](https://nicepage.com/s/79786/black-and-white-colors-of-art-css-template)
- [Dlhamilton - README Reference](https://github.com/dlhamilton/LPSB-Learn-GCSE-CS)