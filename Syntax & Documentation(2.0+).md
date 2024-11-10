# Version 2.0 Syntax & Documentation
The following guide will be updated reguarly as updates roll out.
## Basic Syntax
### In this section you will learn:
- the 4 sucrolose data types
- spacing & syntax
- compiling
### Sucrolose's 4 Data Types
Sucrolose has 4 data types. Those types are:

- Texts: normal printable texts ```this is my text```
- Integers: non-fractional numbers ```0```
- Decis: fractional numbers ```0.1```
- Booleans: true or false ```true``` ```false```
>As of version 2.0: booleans are not implemented, they will be added in a future update
### Spacing and Syntax
Sucrolose is a simple easy-to-understand language, every word is seperated by spaces, no '-', no ':'.

```function paremeter```

```display this is cool text```

>Sucrolose automatically seperates the line of code

### Compiling
Sucrolose compiles code through a executable.

In order for your program to work: your code must be in "main.sucr". This file comes with your compilier, but can easily be created.

How to create a .sucr file:
- enable file extensions visible if you have not already
- create a txt file titled "main"
- change the ".txt" file extension to ".sucr"

Right now, .sucr files can be edited in notepad or any text editor that supports it.

When you're ready to run your code: just run the executable.

## Common functions and variable declaration
### In this section you will learn:
- how to declare variables
- commonly used functions
### Declaring Variables
Declaring variables in sucrolose is very simple.

You declare variables by using the ```declare``` function.

Review the following sample code:

```declare coolvariable this is my cool variable```

>The following line of code is formatted as ```declaration | variable name | variable definition``` or ```declare | coolvariable | this is my cool variable```.

### Commonly Used Functions:
- declare: declares a variable ```declare coolvariable this is my cool variable```
- display: displays to screen ```display this is something i am displaying```
- uput: collects user input ``` declare coolvariable uput put a cool thing here: ```
- math: adds, subtracts, multiplys, and divides 2 numbers ```declare coolnumber 1 + 1```
- pause: pauses program for a certain amount of time ```pause 10```
## Conditionals
### In this section you will learn:
- the "suppose" statement
### The "suppose" Statement
Sucrolose's "if" statement is "suppose".

The "suppose" statement is used to determine if a given condition is true.

```suppose 1 = 1 display true```
>The following line of code is formatted as ```suppose | 1 = 1 |(only continue if true)| display | true``` or ```suppose | conditional |(only continue if true)| function | paremeter```

# FAQ & PIE (Frequently asked questions and Pontential inevitable problems):
Q: My file won't run!

A: It could be a hidden file extension. be sure to disable those then change your file type.

Q: What do i do with this?

A: No clue.

Q: My code is correct but errors are showing!

A: Check for gramatical errors/mistaken capitalizations.

Q: My program completed but it says "invalid function" at the end.

A: Check for any extra lines/spaces below the code.
