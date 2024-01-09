# Testing

Return back to the [README.md](README.md) file.

## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.


| Page | W3C URL | Screenshot | Notes |
| --- | --- | --- | --- |
| Index | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fmikavir.github.io%2Fheartcare-hub%2Findex.html) | ![screenshot](documentation/html-validation-index.png) | Pass: no errors |
| Information | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fmikavir.github.io%2Fheartcare-hub%2Finformation.html) | ![screenshot](documentation/html-validation-information.png) | Pass: no errors |
| Location | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fmikavir.github.io%2Fheartcare-hub%2Flocation.html) | ![screenshot](documentation/html-validation-location.png) | Pass: No Errors |
| Contact | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fmikavir.github.io%2Fheartcare-hub%2Fcontact.html) | ![screenshot](documentation/html-validation-contact.png) | Pass: No Errors |
| Confirmation page |[W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fmikavir.github.io%2Fheartcare-hub%2Fconfirmation-page.html) | ![screenshot](documentation/html-validation-confirmation-page.png) 

### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

| File | Jigsaw URL | Screenshot | Notes |
| --- | --- | --- | --- |
| style.css | [Jigsaw](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fmikavir.github.io%2Fheartcare-hub) | ![screenshot](documentation/css-validation-style.png) | Only warnings on external library bootstrap show |


## Browser Compatibility

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Home | Information | Location | Contact | Confirmation | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Chrome | ![screenshot](documentation/browser-chrome-index.png) ![screenshot](documentation/browser-chrome-index1.png)| ![screenshot](documentation/browser-chrome-information.png)  ![screenshot](documentation/browser-chrome-information1.png)| ![screenshot](documentation/browser-chrome-location.png) ![screenshot](documentation/browser-chrome-location1.png) ![screenshot](documentation/browser-chrome-location2.png)| ![screenshot](documentation/browser-chrome-formv1.png) ![screenshot](documentation/browser-chrome-formv1-1.png) ![screenshot](documentation/browser-chrome-formv1-2.png)| ![screenshot](documentation/browser-chrome-confirmationv1.png)|Works as expected |
| Firefox | ![screenshot](documentation/browser-firefox-index.png) ![screenshot](documentation/browser-firefox-index1.png) | ![screenshot](documentation/browser-firefox-information.png) ![screenshot](documentation/browser-firefox-information1.png)| ![screenshot](documentation/browser-firefox-location.png) ![screenshot](documentation/browser-firefox-location1.png) ![screenshot](documentation/browser-firefox-location2.png)| ![screenshot](documentation/browser-firefox-formv1.png) ![screenshot](documentation/browser-firefox-formv1-1.png) ![screenshot](documentation/browser-firefox-formv1-2.png) | ![screenshot](documentation/browser-firefox-confirmationv1.png)| Works as expected |
| Safari | ![screenshot](documentation/browser-safari-index.png) ![screenshot](documentation/browser-safari-index1.png)| ![screenshot](documentation/browser-safari-information.png) ![screenshot](documentation/browser-safari-information1.png) | ![screenshot](documentation/browser-safari-location.png) ![screenshot](documentation/browser-safari-location1.png) ![screenshot](documentation/browser-safari-location2.png)| ![screenshot](documentation/browser-safari-formv1-1.png) ![screenshot](documentation/browser-safari-formv1.png) ![screenshot](documentation/browser-safari-formv1-2.png)| ![screenshot](documentation/browser-safari-confirmationv1.png)| Works as expected|


## Responsiveness

I've tested my deployed project on multiple devices to check for responsiveness issues.

| Device | Index | Information | Location | Contact | Confirmation | Notes |
| --- | ---- | ---- | ---- | ---- | ---- | ---- |
| Mobile (DevTools) Iphone XR | ![screenshot](documentation/responsive-mobile-index.png) | ![screenshot](documentation/responsive-mobile-informationv2.png) ![screenshot](documentation/responsive-moile-informationv2-1.png) | ![screenshot](documentation/responsive-mobile-location.png) ![screenshot](documentation/responsive-mobile-location1.png) ![screenshot](documentation/responsive-mobile-location2.png)| ![screenshot](documentation/responsive-mobile-contactv1.png) | ![screenshot](documentation/responsive-mobile-confirmationv1.png)| Works as expected |
| Tablet (DevTools) Ipad Air | ![screenshot](documentation/responsive-tablet-index.png) | ![screenshot](documentation/responsive-tablet-information.png) ![screenshot](documentation/responsive-tablet-information1.png) | ![screenshot](documentation/responsive-tablet-location.png) ![screenshot](documentation/responsive-tablet-location1.png) | ![screenshot](documentation/responsive-tablet-contactv1.png) | ![screenshot](documentation/responsive-tablet-confirmationv1.png) | Works as expected |
| Desktop | ![screenshot](documentation/responsive-desktop-index.png) | ![screenshot](documentation/browser-chrome-information.png) ![screenshot](documentation/browser-chrome-information1.png)| ![screenshot](documentation/browser-chrome-location.png) ![screenshot](documentation/browser-chrome-location1.png) ![screenshot](documentation/browser-chrome-location2.png) | ![screenshot](documentation/browser-chrome-formv1.png) ![screenshot](documentation/browser-chrome-formv1-1.png) ![screenshot](documentation/browser-chrome-formv1-2.png) | ![screenshot](documentation/browser-chrome-confirmationv1.png) | Works as expected |
| Own Device (Iphone 13 pro) |![screenshot](documentation/own-device-index.PNG) ![screenshot](documentation/own-device-index1.PNG) ![screenshot](documentation/own-device-index2.PNG)| ![screenshot](documentation/own-device-information.PNG) ![screenshot](documentation/own-device-information1.PNG) ![screenshot](documentation/own-device-information2.PNG)| ![screenshot](documentation/own-device-location.PNG) ![screenshot](documentation/own-device-location1.PNG) ![screenshot](documentation/own-device-location2.PNG) | ![screenshot](documentation/own-device-contact.PNG) ![screenshot](documentation/responsive-iphone-v1.PNG) ![screenshot](documentation/own-device-contact2.PNG) ![screenshot](documentation/own-device-contact3.PNG) | ![screenshot](documentation/responsive-iphone-confirmationv1-1.PNG) ![screenshot](documentation/own-device-confirmation2.PNG) ![screenshot](documentation/own-device-confirmation3.PNG)| Works as expected |

## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page | Mobile | Desktop | Notes |
| --- | --- | --- | --- |
| Home | ![screenshot](documentation/lighthouse-index-mobile.png) | ![screenshot](documentation/lighthouse-index-desktop.png) | Performance score affected due to slow response time due to large image and use of external libary in mobile device |
| Information | ![screenshot](documentation/lighthouse-information-mobile.png) | ![screenshot](documentation/lighthouse-information-desktop.png) |Performance score affected due to slow response time due to large image and use of external libary in mobile device|
| Location | ![screenshot](documentation/lighthouse-location-mobile.png) | ![screenshot](documentation/lighthouse-location-desktop.png) | Performance score affected due to slow response time due to large image and use of external libary in mobile device |
| Contact | ![screenshot](documentation/lighthouse-contact-mobile.png)  | ![screenshot](documentation/lighthouse-contact-desktop.png) | Performance score affected due to slow response time due to large image and use of external libary in mobile device |
| Confirmation | ![screenshot](documentation/lighthouse-confirmation-mobile.png)  | ![screenshot](documentation/lighthouse-confirmation-desktop.png) | Performance score affected due to slow response time due to large image and use of external libary in mobile device |
## User Story Testing

| User Story | Screenshot |
| --- | --- |
| - As a returning site user, I would like to gain knowledge of cardiac surgery and what it involves, so that I can gain understanding. | ![screenshot](documentation/feature02.png) |
| As a new site user, I would like to know if I am eligible for the role, so that I can consider the job. | ![screenshot](documentation/feature02.png) |
| As a new site user, I would like to know the benefits of being a cardiac health professional, so that I can consider it as an employment. | ![screenshot](documentation/feature03.png) |
|- As a new site user, I would like to know where they do cardiac surgery, so that I can consider the location of employment. | ![screenshot](documentation/feature01.png) |
| As a returning site user, I would like to know the locations, so that I can consider the locations for employment.| ![screenshot](documentation/feature04.png) |
| As a returning site user, I would like to find contact information, so that I can get in touch for potential employment. | ![screenshot](documentation/feature05.png) |
| As a returning site user, I would like to gain resources, so that I can be knowledgeable on the commencement of employment. | ![screenshot](documentation/feature02.png) |
| As a site administrator, I would like to have a clear logo, so that I can increase my brand recognition. | ![screenshot](documentation/feature07.png) |
| As a site administrator, I would like to add my social media links, so that I can improve my online presence. | ![screenshot](documentation/feature06.png) |
| As a site administrator, I would like a intriguing prompt, so that I can increase the likelihood of recruitment| ![screenshot](documentation/feature03.png) |
| As a site administrator, I would like to create a way to connect, so that I can foster trust and credibility with my target audiences. | ![screenshot](documentation/feature05.png)|

## Form Testing

I have succesfuly tested the form in the contact page by submitting it via "post" using the [Code Institute Form Dump](https://formdump.codeinstitute.net/). This has now been changed to redirect to confirmation-page.html via "get" for a better user experience and feedback. This will be changed in the future, once I have the required backend to store the data. 

- ![screenshot](documentation/form-test.png)

## Bugs

- Font not all aligned in contact.html in the tablet version.

    ![screenshot](documentation/bug01.png)

    - To fix this, I increased the font size of the doctor icon to large in my contact.html.

- White space on the sides.

    ![screenshot](documentation/browser-chrome-index.png)

    - To fix this, I have set div col under the div rows as the main was a container fluid and set padding to zero.

- When information nav is clicked, the heading in the information page is obscured. 

    ![screenshot](documentation/bug02.png)

    -To fix this, I have added scroll margin top to the class that targets that heading elememts ie. ".data-comtainer h4, h5".


- When the location card is clicked and directed to the anchor points, the location heading is obscured by the fixed header.

    ![screenshot](documentation/unfixed-bug01.png)

    - ~~ Attempted fix: I have added and set scroll-margin-top to the size of my fixed navigation bar of 5em in the #location-information, but the css element is not showing. I have tried to find resources online and there was no solution found. ~~ 
    - To fix this, I have added the id name of the individual locations.


## Unfixed Bugs

There are no unfixed bugs that I am aware of.

