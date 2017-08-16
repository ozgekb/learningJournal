Learning Journal DAY 1
HTML
---------------------------------------------------------------------------------------------------
<!-- --> comment symbols for html
<!DOCTYPE html> --> declare that this document is HTML
<html> </html>--> opening and closing html tag  that everything should be inside between opening html and closing html tag.
<head></head> --> it contains metadata of html file
<body></body> --> visible part of html. Everything inside the  body tag can be seen from the page.
<h1></h1> --> it contains headings.Every page just has one h1 headig and it coninues <h2><h3><4><h5><h6>.Heading gets smaller.
<p></p> --> contains paragraphs.
<a href="https://www.google.com">This is a link </a> --> makes the text link.
<img src = "img.jpeg" alt="www.google.co,">  --> it has no closing tag and show image.
<div></div> -->used as a container generally use with class.Always starts on new line and takes the full width
<nav></nav> -->container that contains group of element.
<section></section> -->container that keeps group of element
<span><span> -->does not start new line  only takes up necessary width.Used as a container for some text.

to check to code right click to page click inspect to debug.

"section – Used for grouping together thematically-related content. Sounds like a div element, but its not.
The div has no semantic meaning. Before replacing all your div’s with section elements, always ask yourself,
“Is all of the content related?”.

aside – Used for tangentially related content. Just because some content appears to the left or right of the main content isn’t
enough reason to use the aside element. Ask yourself if the content within the aside can be removed without reducing the meaning
of the main content. Pullquotes are an example of tangentially related content.

header – There is a crucial difference between the header element and the general accepted usage of header (or masthead). There’s
usually only one header or ‘masthead’ in a page. In HTML5 you can have as many as you want. The spec defines it as “a group of
introductory or navigational aids”. You can use a header in any section on your site. In fact, you probably should use a header
within most of your sections. The spec describes the section element as “a thematic grouping of content, typically with a heading.”

nav – Intended for major navigation information. A group of links grouped together isn’t enough reason to use the nav element.
Site-wide navigation, on the other hand belongs in a nav element.

footer – Sounds like its a description of the position, but its not. Footer elements contain information about it’s containing
element: who wrote it, copyright, links to related content, etc. Whereas we usually have one footer for an entire document,
HTML5 allows us to also have footer within sections."http://www.anthonycalzadilla.com/2010/08/html5-section-aside-header-nav-footer-elements-not-as-obvious-as-they-sound/
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
JAVASCRIPT
 -HTML to define the content of web pages
 -CSS to specify the layout of web pages
 -JavaScript to program the behavior of web pages

 alert('');-->shows a message in popup box in the page and ok button
 prompt(''); --> shows a message , and it has input holder that user can enter input.it has cancel and ok button.
 var  variableName; keeps value of variables.
 var x = prompt('');
 parseInt(string, radix); it returns string to number if it can not it return NaN
 parseInt("123hui") returns 123
 console.log(''); keeps user input to check(debugging)
 console.log('Question:' + yourVariable +'contunue your message' );

 -------------------------------------------------------------------------------------------------------------------------------------------------------------------------
ATOM

install package for correction and auto filling
apm install linter -eslint
apm install emmet
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------
HTML
<script src="app.js"></script> --> use after body{} it includes java file.
<strong></strong> --> make text bold
<em></em> -->make text italic
4<sup>th</sup>  --> yaziyi yukarida yaziyor
co<sub>2</sub>  --> yaziyi asagida tutuyor
<br></br>       --> try not to use it .breaks line
<hr></hr>       -->  draww line
<q>     ---> quatation mark
<abbr>   -->kisaltmalari uzatiyor
<acronym>  --> kisaltma
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------
CSS
p{
 color : red; --> changes text color
 text-align: center; --> allign text center.
}
h1, h2, p {
    text-align: center;
    color: red;
}
p.center {
    text-align: center;
    color: red;
}
body {
    background-image: url("img_tree.png");
    background-repeat: no-repeat; background image wiil not repeat
    background-position: right top; --> background image position
    background-attachment: fixed; backgrounf image will not scroll to page
}


html file <h1 class="center">This heading will not be affected</h1>

background-color: lightblue; --> changes background color
