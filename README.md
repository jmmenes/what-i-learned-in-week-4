# What I Learned In Week 4 At Code Immersives

&nbsp;

## Setting Up a Dev Environment

I installed on my mac,

- iTerm2, a better terminal
- Homebrew
- Node. NPM, node package manager
- oh-my-zsh
- VS Code. Visual Studio Code is a source-code editor.

&nbsp;

## Git

1. git clone
2. git add
3. git commit -m
4. git push

I used these commands to fork/clone repositories. Which then allows me to edit/make changes to files. After the changes are made I will make a commit to highlight what changes were made. The last step is to push the commit back to the source on GitHub.

&nbsp;

## Into To JavaScript

JavaScript, often abbreviated as JS, is a high-level, interpreted scripting language that conforms to the ECMAScript specification.

How to link external JS to HTML

    <script src="script.js"></script>

How to link internal JS with HTML

    <script> JS Code </script>

&nbsp;

## Variables

JavaScript variables are containers for storing data values. Creating a variable in JavaScript is called "declaring" a variable. You declare a JavaScript variable with the keywords, 'let' or 'const'

JS primitive data types

1. Strings
2. Numbers
3. Booleans = True or False
4. NaN = Not a number
5. Null = The value null represents the intentional absence of any object value. It is one of JavaScript's primitive values and is treated as falsy for boolean operations.
6. Undefined = The undefined property indicates that a variable has not been assigned a value, or not declared at all.

&nbsp;

## Strings & Numbers

Strings are written with quotes. You can use single or double quotes:

let name = ‘Hello World’

const name = “Hello World”

&nbsp;

Numbers can be written with, or without decimals

let age = 2

const age = 2.5

&nbsp;

## Variable Re-Assignment & String Concatenation.

Practiced learning about code logic & how declaring variables with the let keyword can be changed with different values.

To concatenate a string, you add a plus sign + between the strings or string variables you want to connect.

    let myPet = 'seahorse';
    console.log('My favorite animal is the ' + myPet + '.');
    // My favorite animal is the seahorse.
