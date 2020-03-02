# _Article:_
>- create a set of 3 graphs:
>> one will show the number of buyers (line chart)
>> the second will show which countries the customers come from (pie chart)
>> use a bar chart to show profit over the period.
* The great things about Chart.js are that it’s simple to use and really very flexible.

 ***The <canvas> element***
- it doesn't have the **src** and **alt** attributes.
- it has only two attributes, width and height. 
  - it will initially be 300 pixels wide and 150 pixels high.
  - If your renderings seem distorted, try specifying your width and height attributes explicitly in the <canvas> attributes, and not using CSS.
  * insert the alternate content inside the <canvas> element to Provid fallback content.
  * the <canvas> element requires the closing tag (</canvas>).
   >- There are three functions that draw rectangles on the canvas:
>> fillRect(x, y, width, height) // Draws a filled rectangle.
>> strokeRect(x, y, width, height) // Draws a rectangular outline.
>> clearRect(x, y, width, height) // Clears the specified rectangular area, making it fully transparent.
>- functions used to perform these steps:
  >> beginPath() // put Path methods
  >> closePath()
  >> stroke()
  >> fill()
  - moveTo(x, y): Moves the pen to the coordinates specified by x and y.
  * use the lineTo() method to drawing straight lines.
  - To draw arcs or circles, we use the arc() or arcTo() methods.
  * we can use: fillStyle and strokeStyle to hange thr colors.
  + Line styles:lineWidth = value, lineCap = type, lineJoin = type, miterLimit = value, getLineDash(), setLineDash(segments),         lineDashOffset = value.
  >- there are two methods to render text:
  >> fillText(text, x, y [, maxWidth])
  >> strokeText(text, x, y [, maxWidth])
  
  
  
  
  
  
  
  
  
