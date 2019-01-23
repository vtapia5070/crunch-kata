# Crunch Kata

Welcome to the Crunch Kata! The purpose of this exercise is evaluate your automated testing and problem solving skills. 

## Problem description

You're working on an application that enables its users to explore survey data. These surveys contain many questions, or *variables*, which may be grouped and organized in a tree-like structure to make them easier to find. Your job is to develop a web component that displays these variables following the specified order structure. (A different team is implementing the interface for arranging the variables into that order--that's not your responsibility.)

The backend team has provided two test fixtures that you can use to start developing the feature. The first one, `variables.json`, is the catalog of variables found in a dataset. The second, `order.json`, represents the order in which these variables should be displayed. Each entry in `order.json` maps to an item in `variables.json`.

## Instructions

The deliverable should contain the following:

1. A component that displays the variable catalog following its hierarchical order. It should be easy to tell the group to which a variable belongs, i.e.

    ![HVL](hvl.png)

2. A service that accepts a variable's name and returns the variable's position in the order.
3. A service that accepts a position in the order and returns a variable.
4. An HTTP layer that requests the two fixtures.
5. Automated tests that confirm that your code works.

## About the tools

Use whatever library, framework, and/or build system that you feel comfortable with. 

## Deliverable

Publish your work in a GitHub repository.
