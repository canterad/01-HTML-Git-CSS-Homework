# 01-HTML-Git-CSS-Homework
The repository was created for the Homework Assignment dealing with HTML, Git and CSS.

Developer: Duane Cantera
Date: Sept. 18, 2021
Assignment: 01 HTML, CSS and Git: Code Refactor

The existing code has been refactored for new technology and to make it more accessible.


****************
HTML CHANGES:
****************

I removed all of the < div > elements and replaced them with semantic HTML elements.
The layout of the semantic HTML elements is shown below:  

|----------------------------------------------------------------------------------------|
| |------------------------------------------------------------------------------------| |          
| |   < header >                                         |          < nav >          | | |
| |------------------------------------------------------------------------------------| |
| |------------------------------------------------------------------------------------| |
| |                                                                                    | |
| |                                  < section >                                       | |
| |                                                                                    | |
| |------------------------------------------------------------------------------------| |
| |                                                                                    | |
| |------------------------------------------------------| |---------------------------| |
| |                      < section>                      | |         < aside >         | |
| | |--------------------------------------------------| | | |-----------------------| | |
| | |                                                  | | | |                       | | |
| | |                    < article >                   | | | |      < section >      | | |
| | |                                                  | | | |                       | | | 
| | |--------------------------------------------------| | | |-----------------------| | |
| |                                                      | |                           | |
| | |--------------------------------------------------| | | |-----------------------| | |
| | |                                                  | | | |                       | | |
| | |                    < article>                    | | | |      < section >      | | |
| | |--------------------------------------------------| | | |-----------------------| | |
| |                                                      | |                           | |
| | |--------------------------------------------------| | | |-----------------------| | |
| | |                                                  | | | |                       | | |
| | |                    < article >                   | | | |      < section >      | | |
| | |--------------------------------------------------| | | |-----------------------| | |
| |                                                      | |                           | |
| |------------------------------------------------------| |---------------------------| |
|                                                                                        |
| |------------------------------------------------------------------------------------| |
| |                                                                                    | |
| |                                      < footer >                                    | |
| |                                                                                    | |
| |------------------------------------------------------------------------------------| |
|                                                                                        |
|----------------------------------------------------------------------------------------|


***************
CSS CHANGES:
***************

I reorder the position of the selectors to match the order of the elements in the HTML file.

I consolidated some of the selectors.  Instead of having selectors for each article or section element I now have one that I can use for all of them.


************************
ACCESSIBILITY CHANGES:
************************

I added alt tags for all of the image elements.

For the background image I added a paragraph element that is displayed off-screen which will be read by the screen reader so the impaired user
will know that an image of a Digitial Marketing Meeting was displayed.


**************
BUG FIXES:
**************

I added a Search Engine Optimization ID so the Search Engine Optimization Navigation Link will work and move to that section of the page.

I changed the title in the < head > section to the company name.

I updated the copy right to the year 2021.


***************
LINKS:
***************

Link To Deployed Application: https://canterad.github.io/01-HTML-Git-CSS-Homework/
