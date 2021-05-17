# React 

Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’? render first after that componentDidMount

 static getDerivedStateFromProps() The static getDerivedStateFromProps is the first React lifecycle method to be invoked during the updating phase

 Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
What does componentDidMount do?

constructor

componentWillUnmount

render

componentDidMount

 React Updates

  
  What types of things can you pass in the props?  strings 

What is the big difference between props and state?

  "props" (short for "properties") is an object of arbitrary inputs a React function component accepts as the first argument. "state" is data that changes over the lifetime of a specific instance of a React component.

What are some examples of things that we could store in state?


  he State of a component is an object that holds some information that may change over the lifetime of the component. For example, let us think of the clock that we created in this article, we were calling the render() method every second explicitly, but React provides a better way to achieve the same result and that is by using State, storing the value of time as a member of the component’s state. We will look into this more elaborately later in the article.


