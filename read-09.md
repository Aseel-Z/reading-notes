# Functional Programming in Javascript

## What is functional programming?
> a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.

## Pure Functions
- functions that are determinsitic; returns the same value when given same arguments, and have no side effects (modifying a global object or a parameter passed by reference)
- >Any function that relies on a random number generator cannot be pure
- >mutability is discouraged in functional programming.
- >When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.

- > pure functions + immutable data = referential transparency

# Refactoring JavaScript for Performance and Readability

>  There are no absolutes when it comes to clean code — there's always an edge case.
- when refactoring code, keep readability, efficiency, and less repetition in mind.
- throwing an error can be useful for handling unexpected scenarios/errors so as to avoid getting undefined values.