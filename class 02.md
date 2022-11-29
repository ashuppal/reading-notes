This topic is important as states and props help us build a code which is manageble and helpful for building applications.

**React lifecycle**

Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
‘componentDidMount’ method is invoked immediately after a component is mounted.

What is the very first thing to happen in the lifecycle of React?
"Mounting" is the first thing that happens in the lifecyle of React.

Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
constructor, componentDidMount,render,componentWillUnmount,React Updates

What does componentDidMount do?
This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, 
it should go here. This method is a good place to set up any subscriptions.

**React State Vs Props**

What types of things can you pass in the props?
You can pass any JavaScript value through props, including objects, arrays, and functions.

What is the big difference between props and state?(credit: stackoverflow)
The key difference between props and state is that state is internal and controlled by the component itself while props are external and controlled by whatever renders the component.

When do we re-render our application?
React components automatically re-render whenever there is a change in their state or props.

What are some examples of things that we could store in state?
States can be used for storing data which may be a string , number or any complex object .

###Things I want to learn about###
Creating custom components and using destructring method for props.
