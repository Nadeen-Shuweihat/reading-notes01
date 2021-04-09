## images

- (self closing tags)

* image tag < img src = " url " alt  = " content " title = " text " />
    - img (starting element of the tag)
    - src (source for the image)
    - alt (a text description if you cannot see the image)
    - title (attributes you can to the img element)

- we can resize the images by giving it the hieght and width we want 

- example of 3 places to place the image 
 
  + before a paragraph (the text will be under the image)
     < img /> 
     < p >        < /p >
  
  - inside the start of the paragraph (the paragraph starts with an image and next to it the texts)
     < p >  < img />           < /p >
 
  + in the middle of the paragrapgh
     

* aligning horizontaly (left and right)

* aligning vertically (top , middle and bottom)


## colors 

- 3 ways to specify color in css :

      1- RGB

      2- HEX code 

      3- color names

- there are 3 main colors that all the others colors are made from them (red green blue - RGB)
 ( are expressed between the numbers 0-255)

 * every color can also have hue , saturation and brightness 

 * when picking the colors we need to make sure that there is enough contrast between the background and the foreground
    - high contrast : makes the text easier to read 
    - low contrast : makes the text harder to read 
    - meduim contrast : for long spans of text makes it more readable 

-  the opacity 
   (allows you to specify the opacity of the child color that was made from mixing 2 colors )
   ( its is expressed between the number 0-1)


- CSS3 hsl color

   there are 3 ways to identify colors in css3 :

       - hue : represented as a color circle where the angle represent the color (values from 0-360)
       - saturation : the amount of grey in the color and it's represented as a percentage 
       - lightness : the amout of white or black in the color , represented as a percentage 0% lightness is black 100% lightness is white 
              ( also referred to as luminosity)





## texts 

- typeface terminology
    
    1- serif (used in printing easier to read )

    2- sans-serif (clearer to read inthe screen)

    3- monospace (used for code because they align nicely )

    4- cursive (joining strokes such as handwriting style)

    5- fantasy (decorative fonts used for titles)


- specifying typeface 
   
   1- font-family (type face that should be used )

   2- font-size (pixel,percentage,ems)

   3- font-weight (bold,normal)

   4- font-style (italic,oblique,normal)

   5- text-transform (uppercase,lowercase,capitalize)

   6- text-decoration (none,underline,overline,line-through,blink)

   7- letter spacing and word spacing 

   8- text-align (left,right,center,justify)

   9- vertical-align (baseline,sub,super,top,middle,bottom)

   
## JPEG vs PNG vs GIF blog

- Jpeg 

   * used fo images that contains natural scenes or a wide variation of colors

   * a loosy compression that it can achive compression ration of 1:10 without losing the quality

   * doesn't support transparency

   * can support up to 16 million colors

- Png

   * used for images with texts and objects with sharp contrast edges 

   * loosless image format , would retain higher quality than an image than JPEG and would look a lot sharper, it would also occupy more space on the disk

   * support transparency in 2 ways (insetring alpha channel or declaring a single color as a trasparent)

   * have 2 modes (png8 -can support up to 256 colors,used for simple shapes  and png24 - can handle up to 16 million colors,used for complex shapes )

- Gif

  * for images that contain animations

  * a lossless image format , uses LZW compression algorithm ,now mainly used only if the image contains animations

  * support transparency by declaring a single colour in the colour palette as transparent , is unsuitable for images with transparent backgrounds

  * limited to 256 colours, one of these 256 colours is assigned as transparent and the remaining 255 are used for other colours

  



