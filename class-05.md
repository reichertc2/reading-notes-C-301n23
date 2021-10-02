# Code 301 - Intermediate Software Development

## Class 05 - Putting it all Together

Block intro

> I love it when a plan comes together - John "Hannibal" Smith

### React Docs - Thinking in React ([Article](https://reactjs.org/docs/thinking-in-react.html))

* What is the **single responsibility principle** and how does it apply to components?
* What does it mean to build a ‘static’ version of your application?
* Once you have a static application, what do you need to add?
* What are the three questions you can ask to determine if something is state?
* How can you identify where state needs to live?

The single responsibility principle is a idea that all components should have one specialized task. It applies to components, if  a component becomes too robust or performs too many tasks it should be distilled into smaller sub components.
Static version implies the application is completely visuble from a UI standpoint. The interactivity of the site is not written in this version. It simply removes the manipulation of state and some methods.
The fallowing action after building a static version is to clarify the minimal representation of the user interface state. I.E. map out how the UI will perform.
Here are the three questions to ask oneself to verify if it is state:

* Is it passed in from a parent via props?
* Does it remain unchanged over time?
* Can you compute it based on any other state or props in your component?

The location of the state requiring manipulation is determined by the lowest common component. In which the state requires manipulation.

### Higher-Order Functions ([Article](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK))

* What is a “higher-order function”?
* Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
* Explain how either map or reduce operates, with regards to higher-order functions.

Higher order functions are used in other functions. I.E. ```.forEach()```.
It returns the vairable 'm' if it is greater than 'n'
Reduce essentially collapses a numerical array by summing it parts.

### Things I want to know more about

* I would like to know how the bulk of the higher order functions are used in practical applications. Like those i've seen like .```.forEach()``` and ```.map()```.

Go [Home](index.md)