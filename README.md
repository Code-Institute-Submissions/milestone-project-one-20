# **Website Casa Capello Restaurant**

**New website of Italian Restaurant Casa Capello in Den Haag, to reserve a spot, check the menu's and find contact details. 
Special attention went to create a site that reflects the place's stylish but down to earth atmosphere of colorful Italian food and warm hospitality. 
The color palette of the graphic designer is integrated into the pages and headings. The clear structure provides good UX and is easy to follow.  
The website is mobile first design, so it will look good on any screen size and is tested in various browsers.**

## UX

This website is for (future) guests of the restaurant Casa Capello. They can find here what they need to know to have a pleasant evening out - the location, menu, 
phone number and opening hours. There is also a form to reserve a spot at the desired time.

On the index page, there is an attractive video of the interior and various dishes that are served, but also a reservation form as that is the main reason to visit the site. In one click the user can navigate to see the other pages that each represent a 'would be' reason to visit the site: 
* -A user wants to find the restaurant, clicks on contact in the nav bar and sees the embedded google maps iframe.
* -A user wants to check the wines, clicks on wijnkaart in the nav bar and sees the menu.
* -A user wants more information on the restaurant, and clicks on Over ons in the nav bar and sees additional information with the possibility to click on links for more information.
* -A user wants to reserve a place, therefore completes the form on the index page, or navigates to the reservation page to complete the form there, or calls the mentioned phone number. 

All external links open in a new tab, the header, and the footer maintain the same throughout the site for familiarity.

The wireframe that was created, very basic, for the index page:

![wireframe index page, there is a header with the words logo, over ons, menu, wijnkaart, contact and a footer, with social icons. In the middle of the page a foto is drawn in a very basic (crappy) way, with the words hero image interior in brackets and the large words Casa Capello. Under this "image" the word reserveren is displayed just above the footer](https://res.cloudinary.com/lavishnessjumpy/image/upload/v1604005411/untitled_elaa8w.png "wireframe index page")

## Features

### *Existing Features*

#### Index

The index page is the place to evoke the emotional response to visit the restaurant. It features a muted hero video of professional pictures
of the interior and food of the place, with an overlay that suggests poetically the expected atmosphere - casual and fine. Also the name of the restaurant is displayed. 
Under the attractive video there is a peekaboo of the heading of the reservation form, to suggest a visitor of the site to reserve a place on the spot. 

#### Over ons

In the about us section a short and clear text describes the restaurant and a short quote by Aldo, the chef and entrepeneur, is 
giving the audience a warm welcome. On large screens an old foto of the family place (the original Casa Capello) is visible. 
At hte bottom of the page small links are visitable, newspapers that reported on the restaurant, for the very interested guest.

Reserve a place in the restaurant by filling in the form on the index or reserveren pages.
Find the restaurant by visiting the contact page and observing the telephone number, email address, opening hours, address and a visual representation of the address by GoogleMaps.
View the menu by visiting the menu page.
View the wine menu by visiting the wijnkaart page.
See information about the restaurant and visit media links by visiting the over ons page.

### *Features Left to Implement*
* Reserve form: interactive by a clickable calendar and a back end integration
* Email adress is a link and opens in user email in pop up
* Instagram live feed visible on one of the pages
* Modal pop up of cookies (when there are tracking cookies)
* Modal pop up of successful reservation/unsuccessful reservation (when reserving is possible)

## Technologies Used
This site was created using HTML, CSS, and a tiny bit of bootstraps/vimeo's JavaScript.

### *Tools*
#### Bootstrap
Bootstrap was used to create a basic responsive structure throughout the site. Layers of custom CSS were placed over a bootstrap framework.  
https://getbootstrap.com/

#### Fontawesome
Fontawesome was used for all the icons on the site.  
https://fontawesome.com/

#### Favicon
Favicon was used to create a favicon in all browsers of the logo.  
http://faviconit.com/en

#### w3schools
W3schools was used to look up basic HTML and CSS properties and uses.
https://www.w3schools.com/

#### Google fonts 
Google fonts were used for the fonts displayed on the page.  
https://fonts.google.com/

#### CSS3 Generator
CSS3 generator was used to generate browser compatible css transformations. 
http://css3generator.com/



## *Testing*
I tested the site by clicking every link on every page, changing screen sizes, and reviewing the responsiveness of every page.
I filled in the reservation form in correct and incorrect ways to check if it was working as desired.
I used LambdaTest (https://www.lambdatest.com/feature) to create screenshots throughout browsers to check if everything looks the same, and 
Browserling (https://www.browserling.com/) and LambdaTest to surf around the site in different browsers to compare the ui. 

I found out that the hero video and overlay was faulty on all other browsers then chrome. I managed to fix this by making the code more precise on size and place.

The images were stretched in other browsers, i found the solution on StackOverflow and used the obect fit property to solve this. 

I discovered that the footer icons do not center vertically in IE 11 and lower, but I did not solve this issue yet.
Vimeo video does not play in opera, I did not solve this issue yet, because when I search for solutions it javascript that comes up.
I'll save that fun for when I learned something about it. 

I checked the code with https://www.w3schools.com/ testing tools and cleared all errors, except the ones referring to browser compatibility code in CSS, or errors referring to libraries I used. 
For example the WebKit code and to mute the hero video, what was done by the advice of the site of Vimeo (that is hosting the video)
"Error: Attribute ?muted not allowed on element iframe at this point."
On the site of Vimeo, it reads: "?muted=1 This parameter will automatically mute your video on load. Once your video plays, viewers can manually un-mute by clicking on the volume bar within the player.
(https://vimeo.zendesk.com/hc/en-us/articles/115004485728-Autoplaying-and-looping-embedded-videos)" This is needed to be able to autoplay throughout browsers.

## *Deployment*
When I was around 80% ready with this site I decided to change a CSS animated hero image to a hero video (the loading of the images was visible and not pretty to see, 
even if hosting from a site and reducing the size as small as possible). Being new to all of this I uploaded the video file in my Github repo and tried to commit. This gave an error because the file was too big, so I deleted it. I thought the commits would be processed, just the file could not join with. Five commits later I realized that it was not possible to push to GitHub because of this error.
It took two weeks of help from the very friendly, and patient Github developer support (go Matt) to manage to delete my crazy big file and push again to GitHub. Because in the meantime i needed to
finish developing the site I made a new repository, this one, and finished the website here. Because the old repository is not relevant anymore for the website itself (just relevant for my study and tutors) I decided not to merge the two repositories. The first, and older repo is visible here:
https://github.com/annakovesdi/milestone-project-1
and is live here: 
https://annakovesdi.github.io/milestone-project-1/


This site will eventually be used by Casa Capello restaurant in Den Haag. But first, I have to learn a lot more to complete it, so I can deliver a full-stack project. This means it will not be officially deployed untill i finish school,
on casacapello.nl. For now it is deployed through GitHub Pages. GitHub Pages is designed to host your personal, organization, or project pages from a GitHub repository.

## *Credits*
Content
* how to change color toggler icon 
https://stackoverflow.com/questions/24080462/how-to-change-bootstrap-toggle-navigation-color/24080725
* hover 
https://css-tricks.com/snippets/css/scale-on-hover-with-webkit-transition/
* hero image with overlay
https://medium.com/@ItsMeDannyZ/code-a-full-width-hero-background-image-with-transparent-overlay-95d757f8ff2c
* css gradient background color 
https://cssgradient.io/
* css border shapes
https://sharkcoder.com/visual/shapes
* css animation
https://www.w3schools.com/css/css3_animations.asp
* favicon
http://faviconit.com/en
* css background video
https://stackoverflow.com/questions/56341147/responsive-hero-with-vimeo-background/56341526
* images changing shape in different browsers
https://stackoverflow.com/questions/29551637/css-image-scaling-issue-with-flexbox-in-firefox-internet-explorer answer of Carl
* Code selector [class*="col-"]
https://stackoverflow.com/questions/19562903/remove-padding-from-columns-in-bootstrap-3 answer by Hashem Qolami
* Image transform css
http://css3.bradshawenterprises.com/cfimg/ Demo 1 - One image to another, on hover
* calculate multiple browser friendly attributes for css 
http://css3generator.com/


## *Media*
The photos and text used in this site were obtained from Julia van de Slikke (Casa Capello)
