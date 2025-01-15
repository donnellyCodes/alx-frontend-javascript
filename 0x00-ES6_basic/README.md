# 0x00. ES6 Basics

## Description
This repository contains solutions and explanations for tasks focused on ES6 (ECMAScript 2015) basics in JavaScript. The concepts covered include:
- Const and let
- Block scope
- Arrow functions
- Default parameters
- Rest and spread syntax
- String templating
- Object creation and shorthand syntax
- Iterators and for-of loops

## Learning Objectives
By completing this project, you will learn:
- What ES6 is and its significance in JavaScript programming
- New features introduced in ES6
- The difference between constants and variables
- How to work with block-scoped variables
- The use of arrow functions and default parameters
- The rest and spread syntax for functions and arrays
- String templating with template literals
- Efficient object creation using shorthand syntax
- Iterators and for-of loops

## Requirements
- All files are executed on **Ubuntu 18.04 LTS** using **Node.js 12.11.x**
- Allowed editors: `vi`, `vim`, `emacs`, `Visual Studio Code`
- All files end with a new line
- Use the `.js` extension for all JavaScript files
- Tested with **Jest**
- Code analyzed using **ESLint** with specific rules provided
- Functions must be exported using `export` syntax

## Setup
### Install Node.js
```bash
curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
sudo bash nodesource_setup.sh
sudo apt install nodejs -y
```
Check versions:
```bash
nodejs -v  # v12.11.1
npm -v     # v6.11.3
```

### Install Dependencies
Run the following command in the project directory:
```bash
npm install
```

### Configuration Files
#### `package.json`
Contains metadata and dependencies for the project.
#### `babel.config.js`
Sets up Babel for transpiling ES6+ code.
#### `.eslintrc.js`
Contains ESLint rules for linting JavaScript code.

## Tasks
### Task 0: Const or Let
Refactor the following functions to use `const` and `let` appropriately:
```javascript
export function taskFirst() {
  const task = 'I prefer const when I can.';
  return task;
}

export function taskNext() {
  let combination = 'But sometimes let';
  combination += ' is okay';
  return combination;
}
```
### Task 1: Block Scope
Modify variables inside the function `taskBlock` to avoid overwriting within the conditional block using block scope.

### Task 2: Arrow Functions
Convert the standard function in `getNeighborhoodsList` to use ES6 arrow syntax.

### Task 3: Default Parameters
Condense the `getSumOfHoods` function using default parameters.

### Task 4: Rest Parameter Syntax
Implement rest parameter syntax to determine the number of arguments passed to the function.

### Task 5: Spread Syntax
Concatenate two arrays and spread a string into characters using the spread operator.

### Task 6: Template Literals
Rewrite return statements to use template literals for clean and readable string interpolation.

### Task 7: Object Property Value Shorthand
Simplify the object creation in `getBudgetObject` by using property value shorthand.

### Task 8: Computed Property Names
Refactor `getBudgetForCurrentYear` to use computed property names.

### Task 9: ES6 Method Properties
Use ES6 method properties in the `getFullBudgetObject` function for concise method definitions.

### Task 10: For...of Loops
Refactor `appendToEachArrayValue` to use the `for...of` loop for iterating over an array.

### Task 11: Iterator
Create a function `createEmployeesObject` that returns an object containing a department and its employees.

### Task 12: Report Object
Write a function `createReportObject` that uses `createEmployeesObject` to generate a detailed report object.

## Repository
- **GitHub Repository**: `alx-frontend-javascript`
- **Directory**: `0x00-ES6_basic`

## Usage
To execute a task:
1. Navigate to the respective directory.
2. Run the file using Node.js:
```bash
node <filename>
```
Or use the provided test files:
```bash
npm run dev <test-file>
```

## Author
Donnelly Nyagoha Amaitsa
