# React Docs - Forms

1- What is a ‘Controlled Component’?

         one that takes its current value through props and notifies changes through callbacks like onChange 

2-Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

          yes becaues the setState function is async function.
         
3-How do we target what the user is entering if we have an event handler on an input field?

          
          set onChange event on the element thathandle the changes and set it to the state properties 
     

# The Conditional (Ternary) Operator Explained

1-Why would we use a ternary operator?


      Using a conditional, like an if statement, allows us to specify that a certain block of code should be executed if a certain condition is met.


2- Rewrite the following statement using a ternary statement:
         
         
         if(x===y){

           console.log(true);
              } else {
            console.log(false);
               }
            (x===y)? console.log('true') : 

        console.log('false');


    