# CS-Travel Site

This is a website designed for users to search for hotels in their desired locations around the world.
Users can see names, addresses, telephone numbers, ratings and websites(where available) of the hotels.

It demonstrates the use of HTML, CSS, jS, Materialize, Font Awesome, and the Google Maps and Places APIs.



## Features

* On screen sizes 992px and below, the navigation bar becomes a side-nav for user convenience.
 
* Users are prompted to enter a city which they would like to travel to. Once the city is entered, users are provided with locations of the hotels in the area. 

* The names of the hotels are listed on the left of the map on screens with a width of 992px or above, as well as being shown as map markers on all screen sizes.

* Users can either explore the hotels on the map by clicking on the markers. 

* Once clicked, the user is shown the name, address, telephone number, rating and website(where available) of the hotel.

* Users are also provided with details of popular destinations, as well as a photo gallery showing popular places around the world.

* In the Contact section, users can see CS-Travel's address and contact the company with queries regarding bookings. As this is not an actual company, 
the form cannot be sumbitted.

* There are social media links in the footer for users to follow CS-Travel. As this is not an actual company, the links direct the user 
back to the homepage.



## Testing

* Click on each nav-bar item. Ensure that you are directed to the correct location on the page.

* Click on each side-nav item. Ensure that you are directed to the correct location on the page.

* Ensure that the Google Map loads once the user enters the site.

* Ensure that markers are returned on map once a destination has been entered.

* Click on each marker to ensure that the Hotel Name, Address, Telephone number, Rating, and Website are shown.

* Search for destinations on screens with a width of less than 992px and ensure that the results list is no longer shown.

* Click on NOW! in the 'Return to Map' section to ensure that you are brought back to the 'Search' section.

* Click on each picture in the 'Gallery' section to ensure that the picture becomes enlarged.

* Enter a character in the 'Name', 'Phone', and 'Enter Message' input fields of the 'Contact' section. Ensure that the line under each input field 
turns from red to green to show validation.

* Enter characters before and after an '@' in the email input field. Ensure that the line below the email field turns green. If charcaters are not entered in this order, then the line will be red.

* Ensure that all social media links return the user to the homepage.




*SEARCH FUNCTION AND MAP TOO FAR DOWN THE PAGE*

UserStory: The user would load the page and the first thing they would see was the slider which occupied most of the page. User was unsure where to click at first.

This was fixed shortly after as I removed the slider, pushed the search function to the top of the page, and showed the map directly underneath so that users are prompted straightaway to enter a search location
and the hotels in that area are shown immediately.


*RESULTS TABLE SHOWING UNDER THE MAP*

UserStory: The user would search for hotels and then be given a list of results below the map. This lead to a lot of unnecessary scrolling and a bad user expereince.

This was fixed shortly after as I had the results table show on the map rather than below it, allowing users to see the map and results at the same time. 
For screens with a width below 992px, I removed the results table, as it would cover too much of the map. Instead, users can use their fingers to move the map and click on the results.


*SOCIAL MEDIA LINKS NOT VERY NOTICEABLE*

UserStory: The user scrolled past the social media section without noticing it, as it was placed in the middle of the page.

This was fixed by moving the social media links to the footer, for a better user experience.


*COLOUR-SCHEME MADE THE FONT DIFFICULT TO READ*

UserStory: The user found the font difficult to read as the initial colours were too bright. 

This was fixed by using colours which compliment each other and allow the font to be easily read.


*SUBMITTING CONTACT FORM LED TO 404 ERROR*

UserStory: The user was shown an error after clicking the submit button on the contact form. 

This was fixed by changing the button type="submit" to type="button" in order to stop the form from being submitted, as this
is just an example contact form. If we were submitting the contact form, and using button type="submit, then each input field
is set up to be validated before a successful submission.




## Deployment

* This website was deployed to Github Pages using git.

* From the Travel-site repository on Github, I clicked on 'settings' and scrolled down to the 'Github Pages section'.

* I selected 'master branch' as the source, and the site is now deployed at (https://ciaranm-2018.github.io/travel-site/)

* I then added (https://ciaranm-2018.github.io/travel-site/) to the list of HTTP referrers, so that API requests can be made
and the Google Map can funtion when the site is loaded.

 
 
## Credits
 
 Content:
 
 [Wikipedia](http://www.wikipedia.com)
 
 [Google Maps API](https://developers.google.com/maps/documentation/)
 
 [Materialize](https://materializecss.com/)
 
 [Font Awesome](https://fontawesome.com/)
 
 
 
 
 Media:
 
 The photos used in this site belong to the author (Ciaran Mitchell).
                                                  


## Author

 Ciaran Mitchell
 
