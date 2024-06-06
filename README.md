# CyberSafe Haven
## By The Hackstreet Boys
## Project Brief 3: A Guide To Staying Safe Online

# Table of Contents
1. [Introduction](#introduction)
2. [Instructions and Features](#instructions)
3. [Development Considerations](#development)
4. [Testing](#testing)
5. [Team](#team)
6. [Future Ideas](#future)
7. [Project Deployment](#deployment)
8. [Technical Facts](#technical-facts)
9. [Repository and Project Board](#repository)
10. [Credits](#credits)

<a id="introduction"></a>
## Introduction

Welcome to CyberSafe Haven, a website designed to introduce key concepts of staying safe online. The aim of this project is to clearly and concisely illustrate the best approaches and practices in dealing with important computer security issues. In addition to this, there are sections about security online as well as content on cyberbullying and general harassment. Finally, there are links to further information for curious readers in the "More Information" page along with final credits for external content used.

This website was created during Hackathon 1 of the "16-Week High-Performance Full Stack Skills Bootcamp" which ranged from 06/04/2024 to 06/06/2024 (12pm). Permission was given by the Bootcamp lead to start coding on the day before and some minor ideas were explored during this time. Planning and preparation for the Hackathon was conducted over the weekend before (2024/06/01 - 2024/06/02). The requirements of this Hackathon are found [here](/assets/docs/hackathon-1-requirements.pdf).

<a id="instructions"></a>
## Instructions

CyberSafe Haven is designed to be intuitive to use and to present information in a clear and easy to read way. A navigation bar is placed at the top to help the user to move around the site and a footer can be found at the bottom linking to (virtual) social media pages.

# General style

The site is designed to use high-contrast colours and a neat, professional design. The first page has an attractive styled image with all other pages sporting a black on white style for the main sections. The purpose of this choice is to make it easy for the user to feel engaged by the initial impression and then to find the main content areas light and easy to read.

Desktop view of home page:

![Full cover page in desktop view](/assets/images/docs/cover-desktop.png "Full cover page in desktop view")

Mobile view of home page: 

![Full cover page in mobile view](/assets/images/docs/cover-mobile-scaled.png "Full cover page in mobile view")

Desktop view of device security only (to avoid screenshot overload):

![Full device security page in desktop view](/assets/images/docs/device-security.png "Full device security page in desktop view")

### Header & Navigation bar

The header contains a brand piece of text that appears on all pages aligned to the left. The right-sided navigation bar is designed to be responsive at all screen sizes. The links used as descriptive and necessarily long-winded for user-friendliness. Given the length of the topic names, a link called "Menu" is always present for the user to select hidden options. This is shown here in mobile view.

![Navigation bar in mobile view](/assets/images/docs/navbar-mobile.png "Navigation bar in mobile view")

Depending on the size of the screen, some links may be displayed directly on the navigation bar. This can be seen in both laptop and desktop mode below.

![Navigation bar in laptop view](/assets/images/docs/navbar-laptop.png "Navigation bar in laptop view")

![Navigation bar in desktop view](/assets/images/docs/navbar-desktop.png "Navigation bar in desktop view")

### Footer

The footer contains a trademark piece of text and a series of icons that link to (virtual) social media sites to accommodate users who may want to visit the organisation's other online platforms. It is designed to be basic and simplistic and carry the kind of regular content you would expect to see on a modern-day website. The colour scheme matches the nav bar to ensure consistency.

![Footer bar in desktop view](/assets/images/docs/footer-screenshot.png "Footer bar in desktop view")

### Content pages

The user is able to access content on a variety of online safety topics. These are covered by this website:-

- Password security
- Email & social media
- Device security
- Cyberbullying and harassment

Some other concepts are covered by links to other sites in the Menu -> More Information item.

#### Password security

The first password security page has a clean professional style with the content styled clearly, making it easy to read. Images are then used to break up the content, aiding the user in not becoming overwhelmed. It is important to note that the header element and navigation bar are always visible and are fixed at the top of the screen for ease of use.

![Top of password security page](/assets/images/docs/password-security-screenshot.png "Top of password security page")

#### Email & Social Media Security Guide

The second page focusing on email and social media has a slightly different design, with a larger image at the centre before the main content. This design was put in place to separate the page in nature from the others, keeping the user engaged while still keeping to the consistent colour and content structure as the rest of the site.

![Top of email and social media security guide](/assets/images/docs/email-social-page-screenshot.png "Top of email and social media security guide")

#### Other content pages

The rest of the content pages follow a similar ideology. They are different enough to stand out and yet not distract from the general feel of the site. This allows the user to engage in learning the actual content in a refreshing and yet familiar manner.

### More information

This section allows the user to access some external links relating to other forms of cyber security issues that are not covered on this website.

![More info page](/assets/images/docs/moreinfo.png "More info page")

<a id="development"></a>
## Development Considerations

Upon selection of our chosen topic, we began a process of consideration into how the project might be designed and developed. An initial stage was considering what categories and content a sequence of pages might contain. After collecting some summarised information from ChatGPT, we collected an exhaustive amount of information before sorting out initial categories and information. The data we collected and sorted through is contained in [initial-categorisation.pdf](/assets/docs/initial-categorisation.pdf)

A project board was set up during GitHub Projects and populated with tasks. As the project progressed, these items were moved from "Todo" to "In Progress" and then to "Completed". A full Agile methodology was not required during this Hackathon and thus the project board was only used in a basic sense for management.

Wireframe ideas for the design were created to give a sense of the kind of interface we were going for. It was made clear during preparation for this Hackathon (being the first one) that most of the focus would be on the coding for the challenge and thus only limited attempts were made on wireframing concepts. A design was drawn up on mobile dimensions and then expanded to show tablet and laptop/desktop layouts. An example illustration of a themed website in colour was then created using this approach. Ultimately, the styled design was not retained although the wireframed black and white designs ended up laying the groundwork.

Some of the abstract wireframe designs are shown below:-

Mobile view without menu open:

![Wireframe smartphone page barebones](/assets/images/docs/wireframe-smartphone-barebones.png "Wireframe smartphone page barebones")

Mobile view with menu open:

![Wireframe smartphone page barebones with menu open](/assets/images/docs/wireframe-smartphone-barebones-menu.png "Wireframe smartphone page barebones with menu open")

Tablet view:

![Wireframe tablet page barebones](/assets/images/docs/wireframe-tablet-barebones.png "Wireframe tablet page barebones")

Desktop view:

![Wireframe laptop page barebones](/assets/images/docs/wireframe-laptop-barebones.png "Wireframe laptop page barebones")

The initial idea for styling was to use a complimentary colour palette like the following. However, after building a more barebones colour system for the initial construction, it became clear that it worked well in more simple colours. 

![Wireframe smartphone page styled](/assets/images/docs/wireframe-smartphone-styled.png "Wireframe smartphone page styled")

An index.html page was created initially with focus on this as a template page. For this reason, the priority was on creating a header, navbar and footer which was largely completed. Later on, it became clear that operational time limits meant that changes were required to the scope. At this point, a separate unlinked template.html file was created and used as a base for other pages allowing content to be easily added to index.html. From here, the site was expanded to other pages and populated with first content and then designed to a consistent, easy-to-read style.

<a id="testing"></a>
## Testing

The web site was tested in quite a few ways before completing. These are as follows:-

- Page responsiveness tested on all pages at mobile, tablet, laptop and desktop sizes
- Making sure all images load.
- Validating every HTML and CSS page on the site with a W3C validator. All pages are error free although some have warnings that there wasn't time to solve.
- Checking all external sites open in a new tab
- Checking all links work

<a id="future"></a>
## Future Ideas

- Fix the nav bar to show more items in desktop view, the current structure was designed for more pages.
- Add more categories and content to the site.
- Work on spacing and content separation a bit more. There are areas where it isn't perfect.

<a id="deployment"></a>
## Project Deployment

The deployed website can be found [here](https://cyberarchitect777.github.io/hackathon1-hackstreetboys-staying-safe-online/)

<a id="team"></a>
## Team

The team worked cooperatively to take the project from design to final implementation and testing.

- Barrie Millar (Team leader) (https://github.com/CyberArchitect777)
- Jabbeer Jeerooburkhan - (https://github.com/Jab90)
- Lewis Freeman - (https://github.com/LewF-Dev)

<a id="technical"></a>
## Technical facts

### Technologies used:

- HTML
- CSS
- Bootstrap
- Font Awesome

### Tools used:

- Slack (For communications)
- Balsamiq (For wireframing)
- Google Documents (For content consideration)
- GitHub Projects (For project management)
- ChatGPT (For name generation and content categorisation/inspiration/code advice)

<a id="repository"></a>
## Repository and Project Board

- GitHub repository - https://github.com/CyberArchitect777/hackathon1-hackstreetboys-staying-safe-online
- GitHub project board - https://github.com/users/CyberArchitect777/projects/3/views/1
- GitHub deployed website - https://cyberarchitect777.github.io/hackathon1-hackstreetboys-staying-safe-online/

<a id="credits"></a>
## Credits

Lewis Freeman

- [Source for S.M.A.R.T information](https://www.hurstdrive.herts.sch.uk/e-safety/)
- [Source for Woman Ignoring Partner image](https://www.psychologs.com/why-do-people-sometimes-ignore-each-other/)
- [Source for emotional change image](https://www.hrvisionevent.com/content-hub/minimise-emotional-impact-change/man)
- [Source for living alone image](https://edition.cnn.com/2022/01/12/health/living-alone-men-inflammation-wellness/index.html)
- [Deleting social media image](https://www.unitestudents.com/the-common-room/health-and-wellbeing/i-deleted-social-media-heres-why-i-think-you-should-too)
- [cyberbullying.html - How to protect yourself section](https://www.undp.org/kazakhstan/how-protect-yourself-cyberbullying)
- [Credit for unhappy-phone-user image](https://abcnews.go.com/Technology/science-doomscrolling/story?id=74402415)
- [For index page background image](https://www.freepik.com/premium-ai-image/person-typing-laptop-dark-room_44329314.htm)
- YouTube for videos embedded onto site.

Barrie Millar

- Photo by <a href="https://unsplash.com/@brookecagle?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Brooke Cagle</a> on <a href="https://unsplash.com/photos/woman-sitting-on-brown-wooden-chair-while-using-silver-laptop-computer-in-room-WHWYBmtn3_0?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>
- Photo by <a href="https://unsplash.com/@dell?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Dell</a> on <a href="https://unsplash.com/photos/person-using-laptop-on-table-dpbXgTh0Lac?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>
- Photo by <a href="https://unsplash.com/@balazsketyi?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Balázs Kétyi</a> on <a href="https://unsplash.com/photos/black-smartphone-b9rPuUQ_YSs?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>
- Photo by <a href="https://unsplash.com/@danielkorpai?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Daniel Korpai</a> on <a href="https://unsplash.com/photos/space-gray-ipad-pro-A5Z9g4xP6Yw?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>
Photo by <a href="https://unsplash.com/@detpho?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Francesco</a> on <a href="https://unsplash.com/photos/a-close-up-of-a-cell-phone-on-a-red-surface-1bBCtUAUMFI?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>

Jabbeer Jeerooburkhan

- YouTube for videos embedded onto site.
- [Top tips for staying secure online](https://www.ncsc.gov.uk/collection/top-tips-for-staying-secure-online) - Images and content was mainly taken from this website
- [Shutterstock](https://www.shutterstock.com) for additional images