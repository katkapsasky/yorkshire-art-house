# Testing

Click to return back to the [README.md](README.md) file. 

Manual testing has been carried out which includes:
- Testing form validates input and redirects to confirmation page
- Navbar links work correctly
- Call to action link is correctly redirecting to events page
- All internal links open in the same page
- All external links open in a new tab
- Images are showing correctly and alt attributes have been added
- Text and images are visible on desktop, tablet and mobile screens

## Browser Compatibility 

The website has been tested on Google Chrome, Safari and Edge. The screenshots below show sections of the site on each browser.
![Google Chrome](documentation/responsiveness/gallerypage-resp-tablet.png)
![Safari](documentation/responsiveness/homepage-resp-mobile.png)
![Edge](documentation/responsiveness/eventspage-resp-desktop-edge.png)

## Code Validation

HTML Validation:
![HTML Homepage Validation](documentation/codevalidation/html-homepage-validation.png)
https://validator.w3.org/nu/?doc=https://katkapsasky.github.io/yorkshire-art-house/index.html
![HTML Gallery page Validation](documentation/codevalidation/html-gallerypage-validation.png)
https://validator.w3.org/nu/?doc=https://katkapsasky.github.io/yorkshire-art-house/gallery.html
![HTML Events page Validation](documentation/codevalidation/html-eventspage-validation.png)
https://validator.w3.org/nu/?doc=https://katkapsasky.github.io/yorkshire-art-house/events.html
![HTML Confirmation page Validation](documentation/codevalidation/html-confirmationpage-validation.png)
https://validator.w3.org/nu/?doc=https://katkapsasky.github.io/yorkshire-art-house/confirmation.html

CSS Validation:
![CSS Validation](documentation/codevalidation/css-validation.png)
https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fkatkapsasky.github.io%2Fyorkshire-art-house

## Responsiveness

| Page | Screensize | Responsiveness |
| --- | --- | --- |
| Home Page | Mobile | ![mobile](documentation/responsiveness/homepage-resp-mobile.png) |
| Home Page | Tablet | ![tablet](documentation/responsiveness/homepage-resp-tablet.png) |
| Home Page | Desktop | ![desktop](documentation/responsiveness/homepage-resp-desktop.png) |
| Gallery Page | Mobile | ![mobile](documentation/responsiveness/gallerypage-resp-mobile.png) |
| Gallery Page | Tablet | ![tablet](documentation/responsiveness/gallerypage-resp-tablet.png) |
| Gallery Page | Desktop | ![desktop](documentation/responsiveness/gallerypage-resp-desktop.png) |
| Events Page | Mobile | ![mobile](documentation/responsiveness/eventspage-resp-mobile.png) |
| Events Page | Tablet | ![tablet](documentation/responsiveness/eventspage-resp-tablet.png) |
| Events Page | Desktop | ![desktop](documentation/responsiveness/eventspage-resp-desktop.png) |

## Accessibility

## Bugs

### Fixed Bugs

![error 501 fixed bug](documentation/bugs/error-501.png)

The form was initially set up to send submitted data to the Code Institute Formdump and so was set up with a method of Post. When creating the confirmation page for users who have submitted information via the form I received an error 501.

By removing the method and it's value of post from the form I fixed the bug and users who submit the form are now correctly redirected to the confirmation page.

### Unfixed Bugs

There are no remaining bugs that I am aware of.