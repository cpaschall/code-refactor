# Code Refactoring

## Project Goal
 
A client has asked us to refactor the HTML and CSS files of their website's main page, named [index.html](./Develop/index.html) and [style.css](./Develop/assets/css/style.css), respectively.

**Rafactoring** makes code more accesible and readable, without changing what the code does.  
  

## Acceptance Criteria and Changes

**GIVEN a webpage meets accessibility standards**

*WHEN* I view the source code
*THEN* I find semantic HTML elements

- Replaced all "div" tags to the semantic "section" tag
- line 11: replaced div tag with lass "header" to semantic element tag "header"
- line 27: added "main"semantic tag for the main body of the webpage
- line 76: replaced div tag with class "footer" to semantic elementic tag "footer"

*WHEN* I view the structure of the HTML elements
*THEN* I find that the elements follow a logical structure independent of styling and positioning

- Confirmed proper indentation was used for parent and child elements

*WHEN* I view the icon and image elements
*THEN* I find accessible alt attributes

- Added "alt" attribute to all "img" tags that describe the image displayed 


*WHEN* I view the heading attributes
*THEN* they fall in sequential order

- line 14: replaced "ul" tag with "ol" to indicate an ordered (sequential) list


*WHEN* I view the title element
*THEN* I find a concise, descriptive title

- line 7: Added a relavent title to the "title" tag

*All elements and classes were updated in the CSS file to reflect the changes in tags listed above*

## Final Product
  
The final webpage should should appear unaltered from the orginal source code when viewed in a browser.  Below is how the page is expected to appear.
  
![Horiseon Main Page](./assets/images/horiseon-desktop.png)
