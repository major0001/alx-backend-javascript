```markdown
# 0x04. TypeScript

This repository contains the completed tasks for the `0x04-TypeScript` project. Below is a summary of each task, along with the relevant files and directories.

## Overview

This project covers the basics of TypeScript, including types, interfaces, classes, and how to work with the DOM. The tasks are designed to help you understand key concepts such as generic types, namespaces, declaration merging, and ambient namespaces. Each task has been completed and the code is available in the respective directories.

### Prerequisites

Ensure you have the following installed on your system:
- Node.js
- TypeScript
- Webpack
- Jest

### How to Run

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/username/alx-backend-javascript.git
   cd alx-backend-javascript/0x04-TypeScript
   ```

2. **Install Dependencies:**
   Navigate to the directory of the specific task you want to run and install the necessary packages:
   ```bash
   cd task_X   # Replace X with the task number
   npm install
   ```

3. **Build and Run the Code:**
   To transpile the TypeScript code and run the project:
   ```bash
   npm run build
   ```

4. **Test the Code:**
   Some tasks have tests written using Jest. To run the tests:
   ```bash
   npm test
   ```

## Task Details

### Task 0: Creating an Interface for a Student

- **Directory:** `task_0`
- **Files:** `js/main.ts`, `package.json`, `.eslintrc.js`, `tsconfig.json`, `webpack.config.js`
- **Summary:** Created a `Student` interface, instantiated two students, and displayed them in a table using vanilla JavaScript. The project is set up with Webpack to ensure no type errors.

### Task 1: Let's Build a Teacher Interface

- **Directory:** `task_1`
- **Files:** `js/main.ts`, `package.json`, `webpack.config.js`, `tsconfig.json`
- **Summary:** Developed a `Teacher` interface with modifiable attributes and added support for additional dynamic attributes.

### Task 2: Extending the Teacher Class

- **Directory:** `task_1`
- **Files:** `js/main.ts`
- **Summary:** Created a `Directors` interface extending `Teacher`, adding a `numberOfReports` attribute.

### Task 3: Printing Teachers

- **Directory:** `task_1`
- **Files:** `js/main.ts`
- **Summary:** Wrote a `printTeacher` function that returns a formatted string based on the teacher’s name.

### Task 4: Writing a Class

- **Directory:** `task_1`
- **Files:** `js/main.ts`
- **Summary:** Implemented a `StudentClass` with methods for working on homework and displaying the student’s name.

### Task 5: Advanced Types Part 1

- **Directory:** `task_2`
- **Files:** `js/main.ts`, `webpack.config.js`, `tsconfig.json`, `package.json`
- **Summary:** Created interfaces for `DirectorInterface` and `TeacherInterface` and implemented classes with appropriate methods. Also developed a `createEmployee` function.

### Task 6: Creating Functions Specific to Employees

- **Directory:** `task_2`
- **Files:** `js/main.ts`
- **Summary:** Implemented `isDirector` and `executeWork` functions to differentiate between `Director` and `Teacher` tasks.

### Task 7: String Literal Types

- **Directory:** `task_2`
- **Files:** `js/main.ts`
- **Summary:** Developed a `Subjects` string literal type and a `teachClass` function to handle different subjects.

### Task 8: Ambient Namespaces

- **Directory:** `task_3`
- **Files:** `js/main.ts`, `js/interface.ts`, `js/crud.d.ts`, `webpack.config.js`, `tsconfig.json`, `package.json`
- **Summary:** Built interfaces and types, and wrote ambient declarations for external library functions. Integrated the `crud.js` library into TypeScript.

### Task 9: Namespace & Declaration Merging

- **Directory:** `task_4`
- **Files:** `js/subjects/Cpp.ts`, `js/subjects/Java.ts`, `js/subjects/React.ts`, `js/subjects/Subject.ts`, `js/subjects/Teacher.ts`, `package.json`, `tsconfig.json`
- **Summary:** Created a namespace `Subjects` with merged declarations, and developed classes for `Cpp`, `Java`, and `React` subjects.

### Task 10: Update Main.ts in Task 4

- **Directory:** `task_4`
- **Files:** `js/main.ts`
- **Summary:** Instantiated and logged subjects with their respective teachers, utilizing methods defined in the `Subjects` namespace.

### Task 11: Brand Convention & Nominal Typing

- **Directory:** `task_5`
- **Files:** `js/main.ts`, `webpack.config.js`, `tsconfig.json`, `package.json`
- **Summary:** Created `MajorCredits` and `MinorCredits` interfaces with brand properties and functions to sum credits.

## Manual QA Review

- Ready for Manual Review
