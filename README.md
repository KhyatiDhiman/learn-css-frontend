CSS Selectors:

1. Selectors are used taget elements & apply CSS
2.Three simple selectors
	1.1 Element Selector
	1.2 Id Selector
	1.3 Class Selector
3. Priority of Selectors
	Id > Class > Element
--------------------------------------------------------------
Element Selector
1. Used to select HTML elements by its name
2. How to we do it:
	h1{
		color: red;
	}
(We selected the heading tag and then changed the color property i.e. text color to red. Now whatever it written in this tag(content) will have the text color as red)
--------------------------------------------------------------
Id Selectors
1. Id attribute is used to select HTML elements
2. Used to target specific or unique element
 #unique{
	color:green;
 }
 <p id="unqiue"> Hello, world!! </p>
 (We selected the id and then changed the color property i.e. text color to green. Now whatever it written in this tag(content) will have the text color as green)
--------------------------------------------------------------
Class Selector
1. Class attribute is used to select HTML element
2. Used to target specific class of element
.group{
	color: blue;
}
<p class="group"> Hello! </p>
 (We selected the class and then changed the color property i.e. text color to blue. Now whatever it written in this tag(content) will have the text color as blue)
--------------------------------------------------------------
 Universal Selector
1. Wild card character
2. Used to target specific all the elements
 *
 {
	color: yellow;
 }
 <h1> Hi </h1>
 <p> Bye </p>
 
(We selected all the elements and then changed the color property i.e. text color to yellow. Now whatever it written in all the tags(content) will have the text color as yellow)
-------------------------------------------------------------- 
Descendant Combinator Selector
1. Combine two or more selectors
2. How we do that :
	<div id="out">
		<div class="in"> Hiiiiiiiiiiiiiiiiiii </div>
	</div>
(We selected class inside id then changes the color property i.e. text color to purple. Now whatever is written (content) will have the text color as purple.)

#out in {
	color: "purple";
}
--------------------------------------------------------------
Child Combinator Selector
1. Combine two or more selectors like Descendant
2. It only targets the immediate child.
3. How we do that :
	<div id="out">
		<div class="in"> Hi </div>
	</div>
(We selected class inside id then changed the color property i.e text color to babygreen. Now whatever is written (content) will have the text color as babygreen.)

#out> .in {
	color: babygreen;

}
--------------------------------------------------------------
Pseudo-class Selector
1. Used to target state of elements
2. How we do that :
p : hover {
	color: babygreen;
}
<p> Pseudo-class Selector </p>
--------------------------------------------------------------

CSS Colors

There are different colouring schemes for CSS
Two widely used techniques are as follows :
	1. RGB 
		1.1 This starts with rgb and takes 3 parameters
		1.2 Three parameters basically corresponds to red, green and blue
		1.3 Value of each parameter may vary from 0 to 255
		1.4 Eg. rgb(255,0,0): means color red
	
	2. HEX
		2.1 Hex code starts with # and comprises of 6 numbers which further divided into 3 sets.
		2.2 Sets basically corresponds to Red, Green and Blue 
		2.3 A single set of value can vary from 00 to ff 
		2.4 Eg.#ff0000: means color red
	
