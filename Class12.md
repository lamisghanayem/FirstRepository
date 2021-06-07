#  Chart.js

### a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. It’s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.

## Drawing a line chart
1. To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart.

2. we need to write a script that will retrieve the context of the canvas, so add this to the foot of your body element.

3. Inside the same script tags we need to create our data, in this instance it’s an object that contains labels for the base of our chart and datasets to describe the values on the chart.

# canvas element

#### the canvas element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high.
#### The canvas element can be styled just like any normal image (margin, border, background…). These rules, however, don't affect the actual drawing on the canvas.
 #### The canvas element has a method called getContext(), used to obtain the rendering context and its drawing functions.