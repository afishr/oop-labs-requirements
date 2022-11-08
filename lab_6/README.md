# Lab 6: Architecture and SOLID

## Intro

Hi, it's been a while. In this laboratory work we'll focus on organization of your code. You have to polish your projects, separate the code, put all your building block in a correct way from architectural perspective.

This laboratory work is the fifth one in the series (`Lab 2`, `Lab 3`, `Lab 4`, `Lab 5`, -> `Lab 6`, `...Lab 7?`).

## Refactoring

Any project on its timeline sometime hits the points when it requires refactoring. We will artificially bring this moment in this laboratory work. The main purpose of refactoring is to fight technical debt. It transforms a mess into clean code and simple design.

* Clean code is obvious for other programmers.
* Clean code doesn’t contain duplication.
* Clean code contains a minimal number of classes and other moving parts.
* Clean code passes all tests.
* Clean code is easier and cheaper to maintain!

To achieve this, we recommend to **introduce SOLID principles in your project**. It stands for

* Single-responsibility principle (SRP)
* Open-closed principle (OCP)
* Liskov substitution principle (LSP)
* Interface segregation principle (ISP)
* Dependency inversion Principle (DIP)

On the other hand, you have to **introduce architectural patterns**. An architectural pattern is a general, reusable solution to a commonly occurring problem in software architecture within a given context. Architectural patterns are similar to software design pattern but have a broader scope.

The three most popular patterns are MVC, MVP, and MVVM. The MVC stands for model, view, and controller, whereas MVP stands for model, view, and presenter, and MVVM for model, view, and view model.

Why do we need patterns?

* Split complex tasks into simpler tasks.
* Reduce bugs.
* Produce testable and maintainable code.

But without an architectural pattern, you may face difficulties maintaining your app’s business logic.

Before you look at each pattern, here are the terms that make them up:

* **Model** stores data and communicates directly with the database. Model is the part that represents your data and application logic. It defines the business rules that manage data handling, modification, or processing.
* **View** displays the model's data and is responsible for the data’s representation in the user interface.
* **ViewModel** is exclusive to MVVM pattern. This is an abstraction of the view layer and also acts as a wrapper for the model data.
* **Controller** is the component that integrates the view and model.
* **Presenter** is a component that only exists in the MVP model. Presenter gets the input from the view component and processes the data with the help of the model.

_I highly recommend to visit [refactoring.guru/](https://refactoring.guru/) for more insights on refactoring, code organizing and design patterns._

**Let's recap:**
* Refactor your code, separate the logic, organize the file structure
* Introduce SOLID principles
* Introduce design patterns

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
1. File structure
1. Logic organization
1. Architectural pattern
1. SOLID principles
1. Absence of "code smells"
1. Code styling

## General Requirements

* Working in a Unix-based operating system.
* All operations (files and directories creating, compiling source code, creating git repository and committing changes and etc.) should be done **using command line exclusively**.
* Work should be done by yourself. **Plagiarism is penalized.**

## Deadline

**Time to complete:** _**3 weeks**_ since you receive the requirements \
_Each week_ of lateness will cost you minus _**1 point**_.

You can present just **one laboratory work per day**, so don't try to present all of them at the end. \
To be **admitted to midterm, you have to present all laboratories received before it**, so, again, don't procrastinate and ideally present one lab per week.

## Presentation

Write a `README` file where you describe your work done.
Upload your code to a remote repository and send the link to it to <alexandr.calugari@isa.utm.md> with subject including 'OOP Lab 6', **before the deadline**.
The presentations themselves will be offline at laboratory classes.

**Good Luck!**