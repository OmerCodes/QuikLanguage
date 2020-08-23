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

# Print Several Variables or Text

print "" << "" prints more than one thing or variables or text the supported printable variables are all including bool etc.\
**Common Mistake:** Make sure your signs are the right way: << not >> or else your compiler will give the error: "operators not recognized Hint: have you put the operaters like this << ?

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
