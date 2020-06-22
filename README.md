# User Centric Frontend Development Project - Tutorlink

<!-- One or two paragraphs providing an overview of your project. -->

<!-- Essentially, this part is your sales pitch. -->
Welcome to [TutorLink](https://jerhabor.github.io/tutorlink/index.html)!

This website was created for parents & guardians who are in search of a private tutor for their children, as well as students themselves who are well-versed in using technological devices to access and use this site to book a tutor. The site also promotes an opportunity for aspiring tutors to join and share their wealth of knowledge to those in need. 

Following the news of the COVID-19 pandemic, there has since been a strain on family members having to perform home-schooling duties for those still in school. TutorLink offers users the opportunity to alleviate this pressure by hiring a qualified tutor to guide their students to academic excellence. The key benefit of this, is that all sessions can take place in the comfort of their own homes. 

Currently, online sessions are strongly recommended for safety reasons. It is without a doubt a growing market thanks to the advancement of technology to this present day. The aim of the site is to connect students to tutors. The online sessions will take place via the video conferencing application, "Zoom". The times and dates of the sessions can be settled in advance by email or text between both the student and the tutor.  This provides flexibility for both parties as lives adjust to the new normal. 

## 1. User Experience (UX)
<!-- Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things. -->
The idea of creating a platform to encourage further learning has always been one of my goals. In this case, this site was built to enable the experienced to share and the students to learn at greater depths than they normally would in school. This means that tutors will be able to provide mentorship to students and coach them through their academic journey. To illustrate the connection that this site brings between tutors and students, the name "TutorLink" was therefore birthed (credits to my mother). 

The primary target audience are students and parents/guardians who will sign up on behalf of their children.

The secondary target audience are aspiring tutors.

<!-- In particular, as part of this section we recommend that you provide a list of User Stories, with the following general structure:
- As a user type, I want to perform an action, so that I can achieve a goal. -->

### 1.1 User Stories
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

### 1.2 Structure & Skeleton
My systematic approach was to an invisible loop between these two phases of UX design, for reassurance that my deliverables would be an optimal fit for the target audience. I made sure that my wireframes were at least a good representation of how I wish to present information and how well users will be able to interact. 

I used Balsamiq Wireframes to construct my mockups. However, there were limited features on this software to illustrate what I intended to present (e.g. colours, animation etc). These extra features were noted down and I decided to progress with building the outline/template of the website by commenting out section headings in my GitPod workspace.


## 2. Features
<!-- In this section, you should go over the different parts of your project, and describe each in a sentence or so. -->

TutorLink comprises of four pages, namely: 
* [Home](https://jerhabor.github.io/tutorlink/index.html) 
* [Tutors](https://jerhabor.github.io/tutorlink/tutors.html) 
* [Subjects](https://jerhabor.github.io/tutorlink/subjects.html)
* [Contact](https://jerhabor.github.io/tutorlink/contact.html)

### 2.1 General Features
* **Navigation bar** - The passion red colour theme with a contrasting white font, gives a warm welcoming feel to the site as users visit. A good first impression always counts. The active page is in bold and hover effects are applied to the non-active menu items. The **_Sign Up_** button back a gold background so that it stands out to users. I also used the following Bootstrap class to make the header stick on scroll, to a length equivalent to the height of the viewing device's screen:
~~~
<nav class="sticky-top">
~~~

* **Sign Up Modal Form** - This allows the primary target audience to easily sign up in one click. At first glance, this can be accessed by clicking the **_Sign Up_** button on the navigation bar. There are also **_Sign Up Now_** buttons located on: 
    - Each page's _Footer_
    - The Home page _Jumbotron_
    - The _Top Subjects_ collapsible section on the Subjects page 
    - The contact page's _Book A Tutor_ section.

* **Header** - The [Tutors](https://jerhabor.github.io/tutorlink/tutors.html), [Subjects](https://jerhabor.github.io/tutorlink/subjects.html) and [Contact](https://jerhabor.github.io/tutorlink/contact.html) pages have background photo with a heading to indicate what the page offers users. The [Home](https://jerhabor.github.io/tutorlink/index.html) page however uses a carousel as I wanted to immediately communicate to users what the site offers without them having to click anything or anywhere.

* **Background** - I decided to use a plain white background which is a nice contrast to the deep passion red navigation bar and footer. This is therefore visually appealing and allows users to read information clearly as the font colour used were predominantly dark.

* **Fonts Used** - I chose _Montserrat_ as the main font because the wide letter-spacing ensures clarity of textual information to all viewers. _Roboto_ was used in two areas of the site: 
    1. The subjects taught by each tutor - in order to disrupt the initial monotonous aura that the page gave off. 
    2. The italicised text of the Testimonials section - as Roboto was easier on the eye according to users.

* **Testimonials** - Located before the footer, this section also uses a carousel so that users can read multiple reviews in a short space of time without having to click elsewhere on the site. I created my bespoke circular bottom indictors by:
~~~ 
#reviews-slides li {
    width: 10px;
    height: 10px;
    border-radius: 100%;
    background-color: #000;
}
~~~

* **Navigation Button "Back-To-Top"** - Even though the majority of today's users prefer to scroll, I created this button for easy access to the top of the page. I believe this would be useful for the older generation who may be more familiar with just clicking links to get them somewhere.

* **Footer** - To create consistency across the site, I decided to take the advice of Code Institute mentor and past graduates and go with a "less is more" approach. This section only contains the social links and the **_Sign Up Now_** button that will load a modal for the user to fill in.

### 2.2 Specific Features in [Home](https://jerhabor.github.io/tutorlink/index.html)
* **Carousel Header** - I used three background images as carousel items with captions that summarise the type of tuition/tutors that TutorLink provides. The height is 80% of the screen which gives sufficient.

* **Tutorlink Introduction**
* **Mission Statements**
* **Selling Point** - In order to captivate users, it is advised to use more than one means of communication. Up until this point, I have used text and images. So I decided to incorporate a youtube video in an iframe which provides both video and audio; this is more appealing to users of today.
* **Statistics** - 
* **Jumbotron** - This section reminds the user to sign up. I decided to add animation effects to make it stand out so that in the event of scrolling, users can see it easily. I need it to stand out after stating my selling points and success rates.
* **Two-column Site Navigation Section**

### 2.3 Specific Features in [Tutors](https://jerhabor.github.io/tutorlink/tutors.html)
* **Qualifications**
* **Mini-Profiles**

### 2.4 Specific Features in [Subjects](https://jerhabor.github.io/tutorlink/subjects.html)
* **Top Subjects**
* **"What We Offer" Section**
* **Navigation to Subject Groups**
* **Subjects**

### 2.5 Specific Features in [Contact](https://jerhabor.github.io/tutorlink/contact.html)
* **"Contact" Introduction**
* **"Contact" Body**

<!-- - Feature 1 - allows users X to achieve Y, by having them fill out Z
- ... -->

<!-- For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional. -->

<!-- In addition, you may also use this section to discuss plans for additional features to be implemented in the future: -->

### 2.6 Features Left to Implement
These features were disregarded in the scope for this version of the site. The main reason being that they are currently not a necessity in order to fulfill the user requirements. However to grow the brand, the following features can improve user-experience and increase marketability:

* Incorporate [Calendly](https://calendly.com/pages/integrations/embed) so that users can book sessions online without awaiting confirmation from tutors (inspired by Code Institute's Mentor's Calendar).
* Provide tips on how to cope under the pressure of exams and to study effectively with recommended revision techniques.
* Selling of TutorLink-branded stationery and guides/books.
* Access to exam-style questions created by TutorLink tutors
* Members/Students portal and forums so that users can keep track of sessions and engage with other TutorLink users.

## Technologies Used

<!-- In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used. -->

<!-- - [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation. -->


## Testing

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

## Deployment

<!-- This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku). -->

<!-- In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch? -->

<!-- In addition, if it is not obvious, you should also describe how to run your code locally. -->


## Credits

### Content
<!-- - The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z) -->

### Media
<!-- - The photos used in this site were obtained from ... -->

### Acknowledgements

<!-- - I received inspiration for this project from X -->

