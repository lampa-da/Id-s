ID, please!
IDs, on the other hand, are great for when you have exactly one element that should receive a certain kind of styling.

IDs are assigned to HTML elements with the word id and an equals sign:

<div id="first"></div>
<div id="second"></div>
<p id="intro"></p>
IDs are identified in CSS with a pound sign (#):

#first {
    height: 50px;
}

#second {
    height: 100px;
}

#intro {
    color: #FF0000;
}
This allows you to apply style to a single instance of a selector, rather than all instances.
