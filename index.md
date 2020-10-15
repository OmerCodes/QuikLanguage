# Welcome to the Quik language documentation!
If you are on the website if you would like a better coloring and text presentation please head over to here: https://github.com/OmerCodes/QuikLanguage/blob/gh-pages/index.md
Note: Please ignore the arithmetic operators at the start, those are there to highlight the lines of code in color, sadly github has no other option to color and this was the path I took.
# Printing
## Print One Variable or Text
```diff
+ print "" 
```
or
```diff
+ print variable
```
This prints the text inside the quotation marks or the variable there.
### Common Mistakes
**Common Mistake 1:** 
Do not put quotation marks when its a variable  or vice versa, the compiler will not understand but will not give an error for the first one but will give an 
error for the other one saying: "variable not definied in current scope. Hint: Have you put quotation marks around text"


### Examples
**Example 1:**
```diff
+ print "Hello World" 
! Output: Hello World
```
**Example 2:**
```diff
+ String Variable = "Hello"
+ print Variable 
! Output: Hello
```


## Print Several Variables or Text

```diff
+ print "" << ""
```
or
```diff
+ print variable << ""
```
or
```diff
+ print "" << variable
```
or
```diff
+ print variable << variable
```
or More by puttting "<<"
prints more than one thing or variables or text the supported printable variables are all including bool etc.
### Common Mistake
**Common Mistake:** Make sure your signs are the right way: << not >> or else your compiler will give the error: "operators not recognized Hint: have you put the 
operaters like this << ?

### Examples
**Example 1:**
```diff
+ print "Hello " << "World"
! Output: Hello World
```
**Example 2:**
```diff
+ string variable = "Hello "
+ print variable << "World"
! Output: Hello World
```

**Example 3:**
```diff
+ string variable = "World"
+ print "Hello " << variable
! Output: Hello World
```
**Example 4:**
```diff
+ string variable = "Hello "
+ string variable2 = "World"
+ print variable << variable2
! Output: Hello World
```
**Example 5:**
```diff
+ string variable = "Hello "
+ string variable2 = "Wor"
+ print variable << variable2 << "ld"
! Output: Hello World
```

# Input
## Input to one variable or just make a text output
```diff
+ input "" 
```
or
```diff
+ input variable
```
prints the text in quotation marks or if there is a variable it weill get input and put it on the variable.
### Common Mistake
**Common Mistake 1:**  Do not put quotation marks when its a variable or vice versa, the compiler will not understand but will not give an error for the first 
one 
but will give an error for the other one saying: "variable not definied in current scope. Hint: Have you put quotation marks around text"
**Common Mistake 2:** Do not expect any input getting if you only put text after the input, this won't provoke an error but the compiler will just print the text 
and wait for input then do nothing with the taken input.
### Examples
**Example 1:**
```diff
+ input "Hello World" 
! Output: Hello World 
- Note: This won't do anything with the taken input it will just wait for a responce and then continue running the code after it.
```
**Example 2:**
```diff
+ string variable
+ input variable 
! Output: (Does nothing just gets input then the program finishes)
```
**Example 3:**
```diff
+ string variable
+ input variable
+ print variable
! Output: (Outputs whatever the user inputed)
```
## Input to two or more variables and print out text
```diff
+ input "" << ""
```
or
```diff
+ input variable << ""
```
or
```diff
+ input "" << variable
```
or
```diff
+ input variable << variable
```
or More by puttting "<<"
prints out stuff in quotations and inputs the input to the variable there cant be more than one variable next to each other text must separate it
### Common Mistake
**Common Mistake:** Make sure your signs are the right way: << not >> or else your compiler will give the error: "operators not recognized Hint: have you put the 
operaters like this << ?

