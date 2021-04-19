## canvas element

- has 2 attributes (width ,height)

- default width and height 300*150 px

- fallback content (alternate content inside the < canvas > it depends on the browser if it support canvas it will run it other will ignore the tag )

- needs a closing tag

- has a method called getContext (rendering)

- grid (coordinate space)

- drawing rectangle :

       * fillRect(x, y, width, height)
             Draws a filled rectangle.
       * strokeRect(x, y, width, height)
             Draws a rectangular outline.
       * clearRect(x, y, width, height)
             Clears the specified rectangular area, making it fully transparent.

- drawing path (create path,drawing command,render):
        
    * beginPath()
          Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.
    * Path methods
        Methods to set different paths for objects.
    * closePath()
        Adds a straight line to the path, going to the start of the current sub-path.
    * stroke()
         Draws the shape by stroking its outline.
    * fill()
        Draws a solid shape by filling the path's content area.


- move the pen (moveTo(x, y))

- straight line drawing (lineTo(x, y))

- drawing arcs :
      
      * arc(x, y, radius, startAngle, endAngle, counterclockwise)
           Draws an arc which is centered at (x, y) position with radius r starting at startAngle and ending at endAngle going in the given direction indicated by counterclockwise (defaulting to clockwise).

      * arcTo(x1, y1, x2, y2, radius)
          Draws an arc with the given control points and radius, connected to the previous point by a straight line.


-  also drawing many more things such as ( quadratic curves , rectangle or make a comination)

- applying color :
     
     * fillStyle = color
           Sets the style used when filling shapes.
    * strokeStyle = color
       Sets the style for shapes' outlines.

- properties which allow us to style lines:

     * lineWidth = value
         Sets the width of lines drawn in the future.

     * lineCap = type
        Sets the appearance of the ends of lines.

     * lineJoin = type
      Sets the appearance of the "corners" where lines meet.

     * miterLimit = value
      Establishes a limit on the miter when two lines join at a sharp angle, to let you control how thick the junction becomes.

     * getLineDash()
       Returns the current line dash pattern array containing an even number of non-negative numbers.

     * setLineDash(segments)
       Sets the current line dash pattern.

     * lineDashOffset = value
       Specifies where to start a dash array on a line.

- you can add shadow and pattern 

![bv](https://mk0wittysparksm75pi6.kinstacdn.com/wp-content/uploads/2017/07/HTML-Canvas-Cheatsheet.png)