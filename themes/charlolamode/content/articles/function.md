---
title: Funtions
type: page
description: Go functions; more than one function
topic: programming
---

### Variadic Funtions
This is a special form that allows another function to be called
with multiple intergers, _(which are known as variadic parameter)_
By using an ellipsis(...) before the type name of the last parameter,
you can as well indicate more parameters to take in.

This is precisely how the fmt.Println function is implemented:

`func Println(a...interface{}) (n int, err error)`

### Closure
Closure allows the ability to create a function inside a function,
a way to use is by writing a function that returns another function,
which when called generate a sequence of numbers

### Recursion
A function being able to call itself

Closure and Rcursion are powerful programming techniques that form the basis
of **functional programming**