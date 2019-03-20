# Midterm Assignment
## By: Genessis Galindo

### Link to Website
http://csc174.org/midterm/ggalindo/

## Domain
The domain of the website is festivals in Rochester for the 2019 calendar year. 

## Ontology
### Overall Website
- The goal of the website is to get the person visiting the website to want to read more about the festivals in Rochester and the secondary goal is to get them to 'Subscribe' to a Newsletter to stay up to date with the festivals and their details. 

### Index
- The index introduces the topic of festivals and gives a general overview to entice the reader to read more. 

### Individual Page
- The page gives more details pertaining to each festival such as a general overview and more details regarding each. 

## Taxonomy
### Index
- h1 tag for the introduction of topic: Rochester Festivals 2019
	-nav bar composes of "Home, Festivals, Sign-Up"

- h2 tag is for the name of each of the festivals talked about on the website
	- Each festival has a name
	- Each festival has a photo
	- Each festival has an "about" section which gives a bried overview 
	- Each festival has a "details" section (which includes all the following for the festivals):
		- Dates
		- Times
		- Locations
		- Phone Numbers
		- Emails
		- Admission Type
		- Link to the event website

	- footer is "© CSC 174: Advanced Front-end Web Design and Development" and a button to "Subscribe" to the newsletter

### Choreography 
- The index page is a landing page and general introduction to the visitor
	- The "Z-Pattern" allows for the visitors to get a general overview of the topic being discussed and allows for them to scan entire page and continue to the festivals page
- Festival page begins with festivals in chronological order depening on when they take place in the calendar year and 
	- The "F-Pattern" allows for visitors to scroll while looking on the left hand side and having easy accessibility to the Festival names and a picture to try and capture their attention, the users can then read more information about it such as a snippet about the festival and then more details are located on the left-most part of the section which gives visitors more crucial info such as dates, times, locations, contact info, and a link to the event website
	1. Home (index page)
	2. Festivals
	3. Sign-Up

### Application of Z-Pattern
- The implementation of the Z-Pattern on the index page was used to allow the visitor to scan the entrire website
	- On the upper left hand side, I put the title to the website "Rochester Festivals 2019" so that right off the bat, users would know what the website was about
	- On the upper right hand side, I put the nav bar to allow for users to glimpse the titles in the nav bar and not only continue to get an overview of what the webiste contains but also allows for easy access to navigate
	- In the center, I put a slider with various images of festivals to continue to garnish the vistors' attention in the website so that they want to keep reading if they see something they like and are intrested in 
	- To the right side, beneath the slideshow, I wrote a little snippet about what the website contains so that yet again, the user wants to keep reading
	- To the left side, beneath the slideshow, I put a "Learn More" button because now that the user has read the entire index page and made it to the button, they are most likely eager to read more about the topic and this button allows for easy access to keep reading
	- I then utilized a footer to allow for easy access to the "Subsribe" should anyone be eager to sign-up asap while still on the index page

### Application of F-Pattern
- The implementation of the F-Pattern on the festivals page was used to allow for visitors to get a quick glimpse of what types of festivals were offered, for example, users could scroll quickly and look at titles and decide if they want to read more or not
	- On the furthest left of the F-Pattern, I put a picture of the image to get people's attention quickly since users tend to like pictures and pictures grab attention
	- In the middle, I put an "about" section since now that the user is hooked by the picture, they would want to read more about the festival
	- On the furthest right, I put the "details" section so that the ones who were most interested in learning more about the festival had the opportunity to do so

### C.R.A.P. Principles
- Contrasts: The colors contrast one another to work on emphasizing what is important such as my usage of dark colors for the header and the footer allow for the content to stand out in white (the nav bar) and the "subsribe" button. The usage of the color red for the buttons also brings attention to them since they are either on blue or an off white color. The color contrasts allow the user to really pay attention to what is on the page. The font contrasts also allow the user to differentiate from eye catching stuff (such as titles) to more important info that needs to be clean in apperance and easy to read (details and about sections)

- Alignment: Alignment is used to keep things seperated but also easy to read-- once a user finds a topic of interests in the larger titles, it allows for them easy access to find more information on it

- Proximity: Proximity is also used to keep things together that need to be together such as the nav bar for easy access to pages the user may want to visit but proximity also helps keep areas apart from one another on the festivals page to allow more readability for the user-- proximity of the lines (line height) was also changes to allow for more readability


### Fonts
- I selected the "Rubik" font because it was fun yet clear and concise. These festivals are meant to be fun but these festivals may also attract different audiences, for example, some festivals may be more family-oriented but some are not (such as the Flour Beer Festival) but the Rubik font allows for a touch of fun that would not appeal to just one of the audiences but has a better chance at appealing to various audiences
- I then selected the "EB Garamond" font because it allows for clear and concise reading which improves availability since again, the audience that would probably be visiting this page varies also since there is a lot of information, serif fonts allow for a cleaner look

### Structure Behind CSS Architecture
- CSS Organization Technique based off of SMACSS (Scalable and Modular Architecture) 
Base -> Layout -> Module -> State (no theme section since I did not utilize it)
- Outline of CSS Structure:
	- Base
	- Layout
	- Module
	- State
