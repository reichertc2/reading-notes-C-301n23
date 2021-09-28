# Code 301 - Intermediate Software Development

## Class 04 - React and Forms

Block intro

> I’m Going To Need Those TPS Reports ASAP. So, If You Could Do That, That’d Be Great... - Bill Lumbergh

### React Docs - Forms ([Article](https://reactjs.org/docs/forms.html))

* What is a ‘Controlled Component’?
* Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
* How do we target what the user is entering if we have an event handler on an input field?

A controlled component is a element which has a value is controlled by React.
The user response should be stored in the state when the user inputs them. As you can pass the information to other elements in the user interface at the same time.
We target the user entry by assigning the ```name``` attribute.

### The Conditional (Ternary) Operator Explained ([Article](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff))

* Why would we use a ternary operator?
* Rewrite the following statement using a ternary statement:

```
if(x===y){
  console.log(true);
  } else {
  console.log(false);
}
```

The written ternary operator is a simplified syntax that takes multiple lines of code of an truth or false statement, such as an ```if{}``` statement. It then simplifies down to one line.

The single line of code is ```((x===y) console.log(true) : console.log(false))```.

### Skim Articles

1. ([React Bootstrap - Forms](https://react-bootstrap.github.io/components/forms/))
1. ([React Docs - Conditional Rendering](https://reactjs.org/docs/conditional-rendering.html))

### Things I want to know more about

* I would like to know more on abbreviating lengthy code statements like arrow functions and ternary statements.

Go [Home](index.md)