# Lab 4: Into OOP and Polymorphism

## Intro

Hello there. Today we will extend a bit more your projects. We'll dive into polymorphism, another base concept of OOP.

This laboratory work is the third one in a series of 4 labs (`Lab 2`, `Lab 3`, -> `Lab 4`, `Lab 5`). All of them will represent one project that you'll improve step-by-step.

## Polymorphism

In this laboratory you have to improve your simulation by using polymorphism mechanisms provided by your programming language. You have to add abstractions using interfaces, to decouple the actual implementation and it's abstraction. This way you can make your program work with different entities sharing the same properties and methods, without need to know what's the actual type of that entity. Use abstract classes to separate some repeating logic in a parent class, but it shouldn't be instantiated, just extended. Use dependency injection when you need to instantiate a class inside of another one. If you need to call the same method but with different arguments, use overloading, of course if your language provides such a feature. Also, when you need to change a method's implementation in a child class,use method overwriting.

So, now you have to implement the scenarios/flow that will happen in your simulation. For example, if we take a restaurant, a scenario will be a client makes an order. But there will be many variations of it, like the kitchen fails to cook it, or waiter was late and so on. 

**Implement those scenarios separately, your project should not run as a simulation yet. Just a set o independently running scenarios of interaction between you objects.**

Let's recap:
* Create scenarios of your simulation.
* Run them separately and show the result as a text log.
* Use polymorphism principles.
* Describe the hierarchy in a `README` file and upload it to your remote repository.

## Allowed Tools

For this project you're allowed to use programming languages as:
* C++
* Java
* Kotlin
* C#
* Ruby

If you want to use something else, let's discuss it first.

## Grading

This laboratory work will be graded based on:
1. The number of scenarios implemented.
1. The complexity of scenarios.
1. The consistency of scenarios, i.e. how related the scenario is to the simulation.
1. Code styling.

## General Requirements

* Working in a Unix-based operating system.
* All operations (files and directories creating, compiling source code, creating git repository and committing changes and etc.) should be done **using command line exclusively**.
* Work should be done by yourself. **Plagiarism is penalized.**

## Deadline

**Time to complete:** _**1 week**_ since you receive the requirements \
_Each week_ of lateness will cost you minus _**1 point**_.

You can present just **one laboratory work per day**, so don't try to present all of them at the end. \
To be **admitted to midterm, you have to present all laboratories received before it**, so, again, don't procrastinate and ideally present one lab per week.

## Presentation

Write a `README` file where you describe your work done.
Upload your code to a remote repository and send the link to it to <alexandr.calugari@isa.utm.md> with subject including 'OOP Lab 3', **before the deadline**.
The presentations themselves will be offline at laboratory classes.

**Good Luck!**