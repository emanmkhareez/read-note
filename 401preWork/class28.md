Component Lifecycle
Review, Research, and Discussion
Why do we not need more .html pages in a multi-page React app?

A React app consists of a single HTML file index.html. The views are coded in JSX format as components, Because React is not designed to develop multi-page websites. So, we need to create multiple routes to handle multiple views. So, instead of creating more than one htnl page we use routes.
If we wanted a component to show up on every page, where would we put it and why?

Outside the <BrowserRouter/>
Inside the <BrowserRouter />, outside a <Route />
Inside a <Route />
What does routing do with the components that were rendered when a new route is requested?

React Router uses component structure to call components, which display the appropriate information. By preventing a page refresh, and using Router or Link, the flash of a white screen or blank page is prevented. This is one increasingly common way of having a more seamless user experience. React router also allows the user to utilize browser functionality like the back button and the refresh page while maintaining the correct view of the application.
What does props.children contain?

It contains an <img> that is receiving some props and then it is displaying {props.}, it simply means that the component will display whatever is included in between the opening and closing tags while invoking the component
How do useState() and this.setState() differ?

Unlike the setState method found in class components, useState does not automatically merge update objects. You can replicate this behavior by combining the function updater form with object spread syntax:
Document the following Vocabulary Terms
State Hook: it returns both the latest state value and a function for updating the value that keeps React in the loop and lets it do its syncy business. We want to alert React that a value used within a component has changed so it can re-run the component and update the UI if necessary.
Mounting and Un-Mounting:
Mounting is when React renders the component for the first time and actually builds the initial DOM from those instructions.
Un-Mounting : is the last function to be called immediately before the component is removed from the DOM. It is generally used to perform clean-up for any DOM-elements or timers created in componentWillMount . At a picnic, componentWillUnmount corresponds to just before you pick up your picnic blanket.
Preparation Materials
Using the Effect Hook

The Effect Hook lets you perform side effects in function components,there are two common kinds of side effects in React components: those that don’t require cleanup, and those that do.
What does useEffect do? By using this Hook, you tell React that your component needs to do something after render. React will remember the function you passed (we’ll refer to it as our “effect”), and call it later after performing the DOM updates. In this effect, we set the document title, but we could also perform data fetching or call some other imperative API.
Why did we return a function from our effect? This is the optional cleanup mechanism for effects. Every effect may return a function that cleans up after it. This lets us keep the logic for adding and removing subscriptions close to each other. They’re part of the same effect!