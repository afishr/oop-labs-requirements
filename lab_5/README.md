# Lab 5: Wrapping Up the Simulation

## Intro

Hello. In previous laboratory works you built the core of your simulation. Now you'll have to polish it and wrap into a working software.

This laboratory work is the fourth one in a series of 4 labs (`Lab 2`, `Lab 3`, `Lab 4`, -> `Lab 5`, `Lab 6`).

## Simulation

The goal of a simulation software is to reproduce the behavior of an existing system, and give the possibility to experiment on it.
You have to define a set of parameters that user can tune and receive different results, observe some correlations, learn something about the system that is simulated.

Simulation means that the program must run continuously, i.e. we start it and observe the process until we explicitly finish it. No input required to start, no input required to interact with the program. Simulation is an isolated process that represents the work of a system. The user only affects it by changing configurations in runtime or before.

Focus on the details. Try to use less randomness and base the decisions your simulation has to take on some other events that took place previously. In such a way, your simulation will look more like a real-life system.

Also, think on the states your simulation gets through. Think how it is affected by the events that take place in the system. If the majority of the events you implemented doesn't have effects, there is a high probability that they are just useless. Every action should have a consequence.

Let's recap:
* Define parameters to affect the behavior of the simulation.
* Provide some insights, results of simulation runtime. 
* Use random as less as possible. Base the decisions inside your simulation on other events.
* Describe the work done in a `README` file and upload it to your remote repository.

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
1. Level of detalization.
1. Usefulness of insights provided.
1. Variety of states of your system.
1. Code styling.

## General Requirements

* Working in a Unix-based operating system.
* All operations (files and directories creating, compiling source code, creating git repository and committing changes and etc.) should be done **using command line exclusively**.
* Work should be done by yourself. **Plagiarism is penalized.**

## Deadline

**Time to complete:** _**2 weeks**_ since you receive the requirements \
_Each week_ of lateness will cost you minus _**1 point**_.

You can present just **one laboratory work per day**, so don't try to present all of them at the end. \
To be **admitted to midterm, you have to present all laboratories received before it**, so, again, don't procrastinate and ideally present one lab per week.

## Presentation

Write a `README` file where you describe your work done.
Upload your code to a remote repository and send the link to it to <alexandr.calugari@isa.utm.md> with subject including 'OOP Lab 5', **before the deadline**.
The presentations themselves will be offline at laboratory classes.

**Good Luck!**