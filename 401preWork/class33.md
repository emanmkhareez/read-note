<Login /> and <Auth />
Review, Research, and Discussion
Why is the Context API useful?
Context API is easy to is use as it has a short learning curve. It requires less code, and because there's no need of extra libraries, bundle sizes are reduced.
Can a component outside of a provider get its context?
No, react context is available only when the UI is available. This means that on background tasks you can't access it. But that doesn't mean that you can't access it "outside" of components.
What are some common use cases for using the Context API?
Theming — Pass down app themei18n — Pass down translation messagesAuthentication — Pass down current authenticated user.
Describe “Context Hell”?
The React Context hell is the nasty code you get taking advantage of the React Context API.
Document the following Vocabulary Terms
global state: a global state is a set of local states which are all concurrent with each other, a global state in the time domain is also a global state in the causal domain; if two states occur simultaneously, then they cannot have any cause-effect relationship.
global context: is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language. For example, in the code below we manually thread through a “theme” prop in order to style the Button component: class App extends React
provider: The Provider component is what makes the state available to all children components no matter how deeply nested they are.
consumer: The Consumer component allows a React component to subscribe to the context changes. The component makes the data available using a render prop.
Preparation Materials
what is role based access control?

Role-based access control (RBAC) restricts network access based on a person's role within an organization and has become one of the main methods for advanced access control. The roles in RBAC refer to the levels of access that employees have to the network.

EXAMPLES OF ROLE-BASED ACCESS CONTROL - Some of the designations in an RBAC tool can include:

Management role scope – it limits what objects the role group is allowed to manage.
Management role group – you can add and remove members.
Management role – these are the types of tasks that can be performed by a specific role group.
Management role assignment – this links a role to a role group.
BENEFITS OF RBAC:

Reducing administrative work and IT support.
Maximizing operational efficiency.
Improving compliance.
react-cookies component
- API
react-cookie library
- API