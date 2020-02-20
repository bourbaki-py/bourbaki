# b∅∪ℝb∀ki

## Python on a firm foundation

From [wikipedia](https://en.wikipedia.org/wiki/Nicolas_Bourbaki):

> Nicolas Bourbaki (French pronunciation: ​[nikɔla buʁbaki]) is the collective pseudonym of a group of (mainly French) mathematicians. 
> Their aim is to reformulate mathematics on an extremely abstract and formal but self-contained basis in a series of books beginning in 1935. 
> With the goal of grounding all of mathematics on set theory, the group strives for rigour and generality. 
> Their work led to the discovery of several concepts and terminologies still used, and influenced modern branches of mathematics. 

What Nicolas Bourbaki did for mathematics, we aim to do for Python programming.

Types, introspection, and automatic code generation figure prominently in this program.

Reusability is held sacrosanct because "There should be one -- and preferably only one -- obvious way to do it."
Like a useful theorem, a useful computational abstraction should be invokable at will.
It need not be derived more than once.


## Submodules

- `bourbaki.regex` provides an interface for constructing arbitrarily complex 
regular expressions using standard Python syntax.
- `bourbaki.application` derives complete command line interfaces from standard python function and class definitions.
- `bourbaki.introspection` contains utilities for introspecting runtime python objects of various types, and is a major foundational package for many others in the bourbaki namespace.


## Homepage

All of the bourbaki submodules are maintained [here](https://github.com/bourbaki-py/)

In the spirit of the original Bourbaki group, contributions are welcome.
