# 0x00. ES6 Basics

## Overview
This project covers the basics of ECMAScript 6 (ES6) including new syntax and features introduced in the latest version of JavaScript. The goal is to get familiar with ES6 and learn how to leverage its features to write better, more efficient code.

## Concepts
For this project, you should focus on the following concepts:
- JavaScript programming
- Software Linter

## Resources
Read or watch:
- [ECMAScript 6 - ECMAScript 2015](https://www.ecma-international.org/ecma-262/6.0/)
- [Statements and declarations](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Grammar_and_types#Declarations)
- [Arrow functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)
- [Default parameters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Default_parameters)
- [Rest parameter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters)
- [Javascript ES6 — Iterables and Iterators](https://javascript.info/iterable)

## Learning Objectives
By the end of this project, you should be able to explain:
- What ES6 is
- New features introduced in ES6
- The difference between a constant and a variable
- Block-scoped variables
- Arrow functions and function parameters default to them
- Rest and spread function parameters
- String templating in ES6
- Object creation and their properties in ES6
- Iterators and for-of loops

## Requirements
- All files will be executed on Ubuntu 18.04 LTS using NodeJS 12.11.x
- Allowed editors: `vi`, `vim`, `emacs`, `Visual Studio Code`
- All files should end with a new line
- A `README.md` file, at the root of the folder of the project, is mandatory
- Your code should use the `.js` extension
- Your code will be tested using the Jest Testing Framework
- Your code will be analyzed using the linter ESLint with specific rules provided
- All functions must be exported

## Setup

### Install NodeJS 12.11.x
In your home directory, run the following commands:
```sh
curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
sudo bash nodesource_setup.sh
sudo apt install nodejs -y
nodejs -v
# Should output: v12.11.1
npm -v
# Should output: 6.11.3
