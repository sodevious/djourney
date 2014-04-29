---
layout: post
title:  "Python for Beginners II: Notes from the NYC Meetup"
date:   2014-04-29 00:28:53
categories: python notes
---

- Functions are reusable pieces of code
- `def` defines the function
- Any complex statement in python needs a colon
    def complex_statement():

- Functions take parameters 
- Arguments correspond to parameters (things in parenthesis)
- Parameters can be named so they can be used out of order
- Every function gets its own namespace which is separate from global variables
- Functions define namespaces (how you keep things from interfering from each other)
- add `global` before statement to define global variables
- in Python every function returns a value even if it doesn't have a return statement (aka, `None`)
- functions can return multiple values

- simple functions: single lines
- compound functions: next lines will be indented

- when talking about None, use `is None` not `== none`

- functions are opjexts

refer to a function by calling it without parenthesis
- lambda: there is no return value, defines a function without naming it

- classes define objects which have attributes(variables) and methods(functions)
- empty parenthesis: this is a class that doesn't extend on anything else
- `__init__` method = contstructor, has self parameter
