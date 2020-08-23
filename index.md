# Welcome to the Quik language documentation!

# Printing
## Print One Variable or Text
```diff
+ print "" 
```
or
```diff
+ print variable
```
This prints the text inside the quotation marks or the variable there.\
**Common Mistake:** Do not put quotation marks when its a variable  or vice versa, the compiler will not understand but will not give an error for the first one but will give an error for the other one saying: "variable not definied in current scope. Hint: Have you put quotation marks around text"

**Example:**
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
prints more than one thing or variables or text the supported printable variables are all including bool etc.\
**Common Mistake:** Make sure your signs are the right way: << not >> or else your compiler will give the error: "operators not recognized Hint: have you put the operaters like this << ?
**Example:**
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

# Input
## Input to one variable or just make a text output
```diff
+ input "" 
```
or
```diff
+ input variable
```
prints the text in quotation marks or if there is a variable it weill get input and put it on the variable
## Input to two or more variables and print out text
