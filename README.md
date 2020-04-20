# Project 0

Web Programming with Python and JavaScript

This project contains four web pages that tell a little about me.

HTML

index.html (or pg1) is the starting page. It has a drop down list that shows am image of some of the foods I enjoy. 
It also has a set of four buttons on the bottom that allow you to get from any page to any other page.
The buttons are made by using the bootstrap component "btn-group"

pg2.html shows some of the books that I like.
The list is an unordered list that contains ordered lists.
To help with the layout I used bootstrap's grid model to center the list. 
There are three columns with the list being in the center while the left and right are empty.

pg3.html uses a table to display some of the older music that I like. 
The rows show Album, Artist, and images of the Cover Art.

pg4.html shows google map views of my house. There is a neighborhood view and a closeup of just my house.
To change from one to the other I used a mobile-responsive @media query.
When you narrow the screen, the image changes from neighborhood view to the closeup.

CSS and SCSS

proj0_css1.css is the main css for the project.
It contains the media query used in pg4.html.
It uses more than five different properties and more than five different selectors.
It also uses both class and ID selectors.

style.scss is a sass sheet. It gets compiled into style.css.
It uses $color as a variable, .pgTitle for nesting and .foot with .specificFoot as an example of inheritance.

cs50 project0.mp4 is the screencast. I apologize for the poor quality, I think this is due to my poor laptop.