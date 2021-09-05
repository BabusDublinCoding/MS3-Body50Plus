# MS3-Body50+

**Body50+**

Backend Development Milestone Project - Code Institute.

The live website can be found []()


![All Devices Image](wireframes/sitealldevices.png)


**Overview**

As we age, every decade a man will lose ten pounds of muscle. They begin to shrink and lose mass. The number and size of muscle fibres also decrease. Handgrip strength drops, making it more difficult to do simple tasks like opening a jar. The heart muscle becomes less able to propel large quantities of blood quickly to the body. We tire more quickly and take longer to recover. The body's metabolic rate slows down, making it a lot easier to put on body fat. The mineral content of bones falls, so that bones become less dense and more fragile.

Body50+ gives users an opportunity to access information on resistance exercises that are relevant to person who is over 50 and who is looking to build and maintain muscle in order to create a strong healthy body as they age.

The website design is to be a simple and easy to use. It is primarily targeted towards an audience that has little experience of exercise or building muscle. It is free to use and publicly available. The user will need to sign up as a member in order to view and contribute to the pool of exercises.



**Features**


## User Experience (UX)

**New User**
- I would like to find out what the site is about
- I would like to see if the site is for me without registering
- I want to easily navigate through the site to find content
- I would like to easily register
- I want to have the ability to find their social media links 
- I would like to be able to add my exercises

**Existing User**
- I want to be able to sign in and out easily
- I would like to be able to delete my account
- I would like to be able to add/edit/delete comments to my own exercises
- I would like to be able to reset my password
- I want to have the ability to Create, Read, Update and Delete my exercises

**All Users**
- I would like to be able to contact Body50+
- I would like to be able to add/edit/delete exercise information
- I would like to be able to add/edit/delete my information

**Site Owner**
- I would like to present a clean, simple website free of ‘clutter’, which is visually appealing
- I would like easy navigation between pages
- I would like to get user feedback when I take actions on the site
- I would like to promote exercise to all, particularly the target audience 





 ## UX Design
 
**Strategy**

*User Needs* - User to access the site on mobile, tablet and then the desktop. The information is to be presented in a concise manner.

*Technical Aptitudes* - The main technologies used in the project will be HTML, CSS, Materialize, Python+Flask and MongoDB

*Business Vision* - The project is not a commercial venture but simply to inform and educate the user.


**Scope**

For the audience I want to present a fun and enjoyable app that is easy to understand and can be accessed on mobile devices, laptops and desktops. If they find the content useful they might tell their friends.

**Structure**


**Skeleton**

*[Wireframes](https://github.com/BabusDublinCoding/MS2-And-The-Award-Goes-To/tree/master/wireframes)*

- The wireframes were created using Balsamic, a popular wireframing tool, which Code Institute student can avail of as a fully licenced product.
- This was done during the early stages of the project and demonstrates the structure of the website on different devices including mobile, tablet and desktop.



**Surface**

*Design*

**Colour Scheme**

Colours associated with exercise related websites tend to contain strong dark colours such as black contrasted with light greens and shades of white. There are often warmer colours added sparingly to add a sense sophistication. I have chosen a palette which reflects this, so the user feels a certain comfortable familiarity. 

https://coolors.co/fcefef-416788-f7b32b-47e5bc-131112
 
**Typography**

**Icons**

- Icons are from the Font Awesome library

## Features

**Existing**

**Features to implement in the future:**



## Technologies Used

During the development and testing of the website:

- **Languages**

   - [HTML5](https://en.wikipedia.org/wiki/HTML): Used to structure the page

   - [CSS3](https://en.wikipedia.org/wiki/CSS): Used to style the different elements on the page
   
   - [JavaScript](https://en.wikipedia.org/wiki/JavaScript): Used to allow the game to produce relevant responses dependent on users' actions

- **Frameworks and libraries**
  - [Materialize]( https://materializecss.com/): website framework with html, CSS and JavaScript
  - [Font Awesome](https://fontawesome.com/): Used for the social media icons on the website
  - [Flask](https://flask.palletsprojects.com/en/2.0.x/): framework for the back end application to connect database to front end web page

- **Media & wireframes**
  - [Balsamiq](https://balsamiq.com/wireframes/): To design the wireframes
  - [Am I Responsive](http://ami.responsivedesign.is/#): Image of site all devices

- **Workspaces & repository hosting**
  - [Gitpod](https://www.gitpod.io/): As a local repository to develop the code
  - [Visual Studio Code](https://code.visualstudio.com/): As a local repository to develop the code
  - [Git](https://git-scm.com/): For version control from gitpod to save commits and push code onto GitHub
  - [GitHub](https://github.com/): To save the code
  - [MongoDB]( https://www.mongodb.com/):  used as the database for the site
- **Testing**
  - [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools): Google inspect was used examine and test responsiveness
  - [Google Mobile Friendly Test](https://search.google.com/test/mobile-friendly?utm_source=gws&utm_medium=onebox&utm_campaign=suit): For additional mobile testing
  - [Google Lighthouse](https://developers.google.com/web/tools/lighthouse): Google lighthouse was used to assess performance of the site
  - [W3C HTML Validator](https://validator.w3.org/): To check there's no error in the HTML code
  - [W3C CSS Validator](https://jigsaw.w3.org/css-validator/): To check there's no error in the CSS code
  - [JavaScript Code Checker](https://jshint.com/) To check there's no errorJavaScript code

- **Deployment**
  - [Heroku]( https://www.heroku.com/): To deploy the live site


## Testing

## Deployment


Using [Gitpod](https://www.gitpod.io/), I created Body50+ web application. Then, using Git commits I pushed the project to my GitHub repository. [Heroku](https://www.heroku.com/) was used with the deployment of the live website. Connecting Gitpod / GitHub to Heroku meant that any git commits changes automatically updated the live site.

**Running Body50+ Online Locally**

**GitHub**

How to clone Body50+ from GitHub

Please note that this project will only run locally if an env.py file is set up containing the IP, PORT, SECRET\_KEY, MONGO-URI and MONGO\_DBNAME. For security reasons these details will not be shared on this documentation. The env.py file should be added to your gitignore file.

1. Navigate to BabusDublinCoding/MS3-Body50+
2. Click on the green Code button
3. Select the code dropdown button beside the Gitpod button
4. Copy the URL listed.
5. Start up your IDE and navigate to the file location.
6. To clone, copy this code and input it into your terminal:

[https://github.com/BabusDublinCoding/MS3-Body50](https://github.com/BabusDublinCoding/MS3-Body50+

**Heroku**

**Deployment to Heroku**

**Create the application**

\* Login in to heroku.com

\* Click on New, and Create new app

\* Enter your app name

\* Select the region that is closest to you

**Connect to you GitHub repository**

\* Click Deploy and select GitHub - Connect to GitHub

\* Enter your repository name and search

\* Click Connect on the correct repository

**Set Your Environment Variables**

Go to settings, and within Config Vars enter the following

\* IP: 0.0.0.0

\* PORT: 5000

\* MONGO\_DBNAME: (enter the database name that you are connecting to)

\* MONGO\_URI: (enter your mongo uri. This is found by going to clusters\&gt; connect\&gt; connect to your application and entering your passwords and dbname within the link)

\* SECRET\_KEY: (This is a secret password that must be very secure.)

**Enable Automatic Deploys**

\* Go to the deploy tab

\* Within the automatic deploys section, choose the branch that you want to deploy from and select Enable Automatic Deploys.


## Credits

This project was heavily influenced by the backend development mini project and the plan was to use it as a basis and adapt it to suit my original idea. Unfortunately I was not able to complete it in the way that I would have like, hence it looks very simlar. I will look to make significant changes when I resubmit it. 



**Content**
- All wording content was written by the developer




## Acknowledgements
- My mentor Narender Singh for his time, patience and motivation
- My girlfriend Giovanna for her constructive criticism, understanding and encouragement 
- Finally, as always the slack community and the [Code Institute]( https://codeinstitute.net/) tutors

