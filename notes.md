# Module 1

## IDLE
Stands for integrated DeveLopment Environment
Kind of like IDE where code can be written and run
New Files can hold and contain code
Interactive mode (1 line of code)
Script mode (multiple lines of code) 

## Steps to write code
Open up IDLE
Create New File
Save it as something (add .py at the end of name for files)
Run it
(to open any file made, Click file, recent files)


## Functions
Pre made code to do something specific
Little workers 
Examples
print()
You can add `end = ‘ ‘` and  `sep = ‘ ‘`
`\n`adds a line break
`\t` adds a tab
input()
Does : it asks the user a question
Returns: the answer of the user 

## Strings
Delimiters (Characters that show the beginning and end of a string)
You can use (`“hi”`, `‘hi’`, `“””hi”””`, `‘’’hi’’’`)

## Different types of strings 

## String literals
A combination of character data in delimiters

## Numeric literals
numbers!

## Variables
Can’t start with a number
Can’t have spaces
Can’t use special characters (can’t have - in a variable name)
Can’t use reserved python words



# Module 2

## Commenting
You can use “”” “”” for multiple line commenting
You can use # for single line commenting

## Data types
Strings
Any combination of characters contained in delimiters 
`var 1 = “birds”`

## Numeric literals
Integer

Whole number (never have decimal points)
`var2 = 5`

Floating point value (Any number with a decimal point)
`var3 = 6.0`

Logical values (booleans → true/false) 
isSaturday = false

You can print out the type of data a variable is by using the function type()
[Example] `print(type(var1))`

## Data Type conversions
There are a variety of python functions which will help change one data type into another
int → float  you use float()
Float → int you use int()
Float/int → string you use str()


## Mathematical operations

## Division operators 
There’s two types

## Floating point division
`(5/2) = 2.5`

## Integer Division
The // for integer division will just round down to the nearest whole number 
`(5//2) = 2   `
`(-5//2) = -3 `

## Exponent operator
`(2 ** 4) = 16`   ← 2^4
`(4 ** .5) = 2`      ← Square root of a number

## Mod operator
`(5 % 2) = 1`

## Mixed type operations
Can't subtract or divide strings but you can add and multiply

## Different math functions
`Math.floor`
`Math.ceil`



## The format Function
format(value, format_spec=””)
PI = 3.1415926   # a float 
`format(PI,  “>10.2f”)`

*Always returns a string*


## Errors

## Syntax Errors
Does not follow the rules of the language

## Runtime Errors
Code is fine but the program crashes

## Logic Errors
Code is fine but what happens is not what is wanted



# Module 3

## Boolean
Data type
*Values can be True or False*
*Case sensitive, must be capitalized (True and False)*

## Ways to check boolean values
`==` →If It is equal
`!=` →If it is not equal
Can wrap it in other statements (ex: `print(1 == 1)` → True



## Opporations

## Comparison Operators

## Logical Operators
	

*Order of Operations(First: Mathematical,  Second: Comparison, Third: Logical Operators)*
*Order of Logical Operators (First: not,  Second: and, Third: or)*


## Conditionals



*Python recognizes 0 as false and any other integer as true*


## Modules

Must import modules first then it can be in use
Kind of Like JavaScript tools
They have their own special functions

*Math Module*

*Random Module*

*Turtle Module*



# Module 4

## While loop
A condition-controlled loop (repeats statements as long as condition is true

`while condition:
	Statement
	Statement
	Statement`

Control variable → Keeps track of weather or not we should keep looping 
Accumulator variable → Defined globally and can be used as a self referential variable assignment

Break
→ keyword to end the loop

Continue
→ keyword to iterate the loop again

Sentinels
A predefined value that the user can type in to indicate that they are finished entering data 

Data Validation



# Module 5
## While loops
Unknown number of iterations

## For Loops
Fixed number of iterations
`for VARIABLE in ITEMS:
    STATEMENTS`



