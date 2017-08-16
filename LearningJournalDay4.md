Learning Journal Day 4

JAVASCRIPT
--------------------------------------------------------------------------------
http error 500 ---> server has problem, nothing with page
 WE have learned how to format arrays element

myArray.join(''); ----> puts come between arrays element
myArray.split(''); ---->  you can format your string or array
str.split([separator[, limit]])
letter.split('');

we have also  learned how to create function, global variable and local variable

if variable is not inside the function and also it is used every object of program
it is a global variable

if variable is inside the scope it is a local variable that can survive jus within the
scope.

function creating example:

function evenOrOdd (){
var num = prompt ('Input a number');
num = parseInt(num);
console.log(num%2 === 0);
}

We also learned that functions can return function.

function inception (){
function levelOne(){
console.log( 'we have to go');
}
return levelOne;
}
inception(); will return whole console log
inception()(); will return just inside the console log.
---------------------------------------------------------------------------------------
HTML

We have learned inline and block elements.
inline elements has no default margin or padding, we can set those properties.
block element has default margin but we also can change setting with margin:0px.
Block level elements starts in new line.
We learn how to control postion's of element.
There are four types of positioning
1-static --> all html element  positioned static.It positioned normal flow of paged
position:static;
2-relative --> position of element will be set with top bottom left right
and we can move the element from its old place.
position:relative;
3-fixed 
4-absolute

-------------------------------------------------------------------------------
