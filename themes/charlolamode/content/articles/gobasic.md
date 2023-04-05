---
title: Golang
type: page
description: Logging my experience picking up Golang.
topic: programming
draft: false
---

## Intro

We all know Golang has been in his prime for about 5yrs and
picking it up is a good choice after a long ride with Python Picking
Golang was not an easy task for me or anyone coming from a
dynamically typed language though I had an ideal basic of C but
was poised with Golang or Rust Pitching myself to go with Golang
and let see how rough the terrain is……

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

### Day One (Hit the ground running....)

Golang error handling is top-notch NGL….. Noticed that the time it
takes to run a go file for the first time is usually much longer than
the repeated rerun and one of my suspicions is that as a compiled
language Golang makes it pattern behavior of C which you have to
compile it into a.out file before you can run a program, this cost
some secs but I’m still not impressed with the execution time
maybe I will find out along the way or it’s my windows machine
that is ditching the speed

### Control Stucture
