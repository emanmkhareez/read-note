# chart:way to display data this way make understand data quickly 

to use chart in javascript must download  Chart.js.

To draw a line chart-->create a canvas element in our HTM.

Next, we need to write a script that will retrieve the context of the canvas, so add this to the foot of your body element:

difference between canvas and image the canvas does not have src attributedifference between canvas and image the canvas does not have src attribute.

 element has only two attributes, width and height  ***the canvas will initially be 300 pixels wide and 150 pixels high***.

 When no styling rules are applied to the canvas it will initially be fully transparent.

 You should always provide fallback content to be displayed by those browsers.

 canvas must have closing tag

 ## Drawing shapes with canvas.


Unlike SVG, canvas only supports two primitive shapes: rectangles and paths All other shapes must be created by combining one or more paths.

The fillRect() function draws a large black square 100 pixels on each side.

The clearRect() function then erases a 60x60 pixel square from the center.

 strokeRect() is called to create a rectangular outline 50x50 pixels within the cleared square.