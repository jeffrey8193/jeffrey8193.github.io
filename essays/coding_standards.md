---
layout: essay
type: essay
title: "Following Coding Standards With ESLint"
# All dates must be YYYY-MM-DD format!
date: 2025-02-13
published: true
labels:
  - Coding
  - Coding Standards
---

<img width="200px" class="rounded float-start pe-4" src="../img/eslint/eslint_square.png">

## Coding Standards

There are many different types of coding standard that one might encounter throughout their education and career. When writing code for personal projects, I often find that I adhere to my own personal coding standard. I will write code that I find aethestically pleasing, easy to read, and in a way that helps me understand what I'm writing. However, when I start writing code for a homework assignment or a project, there is often strict guidelines for how to format your code and comments. I usually need time to adjust how my code is formatted, like how to format conditionals and what kind of comments to include about functions among other things. I often find that these coding guidelines are helpful when writing code collaboratively since it is designed to make code easier to read and understand. However, they can be a bit tedious to adhere to especially when you aren't used to it.

```js
// Examples of coding guidelines

/*
**    Function Name: foo
**    Return Type: void
**    Parameters: param1: number, param2: string
**    Functionality: Prints param2 if param1 is an even number
*/

void foo(int param1, char[] param2) {
    // Bad example: Explicit block indentation for conditionals
    if(param1 % 2 == 0) printf("%s", param2);
    // Good example: Explicit block indentation for conditionals
    if(param1 % 2 == 0) {
        printf("%s", param2);
    }
}
```

<img width="450px" class="rounded float-start pe-4" src="../img/eslint/eslint.png">

## ESLint

ESLint is a tool that analyzes JavaScript code and helps you find problems and errors when you're writing code. There are also plugins that extend this functionality to JavaScript dialects like TypeScript. When I was using ESLint for TypeScript I often found it very helpful to catch unnecessary variables which allowed me to shorten my code and make it more readable. Something else that was helpful is that ESLint discourages dangerous implementations like using the any type. Before using ESLint I often found myself using any type when I wasn't sure what the type of a variable would be, ESLint highlights these bad coding behaviors. To address this problem in my code, I learned how to use generic types and implemented them into my functions. ESLint was helpful in teaching me better implementations in TypeScript and I'm sure there are more cases where ESLint can push me toward writing less error-prone code. Overall, I don't find ESLint's coding standards tedious to adhere to compared to other coding guidelines I've followed in the past. However, I don't find it all that useful when writing code collaboratively, but it definitely helped me write better TypeScript code.
