# Code 301 - Intermediate Software Development

## Class 03 - Passing Functions as Props

Block intro

> Gentlemen, you can’t fight in here. This is the war room. — President Merkin Muffley

### React Docs - Lists and Keys ([Article](https://reactjs.org/docs/lists-and-keys.html))

* What does .map() return?
* If I want to loop through an array and display each value in JSX, how do I do that in React?
* Each list item needs a unique ____.
* What is the purpose of a key?

```.map()``` returns an array.
Rendering items in an unordered or ordered list via a function
They need a unique key, at least among siblings.
The purpose is to give the elements a stable identity. As variables and objects get swapped into arrays or reordered or manipulated by functions or user imputs, the key is essential to maintain stability.

### The Spread Operator ([Article](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab))

* What is the spread operator?
* List 4 things that the spread operator can do.
* Give an example of using the spread operator to combine two arrays.
* Give an example of using the spread operator to add a new item to an array.
* Give an example of using the spread operator to combine two objects into one.

The spread operator is ```...```.
There are several things it is used for:
* Copying an array
* Using Math fucntions
* Adding items to a list
* Adding to state in React <--

An example of combining two arrays:

```
const array01 = [1, 3, 5];
const array02 = [2, 4, 6];
const comboArray = [...array01,...array02];
```

An example of add new item to array:

```
const array03 = [5,7,9];
const arrayAdd = [11,13,15, ...array03];
```

An example of combining two objects into one:

```
const object01 = {'hola'};
const object02 = {'hasta luego};
const object03 = {...object01,...object02,'hasta manana'};
```

### Videos

 ([React - How to Pass Functions between Components - Episode 22](https://www.youtube.com/watch?v=c05OL7XbwXU))

* In the video, what is the first step that the developer does to pass functions between components?
* In your own words, what does the increment function do?
* How can you pass a method from a parent component into a child component?
* How does the child component invoke a method that was passed to it from a parent component?

1. The developer creates a function at the same level as the state he is attempting to update.
1. The increment method at the App level updates the count attribute in the object at the App level. The increment at the person level sets the state at the person level to display the update tag and to push the change in count to the App level.
1. To pass the method to the child is through the ```.props```.
1. The child invokes the method through the person level increment method to call the parent method of increment as it was passed as a prop for Person

### Skim Articles

1. ([React Tutorial through 'Declaring a Winner'](https://reactjs.org/tutorial/tutorial.html))
1. ([React Docs - Lifting State Up](https://reactjs.org/docs/lifting-state-up.html))

### Things I want to know more about

* Should ebe interesting to see an example of the spread operator in an app, functioning.

Go [Home](index.md)