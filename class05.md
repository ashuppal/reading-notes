**Read: class 05**

This topic is important as understanding what components you need, where they live, who owns the states and functions is extremely important to understand if 
you are trying to build a site which is responsive and have clean code.

**React Docs - Thinking in React**

What is the single responsibility principle and how does it apply to components?
The single responsibility principle is that a component should ideally only do one thing. 
If it ends up growing, it should be decomposed into smaller subcomponents.

What does it mean to build a ‘static’ version of your application?
Static applications and websites render in the user's browser without the need for server side processing, 
this means that all the rendering of HTML, CSS, and JavaScript is done on the client side, rather then relying on server side technologies.

Once you have a static application, what do you need to add?
Once you have a statuc application, you need to add states to add interactivity and pass props between the components.

What are the three questions you can ask to determine if something is state?
The three questions you can ask are:
1. Is it passed in from a parent via props? If so, it probably isn’t state.
2. Does it remain unchanged over time? If so, it probably isn’t state.
3. Can you compute it based on any other state or props in your component? If so, it isn’t state.

How can you identify where state needs to live?
For each piece of state in your application:
1. Identify every component that renders something based on that state.
2. ind a common owner component (a single component above all the components that need the state in the hierarchy).
3. Either the common owner or another component higher up in the hierarchy should own the state.
4. If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.


**Higher-Order Functions**

What is a “higher-order function”?
Functions that operate on other functions, either by taking them as arguments or by returning them, are called higher-order functions.

Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
The greater than function is evaluating if the given argument returns truthy or falsey value based on the callback function.

Explain how either map or reduce operates, with regards to higher-order functions.
The **map** method transforms an array by applying a function to all of its elements and building a new array from the returned values. 
The new array will have the same length as the input array, but its content will have been mapped to a new form by the function.
The **reduce** method builds a value by repeatedly taking a single element from the array and combining it with the current value. 

##Things I want to learn more about

I need to understand states in more detail.How the passing of props works and how to build a component hierarchy before introducing states.





