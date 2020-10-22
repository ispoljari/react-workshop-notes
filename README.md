# react-workshop-notes
Class Notes for the Jobfair React Workshop

The goal of the workshop is to introduce students to the basic concepts of React by implementing features on a real app.

The live version of the app can be found here: [Explore Comsysto Reply](https://csb-6twv6-71kwkht7u.vercel.app/)

# About React

**Declarative**

React makes it painless to create interactive UIs. Design simple views for each state in your application, and React will efficiently update and render just the right components when your data changes. Declarative views make your code more predictable and easier to debug.

**Component-Based**

Build encapsulated components that manage their own state, then compose them to make complex UIs. Since component logic is written in JavaScript instead of templates, you can easily pass rich data through your app and keep state out of the DOM.

**Top-Down Data Flow (Unidirectional)**

Data flows from parent to children components

[React Class Lifecycle](https://miro.medium.com/max/4560/1*EnuAy1kb9nOcFuIzM49Srw.png)

[React Hooks Lyfecyle](https://repository-images.githubusercontent.com/196048036/cc006f00-a420-11e9-99a6-d0bdf5f0c7bb)

*Disclaimer* 

The Mental model for hooks is similar to the mental model for class component lifecycle only on the surface, and when considering more complex use cases the analogy starts to break down. But, this is a more advanced topic. (For the curious: https://iqkui.com/a-complete-guide-to-useeffect/)

# Useful Cheatsheets and Documentation

- [JSX](https://reactjs.org/docs/introducing-jsx.html)
- [ES6 Javascript](https://devhints.io/es6)
- [Thinking in React](https://reactjs.org/docs/thinking-in-react.html)
- [React Cheetsheet](https://devhints.io/react)
- [Props vs. State](https://github.com/uberVU/react-guide/blob/master/props-vs-state.md)

# Wireframes

[JobFair Workshop App Wireframes](https://balsamiq.cloud/sbxzk00/pbo0aag)

# Thinking In React

1) Break The UI Into A Component Hierarchy

2) Build A Static Version in React

3) Identify The Minimal (but complete) Representation Of UI State

4) Identify Where Your State Should Live

5) Add Inverse Data Flow
