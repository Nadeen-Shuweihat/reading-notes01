# Lists and Keys 

* What does .map() return?

       an array that contains the new values (returned one)

* If I want to loop through an array and display each value in JSX, how do I do that in React?

     use {}

* Each list item needs a unique ____.

     key

* What is the purpose of a key?  
 
    Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity - [source](https://reactjs.org/docs/lists-and-keys.html)

    

# The spread Operator 

* What is the spread operator?

      syntax for adding items ,combining and spreading an array 
       
* List 4 things that the spread operator can do.

     - Copying an array
     - Concatenating or combining arrays
     - Using Math functions
     - Using an array as arguments

* Give an example of using the spread operator to combine two arrays.

     let array1 = [' N','a','d'];
     let array2 = [' e','e','n'];

     let array3 = [...array1, ...array2];
     console.log(array3); // result: Nadeen

* Give an example of using the spread operator to add a new item to an array.

     let array1 = [' N','a',,'d'];
     let array2 = [...array1, ' e','e','n'];

     console.log(array2); // result: Nadeen

* Give an example of using the spread operator to combine two objects into one.

     const objectOne = {hello: "🤪"}
     const objectTwo = {world: "🐻"}
     const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
     console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
     const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
     objectFour.laugh() // 😂😂😂😂😂



# How to Pass Functions Between Components

* In the video, what is the first step that the developer does to pass functions between components?
     
     adding props
      
* In your own words, what does the increment function do?

     loop , check the state and then update 

* How can you pass a method from a parent component into a child component?
     
     ' this.props.increment '
     
* How does the child component invoke a method that was passed to it from a parent component?

    