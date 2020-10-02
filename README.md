<h1> CSS-Guide</h1>
This repo guides you through the world of CSS programming

The following webiste provides you with a great overview of CSS<br>
https://www.w3schools.com/css/

<br>
<h2>CSS</h2>

<h3>CSS position</h3>

The position property specifies the type of positioning method used for an element.
There are five position values<br>
<h4>Static</h4>
Static positioned elements are not affected by the top, bottom, left and right properties. <br>
An element with 'position: static;' is not positioned in any special way; it is always positioned according to the normal flow of the page.<br>

<h4>Relative</h4>
An element with 'position: relative;' is positioned relative to its normal position. <br>
Setting the top, right, bottom and left properties of a relatively-positioned element will cause it to be adjusted away from its normal position. Other content will not be adjusted to fit into any gap left bt the element. <br>
<h4>Fixed</h4>
An element with 'position: fixed;' is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled. The top, right, bottom and left properties are used to position the element. <br>
A fixed element does not leave a gap in the page where it would normaly have been located. <br>
<h4>Absoloute</h4>
An element which 'position: absoloute;' is positioned relative to the nearest positioned ancestor (instead of positioned relative to the viewport, like fixed). <br>
However; if an abosute positioned element has no positioned ancestors, if uses the document body, and moves along with page sscrolling. <br>
<h4>Sticky</h4>
An element with 'position: sticky;' is positioned based on the user's scroll position. <br>
A sticky element toggles between relative and fixed, depending on the scroll position. It is positioned relative until a given offset position is met in the viewport - then it "sticks" in place (like positione: fixed) <br>
