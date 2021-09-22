Review, Research, and Discussion
How can we ensure that an effect hook runs only once?

useEffect will run when the component renders, which might be more times than you think, Hooks are used in function components. The Class component comparison to useEffect are the methods componentDidMount , componentDidUpdate , and componentWillUnmount.
Can useState() update more than one state variable at the same time?

Unlike the setState in class components, the setState returned from useState doesn't merge objects with existing state, it replaces the object entirely. You could combine the loading state and data state into one state object and then you could do one setState call and there will only be one render.
Is useState() synchronous?

Yes, setState() is asynchronous. React does not guarantee that the state changes are applied immediately. Think of setState() as a request rather than an immediate command to update the component.
Document the following Vocabulary Terms
State Hook: it returns both the latest state value and a function for updating the value that keeps React in the loop and lets it do its syncy business. We want to alert React that a value used within a component has changed so it can re-run the component and update the UI if necessary.
Component Lifecycle: Each component in React has a lifecycle which you can monitor and manipulate during its three main phases. The three phases are: Mounting, Updating, and Unmounting.
Preparation Materials
useReducer hook

An alternative to useState. Accepts a reducer of type (state, action) => newState, and returns the current state paired with a dispatch method. (If you’re familiar with Redux, you already know how this works.)
useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.
React doesn’t use the state = initialState argument convention popularized by Redux. The initial value sometimes needs to depend on props and so is specified from the Hook call instead. If you feel strongly about this, you can call useReducer(reducer, undefined, reducer) to emulate the Redux behavior, but it’s not encouraged.

Ultimate Guide to useReducer

useReducer is one of the additional Hooks that shipped with React 16.8. An alternative to the useState Hook, it helps you manage complex state logic in React applications. When combined with other Hooks like useContext, useReducer can be a good alternative to Redux or MobX — indeed, it can sometimes be an outright better option.
This is not to knock Redux and MobX, as they are usually the best options to manage global state in large React applications. But more often than necessary, many React developers jump into these third-party state management libraries when they could have effectively handled their state with Hooks.

How does useReducer work?
useReducer is used to store and update states, just like the useState Hook. It accepts a reducer function as its first parameter and the initial state as the second.
useReducer returns an array that holds the current state value and a dispatch function, to which you can pass an action and later invoke. This is similar to the pattern Redux uses but with a few differences.