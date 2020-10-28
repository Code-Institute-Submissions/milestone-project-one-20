Website Casa Capello Restaurant

New website of Italian Restaurant Casa Capello in Den Haag, to reserve a spot, check the menu's and find contact details. 
Special attention went to create a site that reflects the place's stylish but down to earth atmosphere of colorful Italian food and warm hospitality. 
The color palette of the graphic desginer is integrated in the pages and headings and a easy to follow, clear structure provides good UX. 
The website is mobile first design, so it will look good on any screen size, and is tested in various browsers.

UX

This website is for (future) guests of the restaurant Casa Capello. They can find here what they need to know to have a pleasant evening out - the location, menu, 
phone number and opening hours. There is also a form to reserve a spot at a desired time.

On the index page there is an attractive video of the interior and verious dishes that are served, but also a reservation form as that is the main reason to visit 
the site. In one click the user can navigate to see the other pages that each represent a 'would be' reason to visit the site: 
-A user wants to find the restaurant, clicks on contact in the nav bar and sees the embedded google maps iframe.
-A user wants to check the wines, clicks on wijnkaart in the nav bar and sees the menu.
-A user want more information on the restaurant, and clicks on Over ons in the nav bar and sees additional information with the possibility to click on links for more information.
-A user wants to reserve a place, therefore completes the form on the index page, or navigates to the reservation page to complete the form there, or calls the mentioned phone number. 

All external links open in a new tab, the header and the footer maintain the same throughout the site for familiarity.

The design is clear and easy to follow, therefore no wireframes were needed to create the structure.


Features

Existing Features
Reserve a place in the restaurant by filling in the form on the index or reserveren pages.
Find the restaurant by visiting the contact page and observing the telephone number, email address, opening hours, address an a visual representation of the address by googlemaps
View the menu by visiting the menu page
View the wine menu by visiting the wijnkaart page
See information about the restaurant and visit media links by visiting the over ons page

Features Left to Implement
Reserve form: interactive by a clickable calendar and a back end integration
email adress is a link and opens in user email in pop up
instagram live feed visible on one of the pages

Technologies Used
This site was created using HTML, CSS and a tiny bit of bootstraps JavaScript.

tools
bootstrap
Bootstrap was used to create a basic responsive structure throughout the site. Layers of custom css were placed over a bootstrap framework.
https://getbootstrap.com/

Fontawesome
Fpntawesome was used for all the icons in the site 
https://fontawesome.com/

favicon
Favicon was used to create a favicon in all browsers of the logo 
http://faviconit.com/en

w3schools
w3schools was used to look up basic html and css properties and uses 
https://www.w3schools.com/

Google fonts 
Google fonts was used for the fonts displayed on the page
https://fonts.google.com/



Testing
I tested the site by clicking every link on every page, changing screensizes and reviewing the responsiveness of every page.
I filled in the reservation form in correct and incorrect ways to check if it was working as desired.
I used LambdaTest (https://www.lambdatest.com/feature) to create screenshots throughout browsers to check if everyting looks the same, and 
Browserling (https://www.browserling.com/) to surf around the site in different browsers to compare the ui. 

I discovered that the footer icons do not center vertically in IE 11 and lower, but i did not solve this issue yet.

I checked the code with https://www.w3schools.com/ testing tools and cleared all errors, except the ones referring to browser compatability code in CSS, or errors referring to libraries i used. 
For example the webkit code and to mute the hero video, what was done by advice of the site of Vimeo (that is hosting the video)
"Error: Attribute ?muted not allowed on element iframe at this point."
On the site of Vimeo it reads: "?muted=1 This parameter will automatically mute your video on load. Once your video plays, viewers can manually un-mute by clicking on the volume bar within the player.
(https://vimeo.zendesk.com/hc/en-us/articles/115004485728-Autoplaying-and-looping-embedded-videos)"

Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

Different values for environment variables (Heroku Config Vars)?
Different configuration files?
Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.

Credits
Content
how to change color toggler icon 
https://stackoverflow.com/questions/24080462/how-to-change-bootstrap-toggle-navigation-color/24080725
hover 
https://css-tricks.com/snippets/css/scale-on-hover-with-webkit-transition/
hero image with overlay
https://medium.com/@ItsMeDannyZ/code-a-full-width-hero-background-image-with-transparent-overlay-95d757f8ff2c
css gradient background color 
https://cssgradient.io/
css border shapes
https://sharkcoder.com/visual/shapes
css animation
https://www.w3schools.com/css/css3_animations.asp
favicon
http://faviconit.com/en
css background video
https://stackoverflow.com/questions/56341147/responsive-hero-with-vimeo-background/56341526
images changeing shape in different browsers
https://stackoverflow.com/questions/29551637/css-image-scaling-issue-with-flexbox-in-firefox-internet-explorer answer of Carl
Code selector [class*="col-"]
https://stackoverflow.com/questions/19562903/remove-padding-from-columns-in-bootstrap-3 answer by Hashem Qolami
Image transform css
http://css3.bradshawenterprises.com/cfimg/ Demo 1 - One image to another, on hover
calculate browser attributes for css 
http://css3generator.com/


Media
The photos and text used in this site were obtained from casa capello






question mentor: 
Error: The value of the for attribute of the label element must be the ID of a non-hidden form control.

From line 112, column 25; to line 112, column 44

          <label for="number">Person

