# Code 301 - Intermediate Software Development

## Class 09 - Functional Programming

Block intro

> The warrior uses whatever is closest to hand. - Mako

### Functional Programming Concepts ([Article](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa))

* What is functional programming?
* What is a pure function and how do we know if something is a pure function?
* What are the benefits of a pure function?
* What is immutability?
* What is Referential transparency?

Accoriding to Wikipedia - Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.
A pure function is a deterministic. It doesn't return observable side-effects, according to the author.
The code is easier to test.
Immutability - Unchanging over time or unable to be changed, per the author.
Pure functions plus immutable data equals referential transparency.

### Node JS Tutorial for Beginners #6 - Modules and require() ([Video](https://www.youtube.com/watch?v=xHLd36QoS4k))

* What is a module?
* What does the word ‘require’ do?
* How do we bring another module into the file the we are working in?
* What do we have to do to make a module available?

A module is another javascript file.
Require brings in a file or package to the current file.
To access a module is to ```require('./fileName')```, if in local directory. File path is in string format.
To make a module available to another is ```module.exports = ${exported item}```

### Things I want to know more about

* I would like to breakout my server to modules, as it is difficult to follow as currently written.

Go [Home](index.md)