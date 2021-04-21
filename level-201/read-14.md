## 8 simple CSS3 transitions that will wow your users

- fade in 

        ( two steps: first, you set the initial state; next, you set the change, for example on hover)

- change color

      (by using hover also)

- grow box 

     (-webkit-transform: scale();
        -ms-transform: scale();
        transform: scale();)

- shrink box 

     (the same as growing the box but we need to play around with the scale)

- rotate elements

     (-webkit-transform: rotateZ(deg);
        -ms-transform: rotateZ(deg);
        transform: rotateZ(deg);)

- square to circle

      ( hover then we select border radious)

- inset border

     (box-shadow: inset 0 0 0 25px color)

- swing 

     (we need to move the element left and right then apply  -webkit-animation: swing 1s ease;
        animation: swing 1s ease;
        -webkit-animation-iteration-count: 1;
        animation-iteration-count: 1;)

- 3d shadow box

     (add a box of shadow then we move the elemnt on the x axis by  -webkit-transform: translateX(-3px);
        transform: translateX(-3px);)

## Transitions & Animations

- transition 

 ![dw](https://pbs.twimg.com/media/EfyxYgHWkAIExXW.jpg)
   
     (element must have a change in state,different styles must be identified for each state)

* to detirmine style use (pseudo classes) :
         
      + hover
      + active
      + target

     * 4 properties :
        
      + transition-property
      + transition-duration
      + transition-timing-function
      + transition-delay

![sf](https://slidetodoc.com/presentation_image_h/1fd8cb1b646419893cb21c4139329fcc/image-56.jpg)


- animation 

![sd](https://i.ytimg.com/vi/5-I6p3h75tQ/maxresdefault.jpg)


* properties : 

   ![sdf](https://slidetodoc.com/presentation_image_h/1fd8cb1b646419893cb21c4139329fcc/image-67.jpg)


* animation direction :

   ![ferf](https://blog.hubspot.com/hs-fs/hubfs/The%20Ultimate%20Guide%20to%20Animations%20in%20CSS-16.gif?width=600&name=The%20Ultimate%20Guide%20to%20Animations%20in%20CSS-16.gif)



* animation iteration :

   ![sdf](https://img.cloudygif.com/full/f9e5a1e7e7c47e12.gif)

* play state :

   ![dc](https://blog.hubspot.com/hs-fs/hubfs/The%20Ultimate%20Guide%20to%20Animations%20in%20CSS.gif?width=600&name=The%20Ultimate%20Guide%20to%20Animations%20in%20CSS.gif)


## transforms 

* The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.

![fr](https://d34b8fs2z18t5a.cloudfront.net/wp-content/uploads/2020/06/screencast-2020-06-19-16-52-23-3.gif)

* to get better idea on the transform [click here](https://www.youtube.com/watch?v=ypwVbSAAJ68)