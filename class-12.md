## What is HTML Canvas?

element is used to draw graphics, on the fly, via scripting (usually JavaScript).

Canvas has several methods for drawing paths, boxes, circles, text, and adding images.

The <canvas element must have an id attribute so it can be referred to by JavaScript.

The width and height attribute is necessary to define the size of the canvas.

![id](./image12/id.PNG)

## HTML Canvas Drawing

*  Find the Canvas Element

* Create a Drawing Object

* Draw on the Canvas

![drawing](./image12/2.PNG)

## HTML Canvas Coordinates

The HTML canvas is a two-dimensional grid, The upper-left corner of the canvas has the coordinates (0,0).

### Draw a Line

To draw a straight line on a canvas, use the following methods:

* moveTo(x,y) - defines the starting point of the line.
* lineTo(x,y) - defines the ending point of the line.

To actually draw the line, you must use one of the "ink" methods, like stroke().

![3](./image12/3.PNG)

### Draw a Circle

* beginPath() - begins a path .

* arc(x,y,r,startangle,endangle) - creates an arc/curve. To create a circle with arc(): Set start angle to 0 and end angle to 2*Math.PI. The x and y parameters define the x- and y-coordinates of the center of the circle. The r parameter defines the radius of the circle.

![4](./image12/4.PNG)

### HTML Canvas Gradients

Gradients can be used to fill rectangles, circles, lines, text, etc. Shapes on the canvas are not limited to solid colors.

There are two different types of gradients:

* createLinearGradient(x,y,x1,y1) - creates a linear gradient.

* createRadialGradient(x,y,r,x1,y1,r1) - creates a radial/circular gradient.

The **addColorStop()** method specifies the color stops, and its position along the gradient. Gradient positions can be anywhere between 0 to 1.

### Using createLinearGradient()

Create a linear gradient.

![5](./image12/5.PNG)

### Using createRadialGradient():

Create a radial/circular gradient.

![6](./image12/6.PNG)

### HTML Canvas Text

### Using fillText()

Set font to 30px "Arial" and write a filled text on the canvas.

![7](./image12/7.PNG)

### Using strokeText()

Set font to 30px "Arial" and write a text, with no fill, on the canvas:

![8](./image12/8.PNG)

### HTML Canvas Images

To draw an image on a canvas, use the following method:

* drawImage(image,x,y)

![9](./image12/9.PNG)










