---
title: Reverse proxy; as load balancer
type: page
description: Experimenting with Golang
topic: programming
draft: false
---

## Proxy

Let's start by exploring what ==proxy== is an infra that makes a request on behalf of a client(machine)
**For Context**
When you want to visit **www.google.com**, a proxy can be set up to handle
sending the request on your behalf. As far as **google.com** is concerned the
proxy is the client
_This does not expose the actual client to the server(Anonymous)_
Its use case is generally for security purposes(blacklisting certain websites)
but also can be used for Logging & Caching also is a thing
![proxy](images/proxy.png)

## Reverse Proxy

With ==Reverse proxy==, which is the inverse(opposite) of proxy
where the client doesn't know the final destination of the request, this might
be confusing
**For Context**
From the example given above with **google.com** in the case of
reverse proxy the request sent from the client is handled by the reverse proxy
which will then direct the client request to another server(something like redirection)
which is unknown to the client though
And one of its uses case is Load balancing
![reverse proxy](images/reverse.png)

## Load Balancer

A load balancer is used to distribute a set of tasks over a set of resources
to make the overall processing more efficient
Load balancing can optimize the response time to avoid overloading nodes while
other nodes are left idle.
There are types of load balancers that I'm not going to dive more into load balancing
the main reason here is ==using Golang to build a Reverse proxy as a load balancer==

## Let's Explore
