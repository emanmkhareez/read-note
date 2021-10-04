Redux - Combined Reducers
Review, Research, and Discussion
Why choose Redux instead of the Context API for global state?
Context API is easy to is use as it has a short learning curve. It requires less code, and because there's no need of extra libraries, bundle sizes are reduced. Redux on the other hand requires adding more libraries to the application bundle. The syntax is complex and extensive creating unnecessary work and complexity
What is the purpose of a reducer?
It uses the action it receives to determine this change. We have tools, like Redux, that help manage an application's state changes in a single store so that they behave consistently
What does an action contain?
two keys and their values. The state update that happens in the reducer is always dependent on the value of action.
Why do we need to copy the state in a reducer?
is a way to describe the unchanged part.
Document the following Vocabulary Terms
immutable state: is an object whose state cannot be modified after it is created.
time travel in redux: is the ability to move back and forth among the previous states of an application and view the results in real time. With Redux, given a specific state and a specific action, the next state of the application is always exactly the same.
action creator: is a function that literally creates an action object. In Redux, action creators simply return an action object and pass the argument value if necessary.
reducer: is a function that determines changes to an application's state. It uses the action it receives to determine this change. ... Redux relies heavily on reducer functions that take the previous state and an action in order to execute the next state.
dispatch: A store holds the whole state tree of the application, the only way to change the state inside it is to dispatch an action on it.
Preparation Materials
Using combineReducers

The most common state shape for a Redux app is a plain Javascript object containing "slices" of domain-specific data at each top-level key. Similarly, the most common approach to writing reducer logic for that state shape is to have "slice reducer" functions, each with the same (state, action) signature, and each responsible for managing all updates to that specific slice of state. Multiple slice reducers can respond to the same action, independently update their own slice as needed, and the updated slices are combined into the new state object.

Because this pattern is so common, Redux provides the combineReducers utility to implement that behavior. It is an example of a higher-order reducer, which takes an object full of slice reducer functions, and returns a new reducer function.

Combined Reducer Syntax

The combineReducers helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore.

The resulting reducer calls every child reducer, and gathers their results into a single state object. The state produced by combineReducers() namespaces the states of each reducer under their keys as passed to combineReducers()