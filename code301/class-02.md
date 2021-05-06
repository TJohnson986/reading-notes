## Class 02 Reading Notes
[Home](https://tjohnson986.github.io/reading-notes/)

#### Table of Contents
1. React Lifecycle
1. React State vs. Props

#### React Lifecycle
- Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’? *Render*
- What is the very first thing to happen in the lifecycle of React? *A constructor in the Mounting phase*
- Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates *Constructor, render, React Updates, componentDidMount, componentWillUnmount*
- What does componentDidMount do? *Loads using a network request or initialze DOM.*

#### React State vs. Props
- What types of things can you pass in the props? *Much like arguments to a function*
- What is the big difference between props and state? *Props you pass into a component, State is handled within the component. Props is handled outside of component and has to be changed outside of the component.*
- When do we re-render our application? *When something as changed based on input*
- What are some examples of things that we could store in state? *Counts, form values*