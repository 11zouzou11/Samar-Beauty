# Samar Beauty

![ProjectImage]
(./assets/img/browlift/browlift2.jpeg)
> Beauty at a high level, no compromises!

## Table of contents

1. [Introduction](#introduction)
2. [HowToUse](#howtouse)
3. [Issuesandbugs](#issuesandbugs)
4. [TechnologiesUsed](#technologies used)
5. [Deployment](#deployment)
6. [Credits](#credits) 
 
---

# Project Description

Samar Beauty is a website for the modern women and men who wants to take care of their skin and renew their youth cells.
it's a website with various treatments and servecis to help the customers to take care of their skin and body.

[Back to top ⇧](#Samar-Beauty)

## How To Use 

### Structure

This is a 3 pages website.
1. The first page is the home page and it has 3 sections
    1. The HOME section and the introduction image with some paragraphes.
    2. The ABOUT section where it gives some description regarding the business owners and their expertise.
    3. The SERVICE section where it shows the different services that the website has to offer.
2. The second page is a GALLERY that has a mix of pictures taken by the owners of the business to showcase their practical results on clients.
3. The third pasge is a CONNECT page to get info about the potential clients that need to book new sessions or for consultancy, with a map to the business address.

### Skeleton 

Wireframe mockups were created in a [Balsamiq]((https://balsamiq.com/)

Website :
![Website Wireframe](/workspace/Samar-Beauty/assets/img/Samar-beauty.png "Website Wireframe")


[Back to top ⇧](#Samar-Beauty)

## Issues and Bugs 
The developer ran into a number of issues during the development of the website, with the noteworthy ones listed below, along with solutions or ideas to implement in the future.

**Navbar Bug** - A bug with the Navigation bar. the navbar wasn't taking effect the color set by the developer. While searching on the web if someone had the same issue, the developer found on [Stack Overflow](https://stackoverflow.com/questions/46237610/bootstrap-4-navbar-color-wont-change "Link to Stack Overflow solution") a similar problem with a solution that he implemented and fixed the bug.

**Hero Image Issue - Home Page** - A bug was detected while styling the hero image where the image wasn't taking the position properly, while searching the web to see if someon else had the same ussue the developer found a solution posted on  [Stack Overflow](https://stackoverflow.com/questions/26236486/background-size-cover-not-working "Link to Stack Overflow solution") that helped to fix the bug.

**Google Maps iFrame Issue (Live Page)** - A bug found with the iframe element of the connect page (which was used to implement a Google Maps embed). There was a problem with the responsiveness of the iframe, caused the map to extend over the specified width. while `overflow: hidden;` would have worked with larger screens, it didn't work well on smaller screens. The developer found a post on [Digital Inspiration](https://www.labnol.org/internet/embed-responsive-google-maps/28333/ "Link to Digital Inspiration solution") that helped to understand the problem and to successfully implement a solution.

[Back to top ⇧](#Samar-Beauty)

## Technologies Used

### Main Languages Used

1. [HTML5](https://en.wikipedia.org/wiki/HTML5 "Link to HTML Wiki")
2. [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets "Link to CSS Wiki")

### Frameworks, Libraries & Programs Used
1. [Bootstrap](https://getbootstrap.com/docs/4.4/getting-started/introduction/ "Link to Bootstrap page")
     - Bootstrap was used to implement the responsiveness of the site, using bootstrap classes.
2. [Google Fonts](https://fonts.google.com/ "Link to Google Fonts")
    - Google fonts was used to import the fonts "Roboto", "Lato" and "Montserrat" into the style.css file. These fonts were used throughout the project.
3. [Font Awesome](https://fontawesome.com/ "Link to FontAwesome")
     - Font Awesome was used on all pages throughout the website to import icons (e.g. social media icons) for UX purposes.
4. [Git](https://git-scm.com/ "Link to Git homepage")
     - Git was used for version control by utilizing the GitPod terminal to commit to Git and push to GitHub.
5. [GitHub](https://github.com/ "Link to GitHub")
     - GitHub was used to store the project after pushing
6. [Balsamiq](https://balsamiq.com/ "Link to balsamiq homepage")
     - Figma was used to create the wireframes during the design phase of the project.
7. [Am I Responsive?](http://ami.responsivedesign.is/# "Link to Am I Responsive Homepage")
     - Am I Responsive was used in order to see responsive design throughout the process and to generate mockup imagery to be used.

[Back to top ⇧](#Samar-Beauty)

## Deployment

This project was developed using [GitPod](https://www.gitpod.io "Link to Visual Studio Code site"), committed to git and pushed to GitHub using the computer terminal.

### Deploying on GitHub Pages
To deploy this page to GitHub Pages from its GitHub repository, the following steps were taken:

1. Log into [GitHub](https://github.com/login "Link to GitHub login page") or [create an account](https://github.com/join "Link to GitHub create account page").
2. Locate the [GitHub Repository](https://github.com/11zouzou11/Samar-Beauty "Link to GitHub Repo").
3. At the top of the repository, select Settings from the menu items.
4. Scroll down the Settings page to the "GitHub Pages" section.
5. Under "Source" click the drop-down menu labelled "None" and select "Master Branch".
6. Upon selection, the page will automatically refresh meaning that the website is now deployed.
7. Scroll back down to the "GitHub Pages" section to retrieve the deployed link.
8. At the time of submitting this Milestone project the Development Branch and Master Branch are identical.

### Forking the Repository
By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log into [GitHub](https://github.com/login "Link to GitHub login page") or [create an account](https://github.com/join "Link to GitHub create account page").
2. Locate the [GitHub Repository](https://github.com/11zouzou11/Samar-Beauty "Link to GitHub Repo").
3. At the top of the repository, on the right side of the page, select "Fork"
4. You should now have a copy of the original repository in your GitHub account.

### Creating a Clone
How to run this project locally:
1. Install the [GitPod Browser](https://www.gitpod.io/docs/browser-extension/ "Link to Gitpod Browser extension download") Extension for Chrome.
2. After installation, restart the browser.
3. Log into [GitHub](https://github.com/login "Link to GitHub login page") or [create an account](https://github.com/join "Link to GitHub create account page").
2. Locate the [GitHub Repository](https://github.com/11zouzou11/Samar-Beauty "Link to GitHub Repo").
5. Click the green "GitPod" button in the top right corner of the repository.
This will trigger a new gitPod workspace to be created from the code in github where you can work locally.

How to run this project within a local IDE, such as VSCode:

1. Log into [GitHub](https://github.com/login "Link to GitHub login page") or [create an account](https://github.com/join "Link to GitHub create account page").
2. Locate the [GitHub Repository](https://github.com/11zouzou11/Samar-Beauty "Link to GitHub Repo").
3. Under the repository name, click "Clone or download".
4. In the Clone with HTTPs section, copy the clone URL for the repository.
5. In your local IDE open the terminal.
6. Change the current working directory to the location where you want the cloned directory to be made.
7. Type 'git clone', and then paste the URL you copied in Step 3.
```
git clone https://github.com/USERNAME/REPOSITORY
```
8. Press Enter. Your local clone will be created.

Further reading and troubleshooting on cloning a repository from GitHub [here](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/cloning-a-repository "Link to GitHub troubleshooting")

[Back to top ⇧](#Samar-Beauty)

## Credits 

### Content
- The text used is written by the beauty artist Samar.

## Code 

The following sites were used on a more regular basis to help implement and build this responsive website : 

- [Stack Overflow](https://stackoverflow.com/ "Link to Stack Overflow page")
- [W3Schools](https://www.w3schools.com/ "Link to W3Schools page")
- [Bootstrap](https://getbootstrap.com/ "Link to BootStrap page"
- [Google](https://www.google.com/ "Link to Google page)
- [Youtube](https://www.youtube.com/ "Link to Youtube page)


- Note:
1. the video contect were used to get a better understanding of the elements and everything got modified to meet the websites goals. 
2. all the code that has been borrowed is credited within the html code.

[Back to top ⇧](#Samar-Beauty)