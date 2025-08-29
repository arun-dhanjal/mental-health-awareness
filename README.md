# Healthy Minds website

The Healthy Minds website is designed to be informative, easy to navigate, and responsive. It presents information on mental health awareness, including signs to look out for and ways to address mental health challenges.

![Healthy Minds website shown on a range of devices](/readme-docs/devices-showcase.jpg)

[View Healthy Minds on Github Pages](https://arun-dhanjal.github.io/mental-health-awareness/)

## CONTENTS

* [User Stories](#User-Stories)
  * [User Story 1](#user-story-1-useful-information-on-recognising-and-addressing-mental-health-issues-1--must-have)
  * [User Story 2](#user-story-2-a-responsive-website-that-works-well-on-all-devices-2--must-have)
  * [User Story 3](#user-story-3-a-calming-well-organised-and-easy-to-navigate-website-3--must-have)
  * [User Story 4](#user-story-4-positive-affirmations-and-pleasant-imagery-4--should-have)
  * [User Story 5](#user-story-5-upcoming-events-and-sign-up-5--could-have)

* [Design](#Design)
  * [Colour Scheme](#Colour-Scheme)
  * [Typography](#Typography)
  * [Imagery](#Imagery)
  * [Page Layout](#Page-Layout)
  * [Features](#Features)
  * [Accessibility](#Accessibility)

* [Technologies Used](#Technologies-Used)
  * [Languages Used](#Languages-Used)
  * [Frameworks, Libraries & Programs Used](#Frameworks-Libraries--Programs-Used)

* [Deployment](#Deployment)

* [Testing](#Testing)
  * [W3C Validator: HTML](#W3C-Validator-HTML)
  * [W3C Validator: CSS](#W3C-Validator-CSS)
  * [Lighthouse: mobile](#Lighthouse-mobile)
  * [Lighthouse: desktop](#Lighthouse-desktop)

* [Credits](#Credits)

- - -

## User Stories

### User Story 1: Useful information on recognising and addressing mental health issues (#1 – must have)
 
As a very busy university student I would like to get information on warning signs of mental health issues so that I can recognise when I’m being affected by them and take action to address them.

##### Acceptance Criteria
* A section on the webpage with easy-to-digest information on how to recognise if you are experiencing mental health issues.
* A section on the webpage with easy-to-digest information on how to manage mental health issues.

#### Tasks
* Create a section in the main body of the webpage with at least 4 cards that demonstrate warning signs of mental health issues.
* Create a section in the main body of the webpage with at least 4 cards that demonstrate actions that can be taken to address mental health issues.

### User Story 2: A responsive website that works well on all devices (#2 – must have)

As a mental health coach that works with clients of varying tech-literacy, I would like to recommend a mental health awareness website to them that works on all devices, so that each of my clients can access it, regardless of the tech they have access to.

#### Acceptance Criteria
* The website is responsive and fully functional on all device sizes, including phones, tablets, laptops, and desktops.

#### Tasks
* Use Bootstrap to handle responsiveness, ensuring the correct  Bootstrap classes are used to create separate layouts for each device size.

### User Story 3: A calming, well-organised, and easy-to-navigate website (#3 – must have)

As an extremely busy mother of 3 children, I want a resource that can help me manage my high stress levels as easily and as pleasantly as possible, so that I don’t exacerbate my level of stress.  

#### Acceptance Criteria
* The layout of the webpage should be well-organised and easy-to-navigate.
* The design (font and colour choices) should be calming.

#### Tasks
* Implement all elements on the webpage in a highly organised fashion.
* Implement navigation functionality that is easy-to-use and clearly signposted.
* Use fonts and colours that are subdued and complementary as opposed to bright and garish.

### User Story 4: Positive affirmations and pleasant imagery (#4 – should have)

As a school student revising for my exams I would like a quick-and-easy way to feel better when I’m overwhelmed so that I can get back to my studies.

#### Acceptance Criteria
* A section on the webpage with positive affirmations and pleasant imagery to quickly address the needs of users that are stressed or overwhelmed.

#### Tasks
* Create a section on the webpage with at least 8 positive affirmations.
* Accompany each affirmation with a pleasant image.

### User Story 5: Upcoming events and sign-up (#5 – could have)

As a psychologist that works in the field of mental health, I would like to get information on any upcoming mental health events and sign up to them so I can network and expand my knowledge in this area.

#### Acceptance Criteria
* A section on the webpage with a list of upcoming mental health events and the option to sign up to them.

#### Tasks
* Create a table showing the following details for all upcoming mental health events: event name; topic; speakers; date.
* Create a sign-up form next to the events table that allows the following inputs: Full Name; Email Address; Phone Number; chosen event (dropdown).
* Ensure the input fields have automatic validation.
* Create a success page that shows after successful signup.

- - -

## Design

### Colour Scheme

![Healthy Minds Website Colour Palette](/readme-docs/Healthy%20Minds%20palette.png)

The website uses a palette of pastel greens and browns inspired by the hero image of the website, which itself was generated by Copilot. The colour palette was created using the [Coolors](https://coolors.co/) website.

### Typography

Although other fonts could have been implemented, the default fonts work very well with the design of the website and so no other fonts have been selected. However, other fonts could be used in future iterations, in which case Google Fonts will be utilised for this purpose.

### Imagery

All images, including the hero image and the card images, were generated by Microsoft Copilot based on the website author's prompts. These prompts were written with the intent to align with the colour scheme noted above.

### Page Layout

Wireframes have not been used in the design of page layouts on this occasion. Instead, the intended page layout is expressed below. Note that sm, md, lg, and xl refer to Bootstrap breakpoints.


#### Navigation
* Icon and site name on the left (should redirect back to the top of the page when clicked)
* Navigation links on the right: Home, Signs, Strategies, Affirmations, Events, Contact

  * *sm: collapsed menu*
  * *md: collapsed menu*
  * *lg: expanded menu*
  * *xl: expanded menu*


#### Header
* Hero image with site name and some intro text on top

  * *sm: image stretches full width; text stretches 10 columns*
  * *md: image stretches full width; text stretches 8 columns*
  * *lg: image stretches full width; text stetches 6 columns*
  * *xl: image stretches full width; text stretches 4 columns*


#### Signs of Mental Health Challenges
* 4 cards, each showing a separate sign of mental health challenges
* Each card will show an image, a heading, and some text

  * *sm: centred heading and text; all cards stacked*
  * *md: centred heading and text; 2 columns of cards*
  * *lg: left-aligned heading and text; 2 columns of cards*
  * *xl: left-aligned heading and text; 2 columns of cards*


#### Strategies to Manage Mental Health Challenges
* 4 cards, each showing a separate strategy to manage mental health
* Each card will show an image, a heading, and some text

  * *sm: centred heading and text; all cards stacked*
  * *md: centred heading and text; 2 columns of cards*
  * *lg: right-aligned heading and text; 2 columns of cards*
  * *xl: right-aligned heading and text; 2 columns of cards*


#### Positive Affirmations
* 8 images on a carousel, each with a short positive affirmation on it
* The carousel should have controls and should scroll automatically

  * *sm: centred heading and text above centred carousel*
  * *md: centred heading and text above centred carousel*
  * *lg: left-aligned heading and text with right-aligned carousel*
  * *xl: left-aligned heading and text with right-aligned carousel*


#### Events
* An Events timetable showing 5 upcoming events with names, topics, speakers, and dates
* A short signup form with inputs for Full Name, Email Address, selected Event (from a dropdown), and a submit button

  * *sm: centred events heading and text and timetable and signup form; all elements stacked*
  * *md: centred events heading and text and timetable and signup form; all elements stacked*
  * *lg: events heading and text and timetable on the left; signup form on the right*
  * *xl: events heading and text and timetable on the left; signup form on the right*


#### Successful signup page (separate page)
* Upon successful signup to an event, a success page will show up
* This page will have a message advising on the successful signup
* It will also have a button to return to the home page
* This page will also have the Nav bar at the top and the footer at the bottom

  * *sm: centred text above button*
  * *md: centred text above button*
  * *lg: centred text above button*
  * *xl: centred text above button*


#### Footer
* Note on who designed the website
* Contact details at the bottom left
* Social media links (just icons)

  * *sm: all 3 elements stacked and centred*
  * *md: all 3 elements stacked and centred*
  * *lg: designer name on left; social media icons in middle; contact details on right*
  * *xl: designer name on left; social media icons in middle; contact details on right*

### Features

* Navigation bar:

  * The website logo and name is on the left.

  * Navigation to other sections of the webpage are possible via the top right.

  * On mobile and tablet the navigation options are available via a dropdown menu. On larger devices the menu options are always visible.

  ![Navigation bar screenshot](/readme-docs/navigation-bar.jpg)

* Hero section:

  * An image of a calming landscape spans the full width of the page and 50% of the height of the page.

  * The website name and some introductory text is centered on this image in white text.

  ![Hero section screenshot](/readme-docs/hero-section.jpg)

* Common Signs section:

  * This section has a title with some explanatory text in black.

  * 4 cards are displayed, each with information on common signs of mental health challenges.

  * Each card contains an associated image, a title, and some text.

  * The layout of the 4 cards adapts to the screen size being used.

  ![Common Signs section screenshot](/readme-docs/common-signs-section.jpg)

* Strategies section:

  * This section has a title with some explanatory text in black.

  * 4 cards are displayed, each with information on strategies to tackle mental health challenges.

  * Each card contains an associated image, a title, and some text.

  * The layout of the 4 cards adapts to the screen size being used.

  ![Strategies section screenshot](/readme-docs/strategies-section.jpg)

* Footer:

  * This section contains: information on the website creator; social media links; contact information.

  * The website creator information is left aligned and in white text.

  * The social media links are center aligned and have a hover effect implemented.

  * The contact information is right aligned and in white text.

  ![Footer screenshot](/readme-docs/footer.jpg)

* Future implementations:

  * The Positive Affirmations section of the website is yet to be created, but can be included in a future iteration.

  * The Events timetable and signup for is yet to be created, but can be included in a future iteration.

### Accessibility

I have been mindful during coding to ensure that the website is as accessible friendly as possible. I have achieved this by:

* Using semantic HTML.

* Using descriptive alt attributes on images on the site.

* Ensuring that there is a sufficient colour contrast throughout the site.

- - -

## Technologies Used

### Languages Used

HTML and CSS were used to create this website.

### Frameworks, Libraries & Programs Used

Git - For version control.

GitHub - To save and store the files for the website.

Bootstrap Version 5.3 - Code throughout the website, but mainly for the navigation bar and cards, were used and modified. Additional CSS styling was also implemented in style.css.

Font Awesome - For the social media icons.

Google Dev Tools - To troubleshoot and test features, solve issues with responsiveness and styling.

Microsoft Copilot - For code queries and generation of text and images.

[Tiny PNG](https://tinypng.com/) - To compress images.

[Favicon.io](https://favicon.io/) - To create favicons.

[Am I Responsive?](http://ami.responsivedesign.is/) - To show the website image on a range of devices.

- - -

## Deployment

Github Pages was used to deploy the live website. The instructions to achieve this are below:

1. Log in to Github.
2. Find the repository for this project: mental-health-awareness.
3. Click on the Settings link.
4. Click on the Pages link in the left hand side navigation bar.
5. In the Source section, choose main from the drop down select branch menu. Select Root from the drop down select folder menu.
6. Click Save. Your live Github Pages site is now deployed at the URL shown.

- - -

## Testing

Testing was ongoing throughout the entire build. I utilised Chrome developer tools while building to pinpoint and troubleshoot any issues as I went along, as well as Microsoft Copilot to query specific coding logic queries.

More comprehensive testing was carried out on completion of the build using dedicated validation software, as shown below.

### W3C Validator: HTML

![HTML validation screenshot](/readme-docs/html-validation.jpg)

### W3C Validator: CSS

![CSS validaton screenshot](/readme-docs/css-validation.jpg)

### Lighthouse: mobile

![Lighthouse mobile validation screenshot](/readme-docs/lighthouse-mobile-validation.jpg)

### Lighthouse: desktop

![Lighthouse desktop validation screenshot](/readme-docs/lighthouse-desktop-validation.jpg)

- - -

## Credits

### Content and images

Content for the website was primarily generated by Microsoft Copilot using prompts from the website creator, Arun Dhanjal. This includes the hero image, section headings, card images, and card text content. The website name and hero text was thought of by Arun Dhanjal directly.