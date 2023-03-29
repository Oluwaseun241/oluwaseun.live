---
title: Golang
type: page
description: Logging my experience picking up Golang.
topic: programming
draft: false
---

## Intro

We all know Golang has been in his prime for about 5yrs and picking it up is a good choice after a long ride with Python
Picking Golang was not an easy task for me or anyone actually coming from a dynamically typed language though i had an ideal basics of C but was poised with Golang or Rust
Picthing myself to go with Golang and let see how rough the terrain is......

### Basics

I noticed something don't know if it's good but Golang really go down with 0 and 1.
The way the strings are represented in byte (integer)

**For context**

```
package main

import "fmt"

func main() {
    fmt.Println("Hello, World"[1])
}
```
which returns `101` instead of `e` in case of Python

Another thing is about variable declaration with const and var but what caught my attention is assigning a variable which can be done in two ways

```
var x = 10
or
x := 10
```