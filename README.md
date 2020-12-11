Summary: This is simple static site exercise produced using Bootstrap and SASS/CSS for styling. 

All pages have identical Bootstrap navbar component for navigation links.
 
index.html: Landing page with a Bootstrap container containing a custom hero class for the cursive script which uses a Google font linked in the 
head of the page. Finally we have a Bootstrap Jumbotron displaying another quote and its author in div styled by accessing its id in the stylesheet styles.css

bio.html: Utilizes a mobile-responsive @media query to affect CSS pseudoclass "before" of h1 to display full name "Ramakrishna Paramahansa" on large displays 
and shortened name "Ramakrishna" on small displays. There's an image styled inline with some padding. Some paragraphs of text styled through 
Sass inheritance and variable to set background-color (but trouble accessing font size; see below)

quotes.html: A Bootstrap grid with an image with responsive size.
An image and a lead section with a link styled in CSS by child selector.
Finally it displays a Bootstrap styled nested list to display the quotes. 

books.html: Utilizes a Bootstrap container with responsive flex layout to display book covers. 
Below is a Bootstrap styled table with background-color set by a SASS variable and border defined using SASS nesting.
The table displays book title, author and hyperlinks to Amazon where user can buy them.
