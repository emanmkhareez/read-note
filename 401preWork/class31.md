Context API
Review, Research, and Discussion
Describe use cases useState() vs useReducer()
useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks
Why do custom hooks need the use prefix?
That can use hooks inside of it and contain a common stateful logic to be reused in other components.
What do custom hooks usually do?
Custom Hooks are a mechanism to reuse stateful logic (such as setting up a subscription and remembering the current value), but every time you use a custom Hook, all state and effects inside of it are fully isolated. How does a custom Hook get isolated state? Each call to a Hook gets isolated state.
Using any list of custom hooks, research and name one that you think will be useful in your applications
useScript
useClippy Describe how a hook that fetches API data might work
Document the following Vocabulary Terms
reducer: A reducer is a function that determines changes to an application's state. It uses the action it receives to determine this change. We have tools, like Redux, that help manage an application's state changes in a single store so that they behave consistently.
Preparation Materials
context api

In a typical React application, data is passed top-down (parent to child) via props, but such usage can be cumbersome for certain types of props (e.g. locale preference, UI theme) that are required by many components within an application. Context provides a way to share values like these between components without having to explicitly pass a prop through every level of the tree.

When to Use Context?? Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language. For example, in the code below we manually thread through a “theme” prop in order to style the Button component.

You can only subscribe to a single context using this API. If you need to read more than one see Consuming Multiple Contexts. If you are using the experimental public class fields syntax, you can use a static class field to initialize your contextType.

API

React.createContext
Context.Provider
Class.contextType
Context.Consumer
Context.displayName