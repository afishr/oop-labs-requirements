# Lab 3: Into OOP and Inheritance

## Intro

How do you do, fellow kids? This laboratory work is the continuation of the previous. Here you have to broaden your existing set of actors in the simulation.

This laboratory work is the second one in a series of 4 labs (`Lab 2`, -> `Lab 3`, `Lab 4`, `Lab 5`). All of them will represent one project that you'll improve step-by-step.

## Inheritance

Here you have to extend your existing classes using inheritance. You have to create an hierarchy of your entities. Create superclasses that will be extended by concrete classes, to separate some common logic. Use access modifiers to see how you can manage the visibility of class properties and methods. Define abstract classes if the superclass is not supposed to be instantiated. Override methods in concrete classes when you need to define a different behavior from the parent class.

For this laboratory work try the concept of some OOP oriented languages where `everything is an object`, so every class provided by standard library is a descendent of a common-to-all class, typically called `Object`. So, try to think how to tie all your actors in the simulation to be descendent of one general class, `Actor`/`Entity`, call it whatever you want. You can take any number of intermediary levels, don't inherit `Driver` directly from root object, at least add an intermediary level as `Person`, to group it.

**For the presentation you have to draw a diagram depicting the hierarchy of your system and describe it in a README file.**

Let's recap:
* Create and hierarchy of all your classes being inherited from one root class.
* Draw a diagram of your classes.
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
1. The complexity of your hierarchy.
1. The consistency of your hierarchy.
1. The class hierarchy diagram.
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

Write a `README` file where you describe your hierarchy, what objects you defined, what logic they implement and draw a class diagram.
Upload your code to a remote repository and send the link to it to <alexandr.calugari@isa.utm.md> with subject including 'OOP Lab 3', **before the deadline**.
The presentations themselves will be offline at laboratory classes.

**Good Luck!**