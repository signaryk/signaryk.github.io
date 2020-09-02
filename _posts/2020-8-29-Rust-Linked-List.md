---
layout: post
title: Adventures in Learning Rust
date: 2020-8-29
published: false
---
Part of my daily routine is to glance over the current top posts on Lobste.rs and Hacker News. There's always
at least a couple articles that catch my attention, and I invariably spend an hour or so reading the article
and the comments from users on the link aggregators. I've been a user for long enough to notice a pattern:
whenever a new release of Rust or Go comes out, there's always going to be a post about the new release,
and there will be some comment chain in that post devoted to comparing the two languages. 

This past December I started learning Go after I got interested in systems-level programming during one of my
CS classes the previous semester. Go, I found, would have been perfectly suited for one of the programming
assignments, and I can became especially interested in how easy Go made handling bounded buffers and transmitting
data across TCP. When I have some free time I plan to rewrite my solution to that assignment in Go.

Before I settled on Go, though, I had been debating learning either it or Rust. Both are fairly new programming
languages that have almost a cult following among the users of both Hacker News and Lobste.rs. One of the biggest
features touted of Rust is memory safety, especially in concurrent programs thanks to its unique ownership model.
Rust can be pretty daunting at first, though, as it can sometimes take a lot of effort just to get your program
to _compile_. What you'll find is that a big part of the compilation errors are really just related to Rust's
ownership model. You'll run into these errors a lot. **A lot**. It can be almost maddening how often your
program fails to compile because of some violation of the ownership system. That being said, when your code
_does_ finally compile, you'll be guaranteed that your code is memory safe. A pretty bold statement.

## Actually Learning Rust

My journey with Rust began with a GitHub repo called "Rust for C++ Developers" or something along those lines
(I'll admit, it's been awhile since I did that). Ultimately I ended up stopping because I was approaching the
language with the wrong attitude: I just wanted to translate my C++ skills to Rust as quickly as possible. Rust
takes time to learn, though, and this is not something that can be rushed. There's no analogue for the ownership
system in C++ (or Go, or Python, or any other language I've touched for that matter). I got discouraged the more
I ran up against ownership issues. 

A few weeks ago I discovered a new post on the front page of Lobste.rs: "Learning Rust with Entirely Too Many
Linked Lists". I was interested. We spent quite a bit of time implementing linked lists when I took a course in
data structures and algorithms a few 