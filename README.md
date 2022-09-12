# Drury Buildings #
*My ever first project in coding* is presenting a great place in Dublin City Centre where any person who interested in a tasty small bite or a large dish, a great drink or a high-standard cocktail is looking at the right website. 

The users can find a short description about the history of the place, menu, details regarding the scheduele, contact information and useful links for social media. 

## Features ##

![Header](/assets/images/header.png)


* ### Navigation ### 

   * Starting with the header on the left corner is the name of the venue that links to the home page when clicked.
   * The Menu is on the right side next to the home page again just to be sure the users will find easy the access to the home page.
   * The short description under the header has a paragraph finishing with a link to Menu page when cliked. 
   * At the bottom of the home page in the contact details section, the reservation email when clicked sends the user straight to the email program.
   * The footer contains clickable icons linked to social media platforms.

![Contact details and footer](/assets/images/footer.png)

* ### The Header ###
  * The clickable navigation pages in the header display a red bottom line when we hover the mouse over them. 
  * The header image is the front of the building and has an animation keyframe that brings the attention on the home page while the photo comes from backwards towards the front.
  * In the first paragraph the 'Menu', linked to the menu page has the background-color and the text-color inverted when we hover over so will make aware the user that is a clickable link.
  * The same style applies to the email in contact details so we keep the same structure and style over the page. 

## Testing ##

 * I confirmed that this project is responsive, looks good and function on all standard screen sizes using the Chrome Developer Tool.
 * I confirmed that all the navigation links are working.
 * I confirmed that all text is readable and easy to understand.


### Bugs ###

 #### Solved Bugs ####
  * First the tables for opening hours and contact details had 3 rows and 2 columns and for the row with header I used the colspan atribute to make sure is centered. The style of the page has simple lines so I wanted to keep the same style for these tables but because of the desire to have only border-bottom the tables would have an interupted line between the columns.
    * Removing the columns and write the data in one column fixed the issues and have a nicer aesthetic display.

  * The header image wasn't responsive on the larger screens and the photo would strech. 
    * Looking closer at the CSS properties I gave a certain value for height and width in pixels. I removed those values and left only width 100% which solved the issue.

  * I gave sections in my HTML file without having any heading elements so the validator showed me errors.
    * I have changed the sections with divs to avoid any errors.

  * My icons for social media wouldn't display in the footer.
    * I took the codes from Font awesome 6 instead of version 5 so I simply just copy-paste the older version and that fixed the issue.

  * Using the br element in my list from menu page would give me an error when I was validating the codes.
    * I changed the br with another li element and give it a padding-top value to create a space between my title for items and the list of dishes.

  * My keyframe animation for the header image wouldn't work first.
    * When I checked the value for transform property I've noticed a space between the scale and the bracket containing the scale value. Easy to be fixed by deleting the space.

### Validator Testing ###
 
 * #### HTML ####
    * Both pages have no errors when passing through the official W3C Validator

* #### CSS ####
    * The CSS stylesheet presents no errors when passing through the official (Jigsaw) Validator

* #### Accesibility ####
    * I confirmed the accesibility and the others scores for this website using the lighthouse, desktop and mobile version.
    
    ![Desktop](/assets/images/Project1-desktop.jpg)
    ![Mobile](/assets/images/Project1-Mobile.jpg)


### Unsolved Bugs ###
    * No unsolved bugs





