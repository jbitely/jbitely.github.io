---
layout: post
title: Technical Debt and You.
---

At Hack Reactor, topics are divided into two day blocks known as sprints. Recently I worked on a sprint involving [Backbone.js](http://www.backbonejs.org). The specifics of Backbone aren't relevant to this topic, but it can be described as a framework for building JavaScript applications that separates various bits of functionality into modular sections. This particular sprint has a reputation amongst many HR students and staff of being troublesome and difficult to grasp. The sprint experience turned out to be a very smooth and positive one for me, and I credit a large portion of that experience to the work my partner and I put in before ever touching the keyboard.

There is a concept in programming known as [technical debt](https://en.wikipedia.org/wiki/Technical_debt). Briefly, technical debt is the idea that for any given project, there is some amount of work that must be done before the project is considered complete. As this work is left undone, interest accumulates (it becomes more difficult to implement changes and/or complete the work).

Essentially sometimes you have the chance to do something the quick and dirty way or the cleaner, better, slower way. Quick and dirty has obvious appeal &mdash stuff works, you can move on with life (or on to the next bug). Further into the lifespan of that project however, you may quickly end up in a dirty mess of code that is held together by the code equivalent of duct tape. Taking the extra time to implement something in a way that is easily maintainable and understandable by others (or by yourself the next time you look at it!) can result in greater overall efficiency.

For our Backbone sprint, my partner and I spent a considerable amount of time simply analyzing and discussing the codebase we were given. We used an [online whiteboard](http://www.awwapp.com) to draw out the various models, views, event listners, events, functions, and how they connected to and interacted with each other.

It can be very tempting during this process to start diving into the code during this process, especially in a time-limited situation. We resisted this urge until we were both confident that we had a solid, fundamental understanding of the code we had already been given. As we began to add in small features, we made sure to add them to whiteboard and to update any interactions.

One of the questions we found ourselves asking often was "where should this piece of code live?" Backbone involves a lot of modularization and separation of code, and it can be confusing to keep track of where everything goes. In almost every instance of this question, we were able to spend a short amount of time consulting our diagram and make a strongly educated guess at the answer. In addition to saving us a tremendous of time that might have been spent making mistakes and learning from trial and error, we were assured that we had a good understanding of what each new piece of code we were adding was contributing to the codebase and how it affected the existing code.

By actively minimizing our technical debt, we finished the basic requirements for this sprint faster than any previous topic I had worked on, and I was able to spend a considerable amount of time working on extra features. I left this sprint with a solid understanding of Backbone fundamentals and a strong appreciation for the value of taking time to analyze existing projects before beginning to work with them.

For additional excellent words on technical debt, see [Martin Fowler's post on the subject](http://martinfowler.com/bliki/TechnicalDebt.html).
