# Code 301 - Intermediate Software Development

## Class 02 - Intro to React and Components

Block intro

> Life is either a daring adventure or nothing at all - Helen Keller

### React Lifecycle ([Article](https://www.tutorialspoint.com/software_architecture_design/component_based_architecture.htm))

* Based off the diagram, what happens first, the 'render' or the 'componentDidMount'?
* What is the very first thing to happen in the lifecylce of React?
* Put the following things in the order that they happen:
    * ```componentDidMount```
    * ```render```
    * ```constructor```
    * ```componentWillUnmount```
    * ```React Updates```
* What does componentDidMount do?

In the phasing displayed in the diagram render occurs in the render phase prior t the componentDisMount which occurs after in the commit phase.

In the lifecycle of React the first thing that occurs is the mounting of the components.

The correct order is:
* ```constructor```
* ```render```
* ```React Updates```
* ```componentDidMount```
* ```componentWillUnmount```

### React Bootstrap Documentation ([Article](https://react-bootstrap.github.io/))

### Netlify ([Article](https://www.netlify.com/))

### Videos

 ([React State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI))

* What types of things can you pass in the props?
* What is the big difference between props and state?
* When do we re-render our application?
* What are some examples of things that we could store in state?

Props that can be passed through are hard coded items, like: images, text, urls, etc.
Props is passed through from a parent component and a state is inherent in the component
The app rerenders when the user has interacted with the specific component, it does not rerender all components.
Some items that are stored in a state are number of clicks, favoriting, etc.

### Skim Articles

1. ([React Docs - State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html))
1. ([React - Docs - handling events](https://reactjs.org/docs/handling-events.html))
1. ([React Tutorial through 'Developer Tools'](https://reactjs.org/tutorial/tutorial.html))

### Things I want to know more about

* Explore more on component building and rendereing in bootstrap.

Go [Home](index.md)