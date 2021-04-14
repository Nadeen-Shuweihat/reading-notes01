
# Chapter 7 
## Forms

* to collect information from visitors 

* there are several types of forms such as :
    - adding text
    - choices
    - uploading files

* How does it work ?

    1- fill the form

    2- the name is sent to the server

    3- processing time 

    4- create a new page 


* form Structure :
    <form action - "url" mention -"get">


* user name and password structure :

    < form action="http://www.example.com/login.php">

        < p>Username:

             < input type="text" name="username" size="15"

              maxlength="30" />

        < /p>

        < p>Password:

             < input type="password" name="password" size="15"

             maxlength="30" />

        </ p>

    </ form>


* text area Structure :

    < form action="http://www.example.com/comments.php">

         < p>What did you think of this gig?< /p>

        < textarea name="comments" cols="20" rows="4">Enter

           your comments...</ textarea>
  
        </ form>

And you can try creating many more things that are related to the forms such as checkbox, drop down list box, multiple select box, file input box, submit button , email , search box ...etc 


# Chapter 14
## lists tables and forms

- list-style-type
   (applied to the < ol >, < ul>, and < li>)

   * we can add an image style 
    
    ![im](https://forum.blocsapp.com/uploads/db8018/original/1X/cd4490dc503feaf572d1cd1570e25ecd86bdb87f.png)

- list-style-position
    (outside or outside the text box)
 

- table properties 

   * width
   * padding
   * text-transform
   * letter-spacing
   * font siza
   * text aligh
   * border top and bottom
   * backgroung color
   * hover
   * align numerial
   * shade alternate row
   * give cells padding

   ![ouu](https://stuyhsdesign.files.wordpress.com/2016/02/properties.png)

- to show or hide borders to empty cell we can use
    
    * show
    * hide 
    * inherit

- to control the gap ti the empty cells use :

    * border spacing
    * border collapse

- we can style the input text , the submit buttom and the fieldsheet by using 

    * color 
    * background color
    * font size
    * border
    * padding


# Chapter 6
## events

- " Events are the browser's way of indicating when something has happened (such as when a page has finished loading or a button has been clicked)." - javascript and jquery interactive book

* types of events :

    ![dd](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/07/JavaScript-Event-Types.jpg)

    

- how it works ??

     ![ds](https://www.rose-hulman.edu/class/cs/csse290-WebProgramming/201330/Slides/images/figure_3_event.png)




- event occurs on an element the webpage changes due to the function so an interaction happens with the user 


     ![df](https://miro.medium.com/max/513/1*3-9o5uejTRLGvco0M8eIiA.png)




- most commonly used events are W3C DOM