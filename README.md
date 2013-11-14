Simple CSS-Only Mega Menu
=========================

__Author:__ Joni Halabi (www.thatdevgirl.com)

Description
-----------

This simple mega navigation menu is inspired by the many mega menus on retail and other websites.  This CSS-only solution is completely customizable - simply modify the HTML and CSS files to meet your specific needs.

What is in the HTML?
--------------------

The HTML for the navigation is enclosed in the <nav> tag, which contains 3 levels of navigation:

1. Level 1 is an unordered list containing only the links in this first level.  These links appear as a bar across the top of the navigation. This list has no child lists.

2. Level 2 is an unordered list containing the links in this second level.  These links appear as a bar across the top of the navigation, below the level 1 navigation.  Each element can have a child element containing the level 3 navigation.

3. Level 3 is hidden on page load and only appears when the user hovers over the applicable link in level 3.  The Level 3 navigation is contained in a <section> tag and can contain any HTML.

What is in the CSS?
-------------------

This project contains 2 CSS files:

1. __reset.css:__ Just a basic CSS reset, inspired by the Eric Meyers' CSS reset. 

2. __menu.css:__ Contains the base styles for the menu, including all hover styles.  The aesthetics are really basic and monochromatic; this CSS file was written with the idea that the developer end-user can customize the styles to match whatever website you are working on.

Credits
-------

Thank you to Place Kitten (http://placekitten.com/) for supplying images used in the Level 3 navigation.
