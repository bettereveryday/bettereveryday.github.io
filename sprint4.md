
# Mayden Academy
## Sprint 3 - Monday 2nd November - Friday 13th November
### PHP & Wordpress

- Mike in all first week.

### Learning Objectives

- Understand the syntax and structural elements of PHP
- Know how to correctly apply the various control-flow structures
- Understand PHP data types, type-juggling, and operator precedence
- Organize code into reusable functions
- Accomplish tasks using PHP's wealth of built-in file system and array functions
- Understand essential elements of HTTP such as cookies and sessions
- Build forms to collect information from a user

### Challenge: Post / poles challenge

### Day 1 - Intro to PHP and it's Basic Language Constructs
- WORDPRESS
	- TALK by @Sarah Maynard
	- WARNING: Procedural not OOP
- Syntax
    - keywords, formatting
    - examples of syntax in different languages
    - syntax vs semantics
    - __EXERCISE:__ tidy up the format of some messy code (without using beautifier)
- What is PHP?
	- php.ini
	- ```phpinfo()``` 
	- __EXERCISE:__ Write a hello word program 
- Quotes
	- Single vs double quotes
	- "Variable Interpolation" 
- Comments
	- Single line
	- Multi line
	- Standard formats e.g DocBlocks
- Special Characters
	- ```"\n; \t; \\"``` 
- Data Types
	- ```String; Integer; Float; Boolean``` 
	- Typed Languages
	- Static/dynamic type checking
	- Type juggling & type casting
- Precedence
	- [Operator Precedence](http://www.php.net/manual/en/language.operators.php) 
- Symbols
	- Logical ```! && ||```
	- Assignment ````=```
	- Comparison ```== === != !==```
	- Compound assignment ```*= /= += -=```
	- Increment/decrement ```++ --``` 
- Variables
	- What is a variable?
	- Allowable names
	- Example: ```$$foo```
	- HEREDOC / NOWDOC 
	- ```$story = EOS>>>```
- Constants
	- ```define("PI", 3.1415927);```



### Day 2 - Control Flow

- Arrays
	- Indexed arrays (Numeric, Enumerative)
	- ```$days_array = array('Mon', 'Tues', 'Wed', 'Thurs', 'Fri', 'Sat', 'Sun');```
	- Associative arrays
	- ```$personal_details = array("Name" => 'John Doe', "Age" => 21, "Sex" => 'Male')'``` 
	- key / value
	- Multi-dimensional arrays
	- Adding to arrays
	- Iterating through arrays ```foreach ($names as $name) {...}``
	- Array Functions
	
- Operators
	- Assignment Operators
	- Combining Operators
	- Mathematical Operators
	- String Operators ```. .=```
	- Comparison Operators
	- Logical Operators
		- ```and or xor not```
		- Difference between ```and``` and ```&&``` (precedence)
- Conditionals
	- if
	- if ... else
	- elseif
	- switch
	- coding style (PSR)
	- Single line if is BAD
	- Ternary Operator ```(<condition>) ? <value if true> : <value if false>;```
- Loops
	- for
	- while
	- do-while
	- foreach
	- continue / break
	- Embedded loops

### Day 3 - Functions & Files
  - [Functions](http://php.net/manual/en/functions.user-defined.php)
	  - Parameters
	  - Optional Parameters
	  - Default values
	  - Return values
	  - Passing by reference
  - [PHP Built in Functions](http://php.net/manual/en/functions.internal.php)
	  - Maths functions
	  - String Functions
	  - Array Functions
	  - How to read/use the php manual
  - Function Design Tools
  - File Systems (Handling)
  - [EXERCISE] Blackjack


### Day 4 - Web Concepts

- Client/Server Communications
- How to embed PHP into HTML
- How to embed HTML into PHP
- Cookies
- Sessions
	- [EXERCISE] Create login using Sessions
- ```$_GET``` and ```$_POST```
- SECURITY
	- [TALK] @JCL


### Day 5 - Introduction to Object Oriented Programming

- 11:00 - 12:00 Automated Testing (@Roy)
- Intro to OOP.
	- Why is OOP better?
	- Examples of Functional vs OOP programs
- Objects, Classes, Instances
- Methods
- Properties
- Setters & Getters
- Encapsulation
- Abstract classes
- Interfaces
- Inheritance
- Polymorphism
- [OOP Concepts](http://www.codeproject.com/Articles/22769/Introduction-to-Object-Oriented-Programming-Concep)

### Week 2 - Project

- Build an Order Inquiry Application
- Monday - Inversion of Control talk [@Oliver MW]
- Friday 13th - Rob C Talk - Scaling Scrum
- Orbit bug fixes
- Challenge


- FRIDAY: Test!
	- 


> Written with [StackEdit](https://stackedit.io/).
