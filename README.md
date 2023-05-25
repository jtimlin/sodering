# SODERING GLAZING LTD.

This is the portfolio project nr 1 for Code Institute. This is a website for a company called Sodering glazing Ltd. (Södertörns/Södering inglasning AB) who is located in Sweden Stockholm.

Company sales balcony and terrace glass roofs and glazings.

![Site view across devices](/assets/images-readme/devices-layout.png)

Link to live website can be found [HERE](https://jindah.github.io/sodering/)

## Tabel of Contents

- [SODERING GLAZING LTD.](#sodering-glazing-ltd)
  - [Tabel of Contents](#tabel-of-contents)
  - [UX](#ux)
  - [Site Purpose](#site-purpose)
  - [Site Goal](#site-goal)
  - [Audience](#audience)
  - [Communication](#communication)
  - [Current User Goals](#current-user-goals)
  - [New User Goals](#new-user-goals)
  - [Design](#design)
    - [Colour Scheme:](#colour-scheme)
    - [Typography:](#typography)
    - [Imagery:](#imagery)
  - [Features](#features)
    - [Existing Features](#existing-features)
      - [Navigation bar:](#navigation-bar)
      - [Landing Page:](#landing-page)
      - [Products Page:](#products-page)
      - [Contact Page:](#contact-page)
      - [Social Links:](#social-links)
    - [Future Features:](#future-features)
  - [Testing](#testing)
    - [Validator Testing](#validator-testing)
    - [Unfixed Bugs](#unfixed-bugs)
  - [Technologies Used](#technologies-used)
    - [Main Languages Used](#main-languages-used)
    - [Frameworks, Libraries \& Programs Used](#frameworks-libraries--programs-used)
  - [Deployment](#deployment)
  - [Credits](#credits)
    - [Content](#content)
    - [Media](#media)

## UX

## Site Purpose

The purpose of the Balcony Glazing Sales website is to provide information about balcony glazing solutions, showcase available products, and offer a platform for customers to inquire and make purchases.

## Site Goal

Our goal is to promote and sell high-quality balcony glazing systems to homeowners, architects, and contractors. We aim to provide detailed product information, showcase successful installations, and offer excellent customer service to ensure customer satisfaction.

## Audience

The target audience for this website includes:

- Homeowners looking for balcony/terrace glazing solutions to enhance their living spaces.
- Architects and contractors seeking reliable glazing systems for their projects.
- Individuals interested in learning about the benefits and options of balcony glazing.

## Communication

The website features a user-friendly interface to help visitors easily access relevant information about balcony glazing sales. It offers clear navigation and intuitive sections, allowing users to explore product details, view installation examples, and request quotes or further assistance.

## Current User Goals

- To explore different balcony glazing options and compare features.
- To view real-life examples of successful balcony glazing installations.
- To request quotes or get in touch with our sales team for further information.

## New User Goals

- To navigate the website effortlessly and understand the available balcony glazing products.
- To learn about the benefits and advantages of balcony glazing systems.
- To easily contact the sales team for inquiries or quotes.

## Design

### Colour Scheme:

Colorming.io was utilized to create a color palette with excellent contrast and harmonious colors that work well together. Colormind, on the other hand, is a color scheme generator that employs deep learning. It has the ability to learn color styles from photographs, movies, and popular artwork.
![Colour Palette](/assets/images-readme/colour-palette.png)

### Typography:

Taviraj was selected for the main heading on each of the pages, accompanied by Josefin Sans and Economica from Google fonts.

### Imagery:

A significant portion of the imagery on the website was sourced from the homepage of company's product suppliers, Malmerkklaasium. Specifically, two of the pictures are taken from the current homepage of Sodering. Credits can be found at the bottom of the readme.

## Features

### Existing Features

#### Navigation bar:

this is included across all three pages, and provides people with an easy reference to navigate between the 'Home', 'Products' & 'Contact' pages.

![Navigation bar](/assets/images-readme/navigation-bar.png)

#### Landing Page:

This defines the feel of the website, providing the user with an image that they can easily associate to what the company is & does.

![Hero image](/assets/images-readme/home-heroimage.jpg)

The About section is listed right beneath the Hero Image, to provide more clarity on the company, and give a better feel to who & what it is.

![About us](/assets/images-readme/home-aboutus.png)

#### Products Page:

First section of products page is about balcony glazing. This section includes a video of the product.

![Balcony glazing card](/assets/images-readme/balcony-glazing.png)

Next on this page is a section about terrace glazing.

![Terrace glazing card](/assets/images-readme/terrace-glazing.png)

#### Contact Page:

First on the contact page is contact information with telephone and email.

![Contact information](/assets/images-readme/contact.png)

If users wish to get in touch with the company, they have the option to use the contact form instead. Additionally, social media links can also be found within the contact form for further engagement. A 'form dump' page has also been included to the project.

![Contact form](/assets/images-readme/form.png)

#### Social Links:

Links to the companies social media pages can be found on the bottom of each page, & each one will take the user to the social media platform being references.

![Social Links](/assets/images-readme/footer.png)

### Future Features:

- Gallery.
- More product information (glass roofs and sun blinds)
- Better navigation for mobile users. (css hamburger menu)

## Testing

I had a problem getting the background image of the index page in the right place. For some reason, there was a gap above the picture. I changed the whole nav section to flexboxes and the problem was solved.

I ran the html files through the validator and got an error code that I had used the same id twice. Changing it to a class fixed the problem.

I also ran the css file through the W3C validator and it was flawless.

The media inquiries turned out to be difficult when I had first made the appearance of the pages suitable for desktop. It should definitely have been made suitable for mobile phones first. The solution to this, however, turned out to be flexboxes. The menu works now, but it could be changed to be more suitable for mobile phones by using a hamburger-style menu.

### Validator Testing

- Html files pass through the [W3C validator](https://validator.w3.org/) with no issues found.
![W3C validator message](/assets/images-readme/validator-html.png)

- CSS files pass through the [Jigsaw validator](https://jigsaw.w3.org/css-validator/) with no issues found.
![Jigsaw validator message](/assets/images-readme/validator-css.png)

- page has an excellent Accessibility rating in Lighthouse
  ![Accessibility score](/assets/images-readme/accessibility-score.png)

- Tested the site opens in Chrome, Safari and Microsoft Edge without issues.

- All links open to external pages as intended.

### Unfixed Bugs

- Navigation menu for mobile users can be better.
- Footer for mobile users can be better.

## Technologies Used

### Main Languages Used

- HTML5
- CSS3

### Frameworks, Libraries & Programs Used

- Google Fonts - for the font families: Special Elite, Raleway & Cabin Sketch. San-serif was used as a default font.
- Font Awesome - to add icons to the social links in the footer element.
- Codeanywhere - to creat my html files & styling sheet before pushing the project to Github.
- GitHub - to store my repository for submission.
- Devtools - to ensure the project looked good across all devices.

## Deployment

The site was deployed to GitHub pages. The steps to deploy are as follows:

- In the GitHub repository, navigate to the Settings tab
- From the source section drop-down menu, select the debloy from a branch
- Once the main branch has been selected, click save and the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

## Credits

### Content

All text content comes from sodering current website https://www.sodering.se.

For the colouring: <http://colormind.io/>
Box shadow code: <https://getcssscan.com/css-box-shadow-examples>

### Media

These two images came from Sodering current website https://www.sodering.se.

- installation_image.jpg at contact page.
- balcony_glazing_1.jpg at products page.

 All the other images on the web page comes from their product supplier "Malmerk klaasium" <https://malmerkklaasium.ee/sv/>
