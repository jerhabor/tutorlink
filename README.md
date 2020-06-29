<img src="assets/images/logo.png" alt="" align="right" width="115" height="auto"/>
 
# [TutorLink](https://jerhabor.github.io/tutorlink/index.html) 
<!-- One or two paragraphs providing an overview of your project. -->

<!-- Essentially, this part is your sales pitch. -->

This website was created for parents & guardians who are in search of a private tutor for their children, as well as students themselves who are well-versed in using technological devices to access and use this site to book a tutor. The site also promotes an opportunity for aspiring tutors to join and share their wealth of knowledge to those in need.

Following the news of the COVID-19 pandemic, there has since been a strain on family members having to perform home-schooling duties for those still in school. TutorLink offers users the opportunity to alleviate this pressure by hiring a qualified tutor to guide their students to academic excellence. The key benefit of this, is that all sessions can take place in the comfort of their own homes. 

Currently, online sessions are strongly recommended for safety reasons. It is without a doubt a growing market thanks to the advancement of technology to this present day. The aim of the site is to connect students to tutors. The online sessions will take place via the video conferencing application, "Zoom". The times and dates of the sessions can be settled in advance by email or text between both the student and the tutor.  This provides flexibility for both parties as lives adjust to the new normal. 
___
## Table of Contents

- [1. User Experience - UX](#1-user-experience---ux)
  * [1.1. User Stories](#11-user-stories)
  * [1.2. Structure and Skeleton](#12-structure-and-skeleton)
- [2. Features](#2-features)
  * [2.1. General Features](#21-general-features)
  * [2.2. Specific Features in Home](#22-specific-features-in-home)
  * [2.3. Specific Features in Tutors](#23-specific-features-in-tutors)
  * [2.4. Specific Features in Subjects](#24-specific-features-in-subjects)
  * [2.5. Specific Features in Contact](#25-specific-features-in-contact)
  * [2.6. Features Left to Implement](#26-features-left-to-implement)
- [3. Technologies Used](#3-technologies-used)
- [4. Testing](#4-testing)
  * [4.1. How to Use Features on TutorLink](#41-how-to-use-features-on-tutorlink)
  * [4.2. Achievement of User Stories](#42-achievement-of-user-stories)
  * [4.3. Code Validation](#43-code-validation)
  * [4.4. Test on Different Browsers](#44-test-on-different-browsers)
  * [4.5. Test on Different Devices](#45-test-on-different-devices)
- [5. Deployment](#5-deployment)
- [6. Credits](#6-credits)
  * [6.1. Content](#61-content)
  * [6.2. Media](#62-media)
  * [6.3. Acknowledgements](#63-acknowledgements)

***

## 1. User Experience - UX
<!-- Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things. -->
The idea of creating a platform to encourage further learning has always been one of my goals. In this case, this site was built to enable the experienced to share and the students to learn at greater depths than they normally would in school. This means that tutors will be able to provide mentorship to students and coach them through their academic journey. To illustrate the connection that this site brings between tutors and students, the name "TutorLink" was therefore birthed (credits to my mother). 

The primary target audience are students and parents/guardians who will sign up on behalf of their children.

The secondary target audience are aspiring tutors.

<!-- In particular, as part of this section we recommend that you provide a list of User Stories, with the following general structure:
- As a user type, I want to perform an action, so that I can achieve a goal. -->

### 1.1. User Stories
As part of the Stategy stage in the five planes of UX, I deemed it necessary to undertake a strategic research process. This involved asking several people what they would expect from this website and tying in these ideas to realise the goals of TutorLink. The target audience came with the following suggestions:

> As a GCSE student, I would like the website to be easy to navigate so that I can see what it offers as quickly as possible.

> As a tutor, I would love to see testimonials from people who have used been taught by us as this will help me in promoting it to other people.

> As a parent of both KS2 and 11+ students, I want to be able to sign up easily so that once I decide to do so, it is quickly over and done with.

> As an A-Level student, there should be the option to choose between face-to-face and virtual tutoring.

> As a parent of an 11+ student, I want your site to convince and reassure me in numerous ways why I should sign up.

> As an A-Level student, I would like to see the full list of tutors so that I can familiarise myself with my chosen tutor's background beforehand.

> As a GCSE student, Link subjects to any recommended revision material so that students can obtain them prior to the first session.


<!-- This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included as a pdf file in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser. -->
These user requirements were traded off and aligned with the stategies of TutorLink in order to establish the project scope. This was predominantly a brainstorming activity to propose and develop initial creative solutions. Once I had consulted with my mentor and defined an initial scope, I then drafted up wireframes for the website in both desktop and mobile versions as well as a moodboard for potential elements and characteristics of the site. I have compiled my project development files in a folder [here](https://github.com/jerhabor/tutorlink/tree/master/assets/project-development).

### 1.2. Structure and Skeleton
My systematic approach was to create an invisible loop between these two phases of UX design, for reassurance that my deliverables would be an optimal fit for the target audience. I made sure that my wireframes were at least a good representation of how I wish to present information and how well users will be able to interact. 

I used Balsamiq Wireframes to construct my mockups. However, there were limited features on this software to illustrate what I intended to present (e.g. colours, animation etc). These extra features were noted down and I decided to progress with building the outline/template of the website by commenting out section headings in my GitPod workspace.


## 2. Features
<!-- In this section, you should go over the different parts of your project, and describe each in a sentence or so. -->

TutorLink comprises of four pages, namely: 
* [Home](https://jerhabor.github.io/tutorlink/index.html) 
* [Tutors](https://jerhabor.github.io/tutorlink/tutors.html) 
* [Subjects](https://jerhabor.github.io/tutorlink/subjects.html)
* [Contact](https://jerhabor.github.io/tutorlink/contact.html)

### 2.1. General Features

#### 2.1.1. Navigation bar  
The passion red colour theme with a contrasting white font, gives a warm welcoming feel to the site as users visit. A good first impression always counts. The active page is in bold and hover effects are applied to the non-active menu items. The **_Sign Up_** button back a gold background so that it stands out to users. I also used the following Bootstrap class to make the header stick on scroll, to a length equivalent to the height of the viewing device's screen:
~~~
<nav class="sticky-top">
~~~

#### 2.1.2. Sign Up Modal Form  
This allows the primary target audience to easily sign up in one click. At first glance, this can be accessed by clicking the **_Sign Up_** button on the navigation bar. 
There are also **_Sign Up Now_** buttons on each page located in: 
    * *Footer*
    * *Jumbotron* on Home pages
    * *Top Subjects* collapsible section on Subjects pages
    * *Book A Tutor* section on Contact page. 

#### 2.1.3. Header  
The [Tutors](https://jerhabor.github.io/tutorlink/tutors.html), [Subjects](https://jerhabor.github.io/tutorlink/subjects.html) and [Contact](https://jerhabor.github.io/tutorlink/contact.html) pages have background photo with a heading to indicate what the page offers users. The [Home](https://jerhabor.github.io/tutorlink/index.html) page however uses a carousel as I wanted to immediately communicate to users what the site offers without them having to click anything or anywhere.

#### 2.1.4. Background  
I decided to use a plain white background which is a nice contrast to the deep passion red navigation bar and footer. This is therefore visually appealing and allows users to read information clearly as the font colour used were predominantly dark.

#### 2.1.5. Fonts Used  
I chose _Montserrat_ as the main font because the wide letter-spacing ensures clarity of textual information to all viewers. _Roboto_ was used in two areas of the site: 
    1. The subjects taught by each tutor - in order to disrupt the initial monotonous aura that the page gave off. 
    2. The italicised text of the Testimonials section - as Roboto was easier on the eye according to users.

#### 2.1.6. Testimonials  
Located before the footer, this section also uses a carousel so that users can read multiple reviews in a short space of time without having to click elsewhere on the site. This meets the following user story:
    > As a tutor, I would love to see testimonials from people who have used been taught by us as this will help me in promoting it to other people.

    I created my bespoke circular bottom indictors by:
    ~~~ 
    #reviews-slides li {
    width: 10px;
    height: 10px;
    border-radius: 100%;
    background-color: #000;
    }
    ~~~

#### 2.1.7. Navigation Button "Back-To-Top"  
Even though the majority of today's users prefer to scroll, I created this button for easy access to the top of the page. I believe this would be useful for the older generation who may be more familiar with just clicking links to get them somewhere.

#### 2.1.8. Footer  
To create consistency across the site, I decided to take the advice of Code Institute mentor and past graduates and go with a "less is more" approach. This section only contains the social links and the **_Sign Up Now_** button that will load a modal for the user to fill in.

### 2.2. Specific Features in Home

#### 2.2.1. Carousel Header  
I used three background images as carousel items with captions that summarise the type of tuition/tutors that TutorLink provides. The height is 80% of the screen which gives sufficient.

#### 2.2.2. Tutorlink Introduction  
I decide to keep this concise so that it's clear straight away what Tutorlink does. This section sits below the carousel to give more information about the company.

#### 2.2.3. Mission Statements  
The use of icons gives more interaction so that the visual communication is not bland with just words.

#### 2.2.4. Selling Point  
In order to captivate users, it is advised to use more than one means of communication. Up until this point, I have used text and images. So I decided to incorporate a youtube video in an iframe which provides both video and audio; this is more appealing to users of today.

#### 2.2.5. Statistics  
The aim of this section is to convince users by demonstrating genuine results. I have therefore provided "Statistics" and "Selling-Point" sections as different means of reassuring users as per user story:
> As a parent of an 11+ student, I want your site to convince and reassure me in numerous ways why I should sign up.
    
#### 2.2.6. Jumbotron  
This section reminds the user to sign up. I decided to add animation effects to make it stand out so that in the event of scrolling, users can see it easily. I need it to stand out after stating my selling points and success rates.

#### 2.2.7. Two-column Site Navigation Section  
This section was styled with alternating pictures as both the images and the text complement each other in terms of the information that they display.

### 2.3. Specific Features in Tutors

#### 2.3.1. Qualifications  
List of achievements that the tutors have which demonstrate experience and ability to deliver well and in good manner. This meets the following user story:
> As a parent of an 11+ student, I want your site to convince and reassure me in numerous ways why I should sign up.

#### 2.3.2. Mini-Profiles  
For further user interaction with the page content - I used a Sepia filter on the profile images. They turn to their original colour when a mouse hovers over them in desktop mode or when the user taps them in mobile/tablet mode.
> As an A-Level student, I would like to see the full list of tutors so that I can familiarise myself with my chosen tutor's background beforehand.

### 2.4. Specific Features in Subjects

#### 2.4.1. Top Subjects  
By displaying to the users what the top subjects are this creates a sense of urgency for them to make a decision. The top subjects are already listed on the Home page in the "Two-column site navigation" section but are also advertised in this Subjects section. Seeing as Maths is a popular subject, this feature aims to speed up users decision-making time; especially for those who are looking for maths tutors. This therefore meets the following user stories: 
> As a GCSE student, I would like the website to be easy to navigate so that I can see what it offers as quickly as possible.

> As a parent of both KS2 and 11+ students, I want to be able to sign up easily so that once I decide to do so, it is quickly over and done with.

#### 2.4.2. "What We Offer" Section  
This feature gives the user clear information on the pricing and method of teaching; both of which play a huge part in their decision. 
> As a GCSE student, I would like the website to be easy to navigate so that I can see what it offers as quickly as possible.

> As a parent of both KS2 and 11+ students, I want to be able to sign up easily so that once I decide to do so, it is quickly over and done with.

> As an A-Level student, there should be the option to choose between face-to-face and virtual tutoring.

#### 2.4.3. Navigation to Subject Groups  
Due to the amount on content on this page, when clicked, this feature allows users to go straight to the subject they are interested in to save scrolling effort.

#### 2.4.4. Subjects  
The logos for some of the subjects namely maths and sciences were obtained from [Exam Paper Plus](https://exampapersplus.co.uk/). I created logos for Business Studies, Economics, Computer Science and Languages using inspiration from this site. The content makes it clear to the user what the subject is about. The subjects are also linked to revision guides so that they can purchase those quickly too. This meets the following user story:
> As a GCSE student, Link subjects to any recommended revision material so that students can obtain them prior to the first session.

### 2.5. Specific Features in Contact

#### 2.5.1. Contact Introduction  
Simple layout stating administration opening times and expected response times. Clear information to meet the following user story:
>  As a parent of both KS2 and 11+ students, I want to be able to sign up easily so that once I decide to do so, it is quickly over and done with.

#### 2.5.2. Contact Body  
I have given the options for different user types as defined in 1. User Experience (UX). Allows them to make their choice and meet their intended goal on visiting the page.

<!-- - Feature 1 - allows users X to achieve Y, by having them fill out Z
- ... -->

<!-- For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional. -->

<!-- In addition, you may also use this section to discuss plans for additional features to be implemented in the future: -->

### 2.6. Features Left to Implement
These features were disregarded in the scope for this version of the site. The main reason being that they are currently not a necessity in order to fulfill the user requirements. However to grow the brand, the following features can improve user-experience and increase marketability:

* Incorporate [Calendly](https://calendly.com/pages/integrations/embed) so that users can book sessions online without awaiting confirmation from tutors (inspired by Code Institute's Mentor's Calendar).
* Ability to book your own tutor.
    * This feature will only be considered and designed when the number of tutors per subject are significant enough for selections to be made.
* Provide daily/weekly tips on how to cope under the pressure of exams and to study effectively with recommended revision techniques.
* Selling of TutorLink-branded stationery and guides/books.
* Access to exam-style questions created by TutorLink tutors.
* Members/Students portal and forums so that users can keep track of sessions and engage with other TutorLink users.

## 3. Technologies Used

<!-- In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used. -->

- [Git](https://git-scm.com/) - TutorLink uses Git as a version control system during its development.
- [GitPod](https://www.gitpod.io/) - This is an online Integrated Development Environment (IDE) used to build TutorLink.
- [HTML5](https://en.wikipedia.org/wiki/HTML5) - HTML stands for Hypertext Markup Language and it is the backbone of TutorLink. The latest version - HTML5 - was used to structure, add and format the site content.
- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets) - CSS stands for Cascading Style Sheets. The latest version - CSS3 - was used to style all HTML content of TutorLink.
- [Bootstrap](https://getbootstrap.com/) - TutorLink uses Bootstrap's grid system to layout site content in a structured manner. This framework also provides some assistance to styling.
- [Google Fonts](https://fonts.google.com/) - This font library offers a huge variety of font styles for selection, to help in the mood design of TutorLink.
- [Font Awesome](https://fontawesome.com/) - TutorLink uses this icon library with its great selection of icons, to add to the visual aesthetics of the site content.
- [JQuery](https://jquery.com/) - TutorLink uses JQuery for effects, animations and the modal form. My mentor also recommended including HTML DOM Manipulation to produce a feedback box after a user presses Submit on the Sign Up Modal.

<!-- - [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation. -->


## 4. Testing

### 4.1. Testing Features
#### 4.1.1. Navigation bar  
- For screen sizes with widths smaller than 840px, a hamburger icon appears on the right.
- The hamburger icon toggles the collapsible element with the menu items when clicked.
- On mouse `hover` over each of the menu items (apart from the **Sign Up** button), they turn to bold for as long as the cursor stays on it.
- On mouse `hover` over the **Sign Up** button, the button scales up in size by 10%, the font colour turns white and the `background-color` turns grey due to Bootstrap's `class="btn btn-outline-secondary"`. The style.css sets the `transition` to 0.5s for smooth `hover` on and off:
    ~~~
    #navbarNav li button:hover {
    font-family: 'Montserrat', sans-serif;
    color: #fff;
    background-color: #808080;
    border-color: #000;
    transition: 0.5s;
    -webkit-transition: 0.5s;
    -moz-transition: 0.5s;
    -ms-transition: 0.5s;
    transform: scale(1.1);
    -webkit-transform: scale(1.1);
    -moz-transform: scale(1.1);
    -ms-transform: scale(1.1);
    }   
    ~~~
- Each link takes the user to the required page.
- The TutorLink logo on the top left when clicked, takes the user back to the home page.
- The Navigation bar is sticky for the length of the device's screen height.
- All navigation items function as intended.

#### 4.1.2. Sign Up to Book a Tutor 
The pop-up modal loads up correctly after clicking: 
- The **Sign Up** button on the navigation bar.
- The **Sign Up Now** button in the footer, Home page Jumbotron and Subjects page Top Subjects button.
- The **Sign Up Now** button under **Book a Tutor** on Contact page.

An error message is displayed if:
- The user tries to submit an empty form.
- [Not all input boxes have been filled in](assets/testing/user-stories/modal-error.JPG).
- An [invalid email address](assets/testing/user-stories/modal-error2.JPG) is given.

After submission, a display box appears with the message: _"Thank you, we have received your request. We will be in touch with you within 24 hours."_

#### 4.1.3. Apply to Become a Tutor  
On the Contact page underneath **Become a Tutor**, there are two parts to the form. 
- _"No file chosen"_ under **Upload CV** is replaced by the file name when the corresponding file has been uploaded.
The form cannot be submitted until: 
- A file has been chosen.
- A covering letter has been typed in the text box.

After submission, the same display box as in [4.1.2.](####412-sign-up-to-book-a-tutor) appears with the message: _"Thank you, we have received your request. We will be in touch with you within 24 hours."_

#### 4.1.4. Access TutorLink's Social Links  
- Social Links are located in the footer.
- On hover, the icon's `color` and `background-color` switch colours.
- For educational purposes, the socials icons are linked to the corresponding home pages (e.g. facebook icon loads facebook page when clicked).
- All links open up in a new tab after including the attribute `target="_blank"` in the anchor tags.

#### 4.1.5. "Why Do You Need A Tutor" YouTube Video  
- The iframe is responsive and displays accordingly on all screen sizes.
- The embedded video does not play automatically but allows the user to control the play button.
- All YouTube features are now enabled for the user to control.
- The user can click the video title to be directed to the YouTube video link in a new tab.

#### 4.1.6. Testimonials
- This section is responsive and displays accordingly on all screen sizes.
- The larger the screen size, the more whitespace to the left and right of the section. 
- For a larger screen size, this is to help the user read the text more easily rather than having to pan across the width.
- When the cursor hovers over the carousel, it stops moving automatically.

#### 4.1.7. View Recommended Revision Material
- When the cursor hovers over each subject, a black border appears over the item to confirm to the user of their selection.
- All links open up in a new tab after including the attribute `target="_blank"` in the anchor tags.  


### 4.2. Achievement of User Stories

**User 1:**
> As a GCSE student, I would like the website to be easy to navigate so that I can see what it offers as quickly as possible.

Features: [2.1.1](####211-navigation-bar), [2.2.7](####227-two--column-site-navigation-section)
- Navigation bar: 
    - [`min-width: 840px`](assets/testing/user-stories/navbar-desktop.JPG)
    - [`max-width: 839px`](assets/testing/user-stories/navbar-mobile.jpg)
    - [`max-width: 839px`](assets/testing/user-stories/navbar-mobile-open.jpg) (toggle open)
- [Home page two-column section](assets/testing/user-stories/two-column-section-home.jpg)

> As a tutor, I would love to see testimonials from people who have used been taught by us as this will help me in promoting it to other people.

Feature: [2.1.6](####-216-testimonials)
- [`min-width: 992px`](assets/testing/user-stories/testimonials-laptop.JPG)
- [`min-width: 768px and max-width: 991px`](/assets/testing/user-stories/testimonials-ipad.JPG)
- [`max-width: 767px`](assets/testing/user-stories/testimonials-mobile.JPG)

> As a parent of both KS2 and 11+ students, I want to be able to sign up easily so that once I decide to do so, it is quickly over and done with.

Features: 2.1.1, 2.1.8, 2.2.6, 2.4.1, 2.5.2
Sign up buttons are located in several places on the site for ease:
- [Navigation bar](assets/testing/user-stories/navbar-desktop.JPG)
- [Jumbotron](assets/testing/user-stories/jumbotron-mobile.JPG)
- [Footer](assets/testing/user-stories/footer-mobile.JPG)
- [Subjects Page](assets/testing/user-stories/top-subjects-open.JPG)
- [Contact Page](assets/testing/user-stories/contact-mobile.JPG)

> As an A-Level student, there should be the option to choose between face-to-face and virtual tutoring.

Feature: [2.4.2](assets/testing/user-stories/subjects-intro-chrome.jpg) 
(I did not add the option to the modal to allow discussion for flexibility in switching from face-to-face to online and vice versa. A great example is the COVI19 pandemic when only online sessions were permitted.)

> As a parent of an 11+ student, I want your site to convince and reassure me in numerous ways why I should sign up.

Features: [2.1.6](####-216-testimonials), [2.2.3](####223-mission-statements), [2.2.4](####224-selling-point), [2.2.5](####225-statistics)
The Home page offers different means of persuading the user to sign up namely:
- [Mission Statements](https://github.com/jerhabor/Milestone-Project-1/blob/df6eea83e939a84c8c8530a102aae0992e976182/assets/testing/user-stories/mission-statements.JPG)
- ["Why Do You Need A Tutor" iframe YouTube video](assets/testing/user-stories/selling-point.JPG)
- [Statistics](assets/testing/user-stories/statistics.JPG)
  
> As an A-Level student, I would like to see the full list of tutors so that I can familiarise myself with my chosen tutor's background beforehand.

Feature: [2.3.2](assets/testing/browsers/tutors-win10-chrome.png)

> As a GCSE student, Link subjects to any recommended revision material so that students can obtain them prior to the first session.

Feature: [2.4.4](####244-subjects)

- Can be accessed by clicking on **Subjects** in Navigation bar
- Click on the subject group to be directed to the required section of the page to choose subject - alternatively the user can scroll straight to the subject.
- Click the card to open up a link in a new browser tab. Click [here](assets/testing/user-stories/recommended-revision-material.gif) for an illustration.

### 4.3. Code Validation
**HMTL Code Validation**  
All HTML documents namely [index.html](assets/testing/validation/home.JPG), [tutors.html](assets/testing/validation/tutors.JPG), [subjects.html](assets/testing/validation/subjects.JPG) and [contact.html](assets/testing/validation/contact.JPG) passed with no warning or errors using the [W3C HTML Validator](https://validator.w3.org/).

**CSS Code Validation**  
The stylesheet, [style.css](assets/testing/validation/css.JPG), passed with no errors using the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/validator).

### 4.4. Test on Different Browsers

Key: &#x2714; = Functions well

|      Browser      | Version |   Home   |   Tutors  | Subjects |  Contact |                         Notes                         |
|:-----------------:|:-------:|:--------:|:---------:|:--------:|:--------:|:-----------------------------------------------------:|
|       Chrome      |    80   | [&#x2714;](assets/testing/browsers/home-win10-chrome.png) |  [&#x2714;](assets/testing/browsers/tutors-win10-chrome.png) | [&#x2714;](assets/testing/browsers/subjects-win10-chrome.png) | [&#x2714;](assets/testing/browsers/home-win10-chrome.png) |                                                       |
|      Firefox      |    74   | [&#x2714;](assets/testing/browsers/home-win10-firefox.png) |  [&#x2714;](assets/testing/browsers/tutors-mac-os-firefox.png) | [&#x2714;](assets/testing/browsers/subjects-win10-firefox.png) | [&#x2714;](assets/testing/browsers/contact-mac-os-chrome.png) |                                                       |
|       Safari      |    13   | [&#x2714;](assets/testing/browsers/home-mac-os-safari.png) |  [&#x2714;](assets/testing/browsers/tutors-mac-os-safari.png) | [&#x2714;](assets/testing/browsers/subjects-mac-os-safari.png) | [&#x2714;](assets/testing/browsers/contact-mac-os-safari.png) |                                                       |
| Internet Explorer |    11   | [&#x2714;](assets/testing/browsers/home-win10-ie.png) | [&#x2714;](assets/testing/browsers/tutors-win10-ie.png)* | [&#x2714;](assets/testing/browsers/subjects-win10-ie.png) | [&#x2714;](assets/testing/browsers/contact-win10-ie.png) | *The css __filter__ property is not supported&#x00B9; |
|        Edge       |    79   | [&#x2714;](assets/testing/browsers/home-win10-edge.png) |  [&#x2714;](assets/testing/browsers/tutors-win10-edge.png) | [&#x2714;](assets/testing/browsers/subjects-win10-edge.png) | [&#x2714;](assets/testing/browsers/contact-win10-edge.png) |                                                       |
|       Opera       |    67   | [&#x2714;](assets/testing/browsers/home-mac-os-opera.png) |  [&#x2714;](assets/testing/browsers/tutors-win10-opera.png) | [&#x2714;](assets/testing/browsers/subjects-win10-opera.png) | [&#x2714;](assets/testing/browsers/contact-mac-os-opera.png) |                                                       |

&#x00B9; It must be noted that although all tutor profiles displayed in an Internet Explorer browser do not have a sepia filter, this does not change the user's purpose and intent of this page.

### 4.5. Test on Different Devices

Key: &#x2714; = Displays as intended

|          Device         | Viewport (Width x Height) |   Home   |  Tutors  | Subjects |  Contact |
|:-----------------------:|:-------------------------:|:--------:|:--------:|:--------:|:--------:|
|         Moto G4         |         360 x 640         | &#x2714; | &#x2714; | &#x2714; | &#x2714; |
|        Galaxy S5        |         360 x 640         | &#x2714; | &#x2714; | &#x2714; | &#x2714; |
|        Galaxy S7        |         360 x 640         | &#x2714; | &#x2714; | &#x2714; | &#x2714; |
|         Pixel 2         |         411 x 731         | &#x2714; | &#x2714; | &#x2714; | &#x2714; |
|        Pixel 2 XL       |         411 x 823         | &#x2714; | &#x2714; | &#x2714; | &#x2714; |
|       iPhone 5/SE       |         320 x 568         | &#x2714; | &#x2714; | &#x2714; | &#x2714; |
|       iPhone 6/7/8      |         375 x 667         | &#x2714; | &#x2714; | &#x2714; | &#x2714; |
|    iPhone 6/7/8  Plus   |         414 x 736         | &#x2714; | &#x2714; | &#x2714; | &#x2714; |
|         iPhone X        |         375 x 812         | &#x2714; | &#x2714; | &#x2714; | &#x2714; |
|           iPad          |         768 x 1024        | &#x2714; | &#x2714; | &#x2714; | &#x2714; |
|         iPad Pro        |        1024 x 1366        | &#x2714; | &#x2714; | &#x2714; | &#x2714; |
| Sony Bravia  Television |   55-inch diagonal (4K)   | &#x2714; | &#x2714; | &#x2714; | &#x2714; |

 For most of the project development, Chrome's DevTools were used. Upon completion, [BrowserStack](https://www.browserstack.com/) was used to test simulated user interaction with TutorLink on different devices. Screen recordings of these were made using [Apowersoft](https://www.apowersoft.com/free-online-screen-recorder?__c=1).

 ### 4.6. Bugs and Problems

All browsers, apart from Internet Explorer, displayed all aspects of the website as intended. 

Internet Explorer does not support filters with [evidence from caniuse.com](assets/testing/browsers/caniuse-filter.JPG). This implies an innovative approach to reduce the `brightness` of the page headers. 

Using the Home page carousel as an example, I had to alter `.carousel-caption` and assign a black `background-color` and opacity of 0.7. As `position: absolute;` this overlays the `.carousel-item` with `position: relative;`.
~~~
.carousel-item {
    width: 100%;
    max-height: 470px;
    overflow: hidden;
    position: relative;
}

.carousel-caption {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    -webkit-transform: translateY(-50%);
    -moz-transform: translateY(-50%);
    -ms-transform: translateY(-50%);
    background: rgba(0,0,0,0.7);
    left: 0%;
    width: 100%;
    height: 100%;
}
~~~


<!-- In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals. -->

<!-- Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them. -->

<!-- For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as: -->

<!-- 1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears. -->

<!-- In addition, you should mention in this section how your project looks and works on different browsers and screen sizes. -->

<!-- You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet. -->

<!-- If this section grows too long, you may want to split it off into a separate file and link to it from here. -->

## 5. Deployment

TutorLink is deployed to GitHub Pages using its master branch; the only branch used.

To deploy:
- Go to TutorLink [GitHub repository](https://github.com/jerhabor/tutorlink)
- Click on Settings (above the green _"Clone"_ button)
- Scroll down to **GitHub Pages**
- Under source, select the `master` branch
- The page will automatically refresh and the following will be seen:

<img src="assets/images/github-pages-deploy.JPG" alt=""/>

In the event of making changes to code externally (i.e. not in an IDE workspace such as GitPod), commit changes so that you can use `git pull` in the IDE.

When working in GitPod IDE, the process to push to the repository is as follows:
~~~
$ git status
$ git add (insert file name) OR $ git add .
$ git commit -m "(mention here why changes were made to this version)"
$ git push
~~~

<!-- This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku). -->

<!-- In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch? -->

<!-- In addition, if it is not obvious, you should also describe how to run your code locally. -->


## 6. Credits

### 6.1. Content
<!-- - The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z) -->
- My mentor, Caleb, provided me with a short HTML DOM manipulation as mentioned in section 3. The following code is found on line 57 in index.html, tutors.html and subjects.html as well as line 56 in contact.html: 
    ~~~
    onsubmit="alert('Thank you, we have received your request. We will be in touch with you within 24 hours.'); return false;"
    ~~~ 

- The following Media Query for **Navbar** found in lines 193 - 209 of style.css was sourced from [Stack Overflow](https://stackoverflow.com/questions/19827605/change-bootstrap-navbar-collapse-breakpoint-without-using-less):
    ~~~
    .navbar .navbar-header {
        flex-wrap: nowrap;
    }
    .navbar-expand-custom .navbar-nav {
        flex-direction: row;
    }

    .navbar-expand-custom .navbar-nav .nav-link {
        padding-right: 0.5rem;
        padding-left: 0.5rem;
    }
    .navbar-expand-custom .navbar-collapse {
        display: flex!important;
    }
    .navbar-expand-custom .navbar-toggler {
        display: none;
    }
    ~~~

### 6.2. Media
<!-- - The photos used in this site were obtained from ... -->
The photos used in this site are for educational purposes only and were obtained from:
* [Pexels](https://www.pexels.com/)
* [Google Images](https://www.google.com/imghp?hl=en)

### 6.3. Acknowledgements

<!-- - I received inspiration for this project from X -->
- My mother Mercy - for coming up with the name TutorLink.
- My mentor [Caleb](https://github.com/calebmbakwe) - for his guidance from conception to deployment.
- My family - for testing the site and providing constructive feedback.
- My Slack community - for the encouragement and general guidance from day one.
