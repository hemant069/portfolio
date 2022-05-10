# My-Portfolio 

<p align="center">
<img src="https://raw.githubusercontent.com/PhantomScript/asset-container/b26b0ebaaa13bec7fac796ee0b8296676df6ee0b/developer-portfolio/website.svg" alt="" width="450px"/>
</p>

## Check out my portfolio! 💼 - https://anirudhjakhotia.netlify.app/

<br />

## Table of Contents :scroll:
- [Sections](#sections-bookmark)
- [Installation](#installation-arrow_down)
- [Getting Started](#getting-started-dart)
- [Folder Structure](#folder-structure-open_file_folder)
- [Usage](#usage-joystick)
- [Hosting](#hosting-globe_with_meridians)
- [Fonts and Images](#fonts-and-images-performing_arts)
- [APIs Used](#apis-used-world_map)
- [Packages Used](#packages-used-package)

<br /><br />


# Sections :bookmark:
- HOME
- ABOUT
- RESUME
    - EDUCATION
    - SKILLS
    - EXPERIENCE
    - PROJECTS 
    - Achievements <br />
- SERVICES 
    - TESTIMONIALS <br />
- BLOG
- CONTACTS 

<br /><br />

# Installation :arrow_down:
### You will need to download Git and Node to run this project

- [Git](https://git-scm.com/downloads)
- [Node](https://nodejs.org/en/download/)

## Also check [this](https://reactjs.org/docs/create-a-new-react-app.html) out if you are new to react.

#### Make sure you have the latest version of both Git and Node on your computer.

```
node --version
git --version
```

<br />

# Getting Started :dart:
### Fork or Clone the repo

#### To Fork the repo click on the fork button at the top right of the page. To get the code-base, open your terminal and perform the following commands shown below:
```
git clone https://github.com/anirudhjak06/My-Portfolio.git
cd My-Portfolio-main
```
### Install packages from the root directory
```
npm install
```
#### or
```
yarn install
```
### Start the development server
```
npm start
```
#### or
```
yarn start
```
<br />

# Folder Structure :open_file_folder:

```bash
├── LICENSE   
├── README.md        
├── package-lock.json
├── package.json     
├── public
│   ├── _redirects   
│   ├── favicon.ico  
│   ├── favicon.png
│   ├── favicon512.png
│   ├── index.html
│   ├── manifest.json
│   └── robots.txt
├── src
│   ├── App.css
│   ├── App.js
│   ├── assets
│   │   ├── fonts
│   │   │   └── Bestermind
│   │   │       └── BestermindRegular.ttf
│   │   ├── pdf
│   │   │   └── resume.pdf
│   │   └── svg
│   │       ├── about
│   │       ├── contacts
│   │       ├── education
│   │       ├── experience
│   │       ├── projects
│   │       ├── skills
│   │       ├── social
│   │       └── testimonials
│   ├── components
│   │   ├── About
│   │   │   ├── About.css
│   │   │   └── About.js
│   │   ├── Achievements
│   │   │   ├── Achievements.css
│   │   │   └── Achievements.js
│   │   │   └── AchievementCard.js
│   │   ├── BackToTop
│   │   │   ├── BackToTop.css
│   │   │   └── BackToTop.js
│   │   ├── Blog
│   │   │   ├── Blog.css
│   │   │   ├── Blog.js
│   │   │   └── SingleBlog
│   │   │       ├── SingleBlog.css
│   │   │       └── SingleBlog.js
│   │   ├── Contacts
│   │   │   ├── Contacts.css
│   │   │   └── Contacts.js
│   │   ├── Education
│   │   │   ├── Education.css
│   │   │   ├── Education.js
│   │   │   └── EducationCard.js
│   │   ├── Experience
│   │   │   ├── Experience.css
│   │   │   ├── Experience.js
│   │   │   └── ExperienceCard.js
│   │   ├── Footer
│   │   │   ├── Footer.css
│   │   │   └── Footer.js
│   │   ├── Landing
│   │   │   ├── Landing.css
│   │   │   └── Landing.js
│   │   ├── Navbar
│   │   │   ├── Navbar.css
│   │   │   └── Navbar.js
│   │   ├── Projects
│   │   │   ├── Projects.css
│   │   │   ├── Projects.js
│   │   │   └── SingleProject
│   │   │       ├── SingleProject.css
│   │   │       └── SingleProject.js
│   │   ├── Services
│   │   │   ├── Services.css
│   │   │   ├── Services.js
│   │   │   └── SingleService
│   │   │       ├── SingleService.css
│   │   │       └── SingleService.js
│   │   ├── Skills
│   │   │   ├── Skills.css
│   │   │   └── Skills.js
│   │   ├── Testimonials
│   │   │   ├── Testimonials.css
│   │   │   └── Testimonials.js
│   │   └── index.js
│   ├── contexts
│   │   └── ThemeContext.js
│   ├── data
│   │   ├── aboutData.js
│   │   ├── achievementData.js
│   │   ├── blogData.js
│   │   ├── contactsData.js
│   │   ├── educationData.js
│   │   ├── experienceData.js
│   │   ├── headerData.js
│   │   ├── projectsData.js
│   │   ├── servicesData.js
│   │   ├── skillsData.js
│   │   ├── socialsData.js
│   │   ├── testimonialsData.js
│   │   └── themeData.js
│   ├── index.css
│   ├── index.js
│   ├── pages
│   │   ├── Blog
│   │   │   ├── BlogPage.css
│   │   │   └── BlogPage.js
│   │   ├── Main
│   │   │   └── Main.js
│   │   ├── Project
│   │   │   ├── ProjectPage.css
│   │   │   └── ProjectPage.js
│   │   └── index.js
│   ├── reportWebVitals.js
│   ├── theme
│   │   ├── images.js
│   │   └── theme.js
│   └── utils
│       ├── ScrollToTop.js
│       └── skillsImage.js
└── yarn.lock
```
<br />

# Usage :joystick:
### Customize your details for each component in `src/data` [folder](https://github.com/hhhrrrttt222111/developer-portfolio/tree/master/src/data).

Eg:
```javascript
export const headerData = {
    name: '-- YOUR NAME --',
    title: '-- YOUR TITLE --',
    desciption:'-- DESCRIPTION --',
    image: '-- IMAGE --',
    resumePdf: ''
}

// You can also import image and PDF from assets as shown below

import resume from '../assets/pdf/resume.pdf'
import profileImg from '../assets/png/profileImg'

export const headerData = {
    name: '-- YOUR NAME --',
    title: '-- YOUR TITLE --',
    desciption:'-- DESCRIPTION --',
    image: profileImg,
    resumePdf: resume
}
```

#### Data for each component is divided into respective files.
>#### Set website theme in [`src/data/themeData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/themeData.js) and choose your favourite font from [`src/App.css`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/App.css)

> #### About You - [`src/data/aboutData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/aboutData.js)

> #### Education details - [`src/data/educationData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/educationData.js) 

> #### Enter your Projects - [`src/data/projectsData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/projectsData.js)

> #### Add your Skills - [`src/data/skillsData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/skillsData.js)

> #### Experience - [`src/data/experienceData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/experienceData.js)

> #### Achievements - [`src/data/achievementData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/achievementData.js)

> #### Services - [`src/data/servicesData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/servicesData.js)

> #### Testimonials - [`src/data/testimonialsData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/testimonialsData.js)

> #### Your Blogs and Articles - [`src/data/blogData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/blogData.js)

> #### Contact Details - [`src/data/contactsData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/contactsData.js)

> #### Social Media Profiles - [`src/data/contactsData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/socialsData.js)

```javascript
// EXAMPLE
export const educationData = [
    {
        id: 1,
        institution: '-- INSTITUTION NAME --',
        course: '-- COURSE NAME --',
        startYear: '2017',
        endYear: '2019'
    },
    //
]
```

### Instructions and format for each section can be found inside the data files.
<br />

## Setting Up Contacts form :envelope_with_arrow:
> ### Follow these [instructions](https://github.com/hhhrrrttt222111/developer-portfolio/wiki/Contacts) to connect contacts form with Google Sheet

<br />

# Hosting :globe_with_meridians:
## Netlify
| Site   | Docs  | Demo  |
| :-------------: |:-------------: |:-------------: |
| [Netlify](https://www.netlify.com/) | [3 ways to deploy React apps to Netlify](https://blog.logrocket.com/3-ways-to-deploy-react-apps-to-netlify/) | [Youtube](https://www.youtube.com/watch?v=sGBdp9r2GSg) |
## Firebase
| Site   | Docs  | Demo  |
| :-------------: |:-------------: |:-------------: |
| [Firebase](https://firebase.google.com/docs/hosting) | [Deploy a React App with Firebase](https://medium.com/swlh/how-to-deploy-a-react-app-with-firebase-hosting-98063c5bf425) | [Youtube](https://www.youtube.com/watch?v=1wZw7RvXPRU) |


## Heroku
| Site   | Docs  | Demo  |
| :-------------: |:-------------: |:-------------: |
| [Heroku](https://www.heroku.com/) | [Deploying React App on Heroku from GitHub](https://medium.com/make-it-heady/deploying-create-react-app-on-heroku-from-github-49447561f670) | [Youtube](https://www.youtube.com/watch?v=dn4mmfbletg) |

## Github Pages
| Site   | Docs  | Demo  |
| :-------------: |:-------------: |:-------------: |
| [GitHub Pages](https://pages.github.com/) | [Deploying React App on GitHub Pages from GitHub](https://create-react-app.dev/docs/deployment/#github-pages) | [Youtube](https://youtu.be/F8s4Ng-re0E) |

<br />

# Fonts and Images :performing_arts:

## Illustrations
- [Icons8](https://icons8.com/illustrations/styles)
- [SVG Porn](https://svgporn.com/)

## Icons
- [Material Icons](https://material-ui.com/components/material-icons/)
- [React Icons](https://react-icons.github.io/react-icons/)

## Fonts
- [Poppins](https://fonts.google.com/specimen/Poppins)
- [Montserrat](https://fonts.google.com/specimen/Montserrat)
- [Raleway](https://fonts.google.com/specimen/Raleway)
- [Big Shoulders Text](https://fonts.google.com/specimen/Big+Shoulders+Text)
- [Bestermind](https://www.dafont.com/bestermind.font)
- [Roboto](https://fonts.google.com/specimen/Roboto)

<br />

# APIs Used :world_map:
- [SheetDB](https://sheetdb.io/)


<br />


# Packages Used :package:

| Client Side Packages  |
| :-------------: |
| @material-ui/core  |
| @material-ui/icons  |
| axios |
| react-fast-marquee |
| react-helmet  |
| react-icons  |
| react-reveal |
| react-router-dom  |
| react-router-hash-link  |
| react-slick  |
| slick-carousel |
| validator |


<br />

# Created with ❤️ by Anirudh Jakhotia!

<img height="120" alt="Thanks for visiting!" width="100%" src="https://raw.githubusercontent.com/BrunnerLivio/brunnerlivio/master/images/marquee.svg" />
<br />