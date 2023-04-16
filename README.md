# Jangles Home Boarding, Walking & Day Care Website
Jangles Home Boarding, Walking & Day Care is a small, independent business in Caerphilly, South Wales that was established in 2014. It provides a home from home experience for your dog and goes the extra mile to ensure that your dog has the best time possible during their stay. It is a service me and my wife have used for 7 years with our two dogs, so we have first-hand experience of how wonderful the service is and how well the dogs are treated. The business is heavily active on social media, however, they have not had a website for a number of years. I believe that a well designed and informative website will be an invaluable tool in providing useful information to new and existing customers whilst promoting the brand.

![Visual Representation](documentation/responsive_image.jpg)

## User Experience (UX) & Design
---
### User Stories
- First Time Visitor

   - As a first time visitor, I want to get to understand the main purpose of the site.
   - As a first time visitor, I want to be able to easily navigate the site to find the content I require.
   - As a first time visitor, I want to know how much the services provided cost.
   - As a first time visitor, I want to see where the business is located.


- Returning Visitor

   - As a returning visitor, I want to easily view the gallery page.
   - As a returning visitor, I want to be able to contact the business owner about specific dates for boarding.
   - As a returning visitor, I want to easily find customer reviews for the business.


- Website Administrator
   
   - As a website administrator, I would like to display and update the gallery with ease.
   - As a website administrator, I would like to be contactable via the website directly to my email address.
### Color Scheme
### Typography
Google Fonts were sued to import the Poppins and Sintony font styles in the style.css file.
### Wireframes
Each link contains wireframes for mobile, tablet and desktop.
   - [Home/Index](documentation/index_home.png)
   - [About Us](documentation/about_us.png)
   - [Gallery](documentation/gallery.png)
   - [Price List](documentation/gallery.png)
   - [Contact Us](documentation/gallery.png)
   - [Thank You](documentation/thank_you.png) - This is displayed in place of an actual submission to a back end server.
---
## Features
---
### Navigation Bar
### Footer
### Home page
### About
### Gallery
### Price List
### Contact
### Thank You
---
## Technologies Used
---
### Languages Used
- [HTML5](https://en.wikipedia.org/wiki/HTML5)
- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### Frameworks, Libraries and Programs Used
- [Balsamiq](https://balsamiq.com/) was used for pre-visualisation of the pages.
- [Google Fonts](https://fonts.google.com/) was used to import the the 'Poppins' and 'Sintony' fonts into the style.css file.
- [Font Awesome](https://fontawesome.com/) was utilised for icons used on the site, including the socila media icons.
- [Bootstrap]() was used for responsive grids, table and elements of the contact form
- [Git](https://git-scm.com/) was used for version control. I utilised the CLI terminal in GitPod & codeanywhere to commit and push to GitHub.
- [GitPod](https://gitpod.io) was used as the cloud based enviroment based on VS Code to develop the site.
- [codeanywhere](https://www.codeanywhere.com) was also used as the cloud based enviroment based on VS Code to develop the site.
- [GitHub](https://github.com/) was used as the repository for the project after being pushed from GitPod.
- [Google Maps](https://www.google.com/maps) for the business location map.

## Testing
---
### Validator Testing
#### HTML
#### CSS
### Browser Compatibility
### Manual Testing and Results
### User Story Tetsing
### Lighthouse Test
### Responsiveness
### Bugs
- When setting up the contact form I was unable to align the submit button within a DIV to the center. I tried a few methods I thought would work with no such luck. A Google search provided the answer and the following code resolved the issue:
```css
.button_position {
    display: block;
    margin: 0 auto;
}
```
Acknowledged in the credits section for the assitance provided.

- I was experiencing side-scroll on the mobile version of the contact page. The input boxes were exceeding the width of the screen and casugin the side scroll.  I added the following code to my CSS targeting the form and this seems to have resolved the issue:
```css
max-width: 300px;
```
However, I believe this to be a temporary solution to one problem as the input boxes still expand to the maximum width of the container. I'll look to amend this in a further update wher the information this page expands from a single column on mobile to 3 coloumns on desktop in a future update.

### Unfixed Bugs
---
## Deployment
---
### How the site was deployed
---
## Credits & Acknowledgements
---
- Credit to RenatoSZ at [Stackoverflow](https://stackoverflow.com/questions/7560832/how-to-center-a-button-within-a-div) for his answer in helping me align my submit button within a DIV tag.
- A massive thank you to Cath Jones of Jangles Home Boarding, Walking & Day Care for allowing me to use all the wonderful images she has taken of the dogs.