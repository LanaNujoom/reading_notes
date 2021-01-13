# Class 12


## ANIMATED CHARTS

### Setting up

    <script src='Chart.min.js'></script>

### Drawing a line chart

    var buyerData = {
	labels : ["January","February","March","April","May","June"],
	datasets : [
		{
			fillColor : "rgba(172,194,132,0.4)",
			strokeColor : "#ACC26D",
			pointColor : "#fff",
			pointStrokeColor : "#9DB86D",
			data : [203,156,99,251,305,247]
		}
	]
}





### Drawing a pie chart
    
    var countries= document.getElementById("countries").getContext("2d");
            // draw pie chart
            new Chart(countries).Pie(pieData, pieOptions);
            // bar chart data
            var barData = {
                labels : ["January","February","March","April","May","June"],
                datasets : [
                    {
                        fillColor : "#48A497",
                        strokeColor : "#48A4D1",
                        data : [456,479,324,569,702,600]
                    },
                    {
                        fillColor : "rgba(73,188,170,0.4)",
                        strokeColor : "rgba(72,174,209,0.4)",
                        data : [364,504,605,400,345,320]
                    }
                ]
            }



![img](https://www.anychart.com/blog/wp-content/uploads/2017/10/AnyChart_JavaScript_chart_example_HTML5_app.png)


### The canvas element

    <canvas id="tutorial" width="150" height="150"></canvas>
    
    

![img](https://i.ytimg.com/vi/fqzaxdiRZS4/maxresdefault.jpg)
     
     
### Drawing shapes with canvas

**Drawing rectangles**

    fillRect(x, y, width, height)
*Draws a filled rectangle.*

       strokeRect(x, y, width, height)
*Draws a rectangular outline.*

    clearRect(x, y, width, height)
    
*Clears the specified rectangular area, making it fully transparent.*

### Drawing paths :

1. beginPath() Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.

2. Path methods Methods to set different paths for objects.

3. closePath() Adds a straight line to the path, going to the start of the current sub-path.

4. stroke() Draws the shape by stroking its outline.

5. fill() Draws a solid shape by filling the path's content area.

### Lines :

    lineTo() method.
    
 The starting point can also be changed by using the moveTo() method.

### Colors :

***fillStyle = color***
Sets the style used when filling shapes.
***strokeStyle = color***
Sets the style for shapes' outlines.

### Transparency :

**setting the globalAlpha property or by assigning a semi-transparent color to the stroke and/or fill style.**


### Line styles:

*properties :*

1. lineWidth = value / width of lines drawn in the future.

2. lineCap = type / appearance of the ends of lines.

3. lineJoin = type / appearance of the "corners" where lines meet.

4. miterLimit = value / limit on the miter when two lines join at a sharp angle.

5. getLineDash() / Returns the current line dash pattern array containing an even number of non-negative numbers.

6. setLineDash(segments) / current line dash pattern.

7. lineDashOffset = value /  start a dash array on a line.




### Drawing Test:

    fillText(text, x, y [, maxWidth])
    
   Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
   
    strokeText(text, x, y [, maxWidth])
    
   strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.
