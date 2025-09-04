---
title: two(makeSomething)
date: 2025-03-29
draft: true
description: An experiment of multiple Hugo sites on one server.
tags:
  - example
  - tag
---

# A Place to Make Things
## The Problem

I have a struggle inside my brain any time I decide it's time to make things. Whether or not the art is worth making, or the statement worth stating, or the photo worthy of attention. 

I feel as if it's time to resolve those feelings and get over it. So, to start the adventure, let's make a few websites. 

PART of the problem is that I am not afraid to reverse engineer something already built, but I am not very good at programming in the first place. I'm a network engineer, a photographer, what I am NOT, is a web developer. Keeping that in mind, let's keep it simple, robust within its means, and something that is responsive.

## The Solution

I've made a handful of decisions. One is that you don't need to scale your website to serve hundreds of thousands of customers. Two is that you don't need e-commerce. Three is that you want something to set and forget, maybe a blogging platform. 

## Caddy

Caddy is our web server of choice. This will make it easy to point to the different instances of Hugo. 

```
TK - install caddy
```

## Hugo

Hugo is our website builder. There's not much to talk about other than it's the best static website builder I've found in recent history. 
