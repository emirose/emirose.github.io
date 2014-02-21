---
layout: post
title:  "What school doesn't teach you about being a software developer"
date:   2014-02-20 23:38:09
categories: sofware 
---

I graduated from college pretty sure that I wanted to be a software
developer, but with very little idea about how software was actually
built. Recently I've had a few college students approach me about what
types of courses they should take to prepare them to be professional
software developers. I don't really have a course to recommend, but
there are plenty of things that I've learned since starting work at
ThoughtWorks 2.5 years ago. This post is an attempt to write down some
of the advice I've given to recent college grads. Here are some things
that you probably won't learn without actual software development
experience:

__Code is not just yours anymore__  
In school many programming projects are individual. Even team-based
projects tend to get divided up into silos.  As a real software
developer you are contributing to a code base as part of a team. To work
effectively with your team, it's better when everyone feels collective
ownership over the code.

__Code needs to be readable__  
When you're writing code for a school project deadline, you are
generally not thinking about maintaining it later since you'll never
have to. In the real world, you (or someone else) might be maintaining
the same code for years. More than just being efficient and functional,
your code needs to be readable and maintainable. You might think that
you'll always remember what that “x” on line 123 stands for, but trust
me, you won't and your teammates certainly won't. I think every
entry-level developer should read up on [Code Smells][code_smells]
and [Clean Code][clean_code].

__There's more to OOP than inheritance__  
The courses I took in college gave me a basic understanding of OOP.  But
when I started working in the software industry, I was surprised to find
out that inheritance is not always the best way to avoid code
duplication. [Composition][composition] is generally
favored because it allows for more flexibility in domain modeling.

__Tests are your friend__  
I vaguely knew what unit tests were when I graduated from college, but I
didn't really understand the point. Testing starts to make a lot more
sense once you've worked on a large software project with a whole team
of developers. I write much better code and spend a lot less time
tracking down bugs now that I understand testing. I don't necessarily
think that college students need to be TDD-ing
(http://en.wikipedia.org/wiki/Test-driven_development) all their
projects, but an introduction to the concept wouldn't be a bad idea.

So, in summary, I can't recommend any college courses that will
magically make a good software developer. A lot of things are easier to
learn outside of the classroom, but there are some widely accepted
industry practices, such as writing readable code and testing, that
students can start practicing regardless of whether their classes
require it.

[composition]: http://en.wikipedia.org/wiki/Composition_over_inheritance
[code_smells]: http://martinfowler.com/bliki/CodeSmell.html 
[clean_code]: http://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882
