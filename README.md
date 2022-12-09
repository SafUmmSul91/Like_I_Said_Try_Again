# Milestone Project - Portfolio Website
View the live project [here](https://safummsul91.github.io/Like_I_Said_Try_Again/)

This is a Portfolio website I created for my Milestone Project with Code Institute. It is mostly responsive and easy to navigate on different devices.

I created this README.md file using the Code Institute template.

# User Experience (UX)
## User stories
### First Time Visitor Goals
As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about the person the portfolio belongs to, and to be able to navigate through the site to find the content I may need e.g testimonials, social media links, past and upcoming projects.
Returning Visitor Goals
As a Returning Visitor, I want to find the best way to get in contact with the person with any questions I may have.
As a Returning Visitor, I want to find community links.
Frequent User Goals
As a Frequent User, I want to check to see if there are any newly added projects or updates.

# Design
Colour Scheme

The "Brand" Colours I chose are:
* RICH BLACK FOGRA 29 #071013
* SILVER SAND #B8C0CA
* PEWTER BLUE #75ABBC
* PALE PINK #FAD4D8

and where found using [Coolers](https://coolors.co/)
I chose these colours because I thought them modern and fun espcially paired with the font.

# Typography

I chose [Montserrat](https://fonts.google.com/specimen/Montserrat?preview.text=The%20quick%20fox%20jumped%20over%20the%20lazy%20brown%20dog.&preview.text_type=custom&category=Serif,Sans+Serif&sort=popularity) and [Jura](https://fonts.google.com/specimen/Jura?preview.text=The%20quick%20fox%20jumped%20over%20the%20lazy%20brown%20dog.&preview.text_type=custom&category=Serif,Sans+Serif&sort=popularity) 

Monterrat being used for the main body of text and Jura used for Headings, Subheadings, these two fonts were chosen because they are clean and modern and switch up the monotony. They are also easy to read. Sans Serif will be the fallback font in casse they aren't being imported correctly.

# Imagery

I didn't use much imigary in this project, it is quite minimal and straight forward.
The Here Image is the SRM logo that I created using [canva](https://canva.com) it is simple but effective.
The Avatar of the woman in headscarf I also found on [canva](https://canva.com) and edited it to suit the colour scheme.

Wireframes - 

# Features:

* Responsive on all device sizes
* Interactive elements

# Languages Used:

* HTML5
* CSS3

# Frameworks, Programs and Libraries used:

### Balsamiq: 
Balsamiq was used to create the wireframes during the design process.

### Git :
was used to commit to Git and Push to GitHub.

### GitHub: 
GitHub is used to store the projects code after being pushed from Git.

### Font Awesome: 
Font Awesome was used to add icons on all pages throughout.

### Google Fonts: 
Google fonts were used to import the 'Montserrat' and 'Jera' font into the style.css file used for the whole website.

### CANVA: 
CANVA was used to create the logo, resizing images and editing photos for the website.

### Bootstrap 4.4.1: 
Bootstrap was used to help with responsiveness and styling.

### jQuery:
jQuery came with Bootstrap to make the navbar responsive but was also used for the smooth scroll function in JavaScript.

# Testing
The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no errors in the project.

### W3C Markup Validator: All errors fixed.

fixed bug on img and buttons. img required no spaces in the name. 
buttons need href to be removed and replaced with <button onclick="location.href='http://www.example.com'" type="button"> www.example.com</button> solution for button found via stackoverflow.com
fixed bug on images by renaming with no spaces on about.html
gave images "alt"
fixed bugs in contact form by correcting typo in "id" and correcting the "for" from "name" to "text".

W3C CSS Validator:
 
Testing User Stories from UX section

Dev tools - Chrome Lighthouse - Results - Run from incognito - Performance in the green

| Action    | Behaviour          | Success? |
| ------------- |:-------------:| -----:|
| click logo in Navbar| move to designated pages| Y |
| click C.V. link in Navbar| open seperate page with pdf C.V. dowload| Y |
| click buttons in index.html | move to about.html| Y |
| click GET IN TOUCH button in about.html | move to contact section| Y |
| click C.V. button in about.html | open seperate page with pdf C.V. dowload| Y |
| check social icons| leave and go to social website profile     |   Y|
| click submit without filling form | trigger validations|    Y|
| check each page/section is responsive| change to fit different screen resolutions|    Y|

##To Deploy
1.	Log into GitHub
2.	From repositories select Like_I_Said_Try_again
3.	from the menu, select "settings".
4.	Go to the menu on the left, in Code and automation, Select "Pages"
5.	Where it says "Build and Deployment" select the drop-down menu under "Source" and select "Deploy from a branch"
6.	under "Branch", use the None or Branch to select a publishing source
7.	Save. Refresh and go back to "Pages" to find deployed website link.

##To run locally:
1.	Use Google Chrome 
2.	Create/Sign in to GitHub account. 
3.	install GitPod Browser extensions for Chrome and then restart browser.
4.	Log into Gitpod
5.	Go to the Github respository and click the green "Gitpod" button on the right. 

## First-Time Visitor Goals
As a First Time Visitor, I want to easily understand what the site is and learn more about the owner of the portfolio.

Upon entering the site, users are automatically greeted with a clean and easily readable navigation bar to go to the page of their choice. Underneath there is a Hero Image with Text and a "Learn More" Call to action button.
The text on the landing page work with the hero image and call to action buttons invite the user to fiind out more.
The user can click the call to action buttons or use the Navbar, both will go to the same place, to learn more from the website.
As a First Time Visitor, I want to be able to easily be able to navigate throughout the site to find content.
The C.V. is easy to both read and download

The site has been designed to be fluid and never to entrap the user. 
The Nav bar is found at the top pf each page and each link describes what the page they will be clearly.
There is a contact form at the end of each page encouring user to get in touch.
On the Contact Us Page, after a form response is submitted, the page refreshes and the user is brought to the top of the page where the navigation bar is.
Small simple social media links are found down first on Lnading page and then in footer of each page should user wish to find out more.

## Returning Visitor Goals
As a Returning Visitor, I want to find the best way to get in contact with the owner with any questions I may have.
The navigation bar clearly highlights the "Contact" Page.
Here they can fill out the form on the page or use the contact information provided.
They can message the owner on their social media.
The footer contains links to the organisations Github, Pinterest and Instagram.
Social links will open in a seperate tab so the user doesnt loose track of where they were on the website.

As a Returning Visitor, I want to find the C.V. option to download if need be.

# Further Testing
The Website was tested on Google Chrome, Internet Explorer, Microsoft Edge and Safari browsers.
The website was viewed on a variety of devices such as Desktop, Laptop, Samsung Note 20, Samsung 20Fe.
Tests work done on each link to make sure they were linking correctly.
Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues. - They commented that the layout could be better on the about page in smaller resolutions.

## Known Bugs
On some mobile devices the text on the Landing page is out of alignment due to font size..
A white gap can be seen under Hero image.
On about page the text elongates and buttons are pushed together.


# CREDITS & Acknowledments

* Bootstrap4: Bootstrap Library used throughout the project.

* Canva used to create leaflets and graphics used in portfolio  page and for Hero image and Avatar.

* Youtube: helping me through bugs and responsiveness issues

* Mentor D.Vlaanderen for giving me tips and spotting typo's last minute

* Code Institute:
1. for their support and for giving me a much appreciated and needed extention.
2. Sample C.V. 





