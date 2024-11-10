# Version 1.0 Syntax And Tutorial:
## Section one: Basic Syntax
### The four data types:
There are 4 data types in sucrolose:
* texttype: sucrolose equivalent of strings and characters
* integers
* decis: fractional number
* booleans
### Formating:
One of the most important differences between Sucrolose and other languages is that spaces are not used to seperate words outside of texttypes. 

Instead, we use hashtags (#). For example:

```
display#this is my sample texttype#
```

>Spaces are only used in the textype ("this is my sample code")

You can only have one command/code instruction per line (unless your using a conditional). For example:
```
display#this is my sample texttype#
display#this is my sample texttype aswell#
```
The full formatting of the code looks like this:

display - function|# - seperator|this is my sample textype - parameter|# - seperator 

### File type and formatting (.sucr [pronounced sook-er]):
Sucrolose's file type is .sucr.

In order for it to run, you need to title your file: "main.sucr".

You will need to edit it in notepad or any other text editing program for now.

Refer to FAQ/PIE for any problems you are having.
## Functions
### declare: declares/creates a variable. ```declare#myvariable#this is my variable#```
### display: displays/prints anything. ```display#you can see this text#```
### 'uput': collects user input. ```declare#myvariable#'uput'#user input here#```
### add: adds 2 numbers and stores them into a variable. ```declare#sum#add#3#4#```
### suppose: sucrolose's "if" statement. ```suppose#2#>1#declare#myvariable#true#```
### pause: pauses program for provided amount of seconds. ```pause#5#```

# FAQ/PIE (Frequently asked questions and Pontential inevitable problems):
Q: My file won't run!

A: It could be a hidden file extension. be sure to disable those then change your file type.

Q. What do i do with this?

A. No clue.

Q. My code is correct but errors are showing!

A. Check for gramatical errors/mistaken capitalizations.

Q. My program completed but it says "invalid function" at the end.

A. Check for any extra lines/spaces below the code.

