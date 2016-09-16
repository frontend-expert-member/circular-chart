# circular-chart

Raphael is a cross-browser JavaScript library that draws Vector graphics for web sites. It will use SVG for most browsers. 
Raphael JS is a lightweight and  flexible JavaScript framework that allows you to draw vector graphics in your browser as well.

Raphael is used by first creating an instance of the Raphael object, which manages the creation of the canvas. 

The following examples create a canvas that is 320 pixels wide and 200 pixels high:

<pre>

// top left of canvas at the viewport's 10,50 coordinate
var r = Raphael(10, 50, 320, 200); 

// top left of canvas at the  top left corner of the #example element (in elements where dir="ltr")
var r = Raphael(document.getElementById("example"), 320, 200);

// same as above
var r = Raphael("example", 320, 200);

</pre>

Once the Raphael object has been instantiated, its various drawing, resizing and animation methods may be called to build up a 
vector graphic.

Circular Graph Sample:

![alt tag](https://github.com/mramkumar-mani/circular-chart/blob/master/Circular-Graph.png)

Circular Animation Sample:

![alt tag](http://i.stack.imgur.com/BPEL4.png)
