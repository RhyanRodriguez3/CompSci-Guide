# Programming Language Guide
Purpose: to be a good enough programmer to qualify for junior BI dev roles. Research a lanaugae we've talked baout that intereste you. Research their official website and wiki page to decide if thats the language you would like to start with. Then learn the langugage you decide to pursure, use youtube as a source. Once you learn how to program using that languages syntax and concepts, use coding bat to kick start your code writing, coderbyte with challegnes, and hackerRank. Important com sci concepts are data strutures, and data science. 

<details>
 <summary>Introduction to Programming and Computer Science - Full Course</summary>

---
### The computer
- Programming is the process of preparing an instructional program for a device. Attempting to get a computer to  complete a specific task without making mistakes.  
- The computer only understands machine code, which is binary code. You need to convert your instructions for the machien to execute it. Programming languages are fundamentally a middleman for translating a  program into machine code. they serve as interprets for converting languages into other languages.
- There are many programming languages and each have their own specific uses, general purpose languages like pythong and Java can perform a variety of computational tasks and other languages are for specific tasks. Low  low level programming languages, such as assembly, or C, are closer to binary than  a high level programming language, such as Java or Python. Each language is specified for specific tasks and has its own advantages and disadvantages. High level langauges have more abstraction from machine code an easier to learn, lower level languages are closer to the machine cldoe but often provide more functionality.
  - For web development: HTML and CSS. HTML is a markup language used for writing the content of a website.  CSS is used to style the design of a website.
  - A scripting langauge is a langauge with many commands for you to use than can be run without being compiled. Easier to port between operating systems. Also used in web dev. Ex are Perl, PHP, Ajax, and JavaScript.
  - General purpose language offer a wide range of uses and applications. A good basic language such as Java, Python, and C++. Java is good for game / Web development Python is good for data analysis and scripting, while C++ tends to be used for writing applications and system programs. These are good basics but be aware that you should find the one which you like the most syntax. 
- The computer knows how to do arithmetic (x, +, -, /).
- It also knows how to handle string (text). Concatenating is adding strings together. Quotations make the value a string.

## Syntax and Programming rules
- And IDE is a program to write, run, and debug code and convert it to machine code. Features include built-in error checking, auto-fill, and project hierarchy (objects that help organize and manipulate files within your project). Has an area for writing code, 
- Each language has it's own set of rules, you must follow within an IDE, called Syntax. Each have their own concepts and styles. 
- Programming grammer is called syntax, set of rules that you must follow exactly  if you want your program to run correctly. Breaking these rules cause a syntax error. Think about programming language as an actual language. Only computers have their language, called machine code, and humans. If you don't follow the syntax, the message is misinterpreted.
- It's recommended that  you learn the rules and syntax of a language before beginning to write complex programs in  that language. Most of the rules are tedious to learn but easy to master.

## Variables
- A variable is something that can store information. That variable can be referenced and manipulated. 
- There are multiple types of variables, primitive variables are integers (Int, whole numbers), booleans(true/false), floats and doubles (decimal numbers), strings and characters (text and str/char).
- You declare a variable, store information in it, then run code. WHen you create a variable, the computer creates a space in memory that stores your variable and its contents.
- Variables can be manipulated by having empty ones to later reference to, update throughout your code. Just keep in mind that these variables  are nothing more than places in memory in which a certain value is stored.
- You can perform operations on variables. Add is called concatenating
- Naming conventions of variables: CamelCase, SnakeCase
- Conditional statements: are statements that change  the path of our code depending on certain conditions. Depending on certain conditions, we want our code to do different things. If Then statements. Most programming langauges use braces (), whatever is inside the braces will be evaluated as either true or false. When true, it executes, when false it moves to the next condition or stops. Else is a statement that comes after the if statements. Switch variable statements define the variable then write cases for each condition and their instructions. are similar to if then or else statements. Conditional statements is improtatn because it adds variability to programming, allowing the user to adapt to different tasks.

## Arrays and Dictionaries
- Variables are good at storing singular bits of information, and are unable to hold more than one piece of data.
- An array is a list of similar values, such as int, str, and other arrays. Usually the data is related. Think of arrays as column in excel.
- When referencing arrays, reference each element of the array within them. For example, you create an array of 1 to 10. In programming we use index to refer to a value. An index is just a fancy way of saying that numbers place within the array. The index starts as 0.  
- When creating arrays, called initializing, you can insert the values or you can define array parameters to be used later. Once an array has been dfeined, there is no way to change it's size. When initizaliing, you must determine the array type. 2D arrays are arrays inside of an array. 
- There are more than one ways to store data such as linked lists, stacks, queues, maps,  trees, and many others. Array lists is a growing array, that dynamically changes its size when you don't know the exact number of values that an array list will need to store. For example, a database of users. 
- Dictionaries are a different way of storing values. It stores multiple values and tied to an identifier that is used to reference the value, called a key. When you use a dictionary, you use the unque key and the dictionary will tell you the value tied to it. 

## Loops
- A loop is a statement that is used to run certain instruction repeatedly. There are three different types of loops.
1. `For loops` are used when you would like to carry out a certain set of instructions numerious times. Consists of three parts, an integer value, a conditional statement the integerger must readh to exit the loop, and an operation to modify the integer value after the instructions inside of the loop are completed. You must make sure to set up a condition where the intial integer value and the operation will at some point be met.
2. `For Each` loop is used for iterating through entire arrays or lists. The loop will go through each element in the array  and carry out a set of instructions for each value. Useful for perfomring operations accross an entire collection of data.
3. `While Loop` will continue while a conditional statement given is true. Do while loops are similar to while loops but will always carry out instructions at least once. Instructions inside loop will run once before checking the conditional statement.  

## Errors
- There are three different types of errors, syntax, runtime, and logic errors. Errors are referred to as bugs.
- Runtime errors are caused by a part of your code cpmputed in a resonable amount of time. Ex: The infinite loop. Runtime errors are usually caused by a  statement in your code that seems logically sound, but the computer physically has no way of  computing it in a reasonable amount of time.  
- Psudeocode is thinking through the flow of your code before runing it (especialy loops), and carefuly planning out the code before writing.
- Logic errors provide results you did not want. To prevent this, test your code invrementally and often.
- To debug, read the error message, it provides you the line where the code turns bad. Google it. Use a print statement on each line. Use breakpoints to pause the program. Comment out the section of error. To prevent errors, backup the code frequently

## Functions
- A function is a segment of code that can be fun by colling the function name. Can be called numrous times and in numerious places. 
- Functions serve many purposes, often, you will just import the ones you need in your program. There are four types of functions. Functions branch into ones that take argument or not, then reutrns values or returns no values.
- Arguments are variables we pass into a function in order to be manipulated then either returned back to us, printed to the console, or used in another operation. 
- Functions that don't take in arguments are when you package multiple functions into one.
- Functions that return values are string, interger, array , etc. Functions that don't return anything are called void functions which take no arguments and returns no value.
- You can import functions from libraries of pre-made functions. A library is a collection of funtions that all have similar functions. You can do this using an `Import` statement, which contains the word import followed by the library name, package, and class.
- A package is a smaller set of functions and   methods to help differentiate between the 1000s  of methods contained in a library
- A class is a specialized function in that package.
- You can create functions. A function is made up of scope (who can use it), declaring and stating what type of function it is (the function type), and the function name followed by parenthesese, then write what you want it to do by writing arguments in the curcly braces.
- An expression is an operation statement that returns a value. For example 2 + 2 = 4.

## Data Structures
- There are many ways to search through lists. Searching algorithms are ways in which we can look through a list of values  stored in an array, and find a particular piece of data. used to return the index of a particular data points so that  it can be used, modified or updated or checked on.
- There are two states of lists sorted or unsorted. Big O notation is a value used to dtermine the efficiency of a searching algo that is based on the average number of items and worst case scenario.
   - Linear searches start at the beginning and systematically check each data point until you find the value. 
   - Binary search uses a recursive process, meaning the computer breaks down the list into smaller parts to find the item your looking for. Only works in a sorted list. It looks ata  list, starts the search in half, then moves up or down to find the value. Recursion is the process of using functions that repeatedly call themselves. Basically, when you code an instruction, a step in that instruction is to call another or same function. 
   - Will need to rewatch recursion to full understand the process. Recursion is useful because it breaks large problems into smaller simpler pieces to compute.
   - A stack is a data structure that contains all the tasks you instruct your program to complete. A LIFO data structure. Stack overflow occurs when you cannot complete the last instructions and causing an infinite loop.

## Writing Code strategies
- A majority of programming is thinking about the code rather than writing it. It is about planning the smaller steps to solve the problem. Constructing an outline for the paper. Three main ways to plan pseudcode is
   - flowchats, which can be used to think through the process of a particular function. Flowchart method is good for thinking through the flow of a function. 
   - Another popular method is to write out what you want your code to do and fill in the functions. The write up method is good for getting the general idea of a program.
   - The final is functionality planning, which is writing out the main features you want the user to have using our program, also what functions or smaller programs you're gon to need to complete those features. Functionality is good for listing out the certain functions of a certain program. 

---

</details>



<details>
 <summary>100+ Computer science concepts explained: Comp Sci definition</summary>

---
- a computer it's just a piece of tape that holds ones and zeros along with a device that can read and write to it it's called a turing machine
- The core of modern computers we have the central processing unit made up of silicon transistors, microscopic on/off switches that trasnmit binary code.
- Declaring a variables, where you attach a name to a data point, allowing you to reuse it somewhere else in your code.
- Data structures are organized data. Arrays organize multiple data points in order. 
- Algorithms are code that solve a problem by doing something to the data structure. A fundamental algorithm is a function: which is a block of code tht takes an input then does something and returns an output.
- Arguments are input parameters.
- Operators are used to compare values.
- Booleans are expression. Expressions produce a value.
- A statement is a block of code that simply does something. For example, If statements, Loop statements,
   - A while loop will run this block of code over and over again until the condition in the parentheses becomes false
   - A for loop continues for each item of something
- Recursions are functions that call themselves.
- A base condition will terminate the loop. 
- The idea behind OOP is that you use classes to write a blueprint for the data or objects in your code a class can encapsulate variables which are commonly called properties as well as functions 
which are usually called methods.

---

</details>

<details>
 <summary>FireShip How to Program</summary>

---
## Fundamental Concepts of Object Oriented Programming
- APIE: are the four pillars of object oriented programming. 
- Abstraction means to simplify reality. For example, if you were designing an app you simplify / break down the smalled bits of data about the thing you want to recreate. Taking real world objects and 
and representing them within code.
- OOP is a programming paradigm based on the concept of objects. 
   - Objects contain data in the form of attributes or properties and actions in thr form or functions or methods. For example, computer monitor (object), size or resolution (properties), on/off brightness is functions or methods.
   - Abstraction  means to only show the necessary details to the user of the object. You only care about calling the method, not the underlying implementation.
   - Inhertiance, useful when you have an existing class and you want to build a new class that uses the stuff from the previous class but you want to add additional features.
   - Encapsulation, restircting access to properties or methods of your object, to prevent 
 

- abstraction means to simplify reality and focus only on the data and processes that are relevant to the application being built.
- encapsulation means that data and the programs that manipulate those data are bound together and their complexity is hidden
- inheritance means that a class can derive its methods and properties from another class this might result in an extensive hierarchy of superclasses and subclasses
- polymorphism means that different subclasses of the same superclass which therefore share the same interface can implement those interfaces in their own ways by overriding the code of the methods they inherit. Akkiws you to  you to determine what kind of function to run while the program is running. For example, the class is enemy (contains code), inheritance is making a vampire using that class, 
- Objects are the thing that you want to store and process data about.
- To program objects, you need a class. A class is a template for creating objects. It is an instance of a class in the computer's memory. For example, person.
- Attributes describe the object aka fields / properties. For example, person firsName, Gener, DOB
- Operations are actions that can be done to the object or performed by the object. Aka methods: programs within the class that are coded as procedures or functions.
- Encapsulation : Hides the data and complexity. Intended to hide and prevent errors. Senior programmers create classes of libraries where junior coders use and need the class name, properties, and methods available.
- Inheritance: A class can derive its methods and properties from another class. Inheritance defines type of relationships. The base class is the start of the hiearchy, sublasses derived from, and
- Polymorphism means that a class can implement an inherited method in its own way

---

</details>

<details>
 <summary>FireShip How to get good at programming</summary>

---
To be a good programmer, don't focus on remembering syntax, recognize patterns.  
Be a problem solver: Solve a bunch of problems / practice. Your goal is not ot have as many programming syntax but a system of learning the tools to solve problems. The best way to do this is to actually solve problems from easier to hard.
- I can actualy relate to this because learning sql was difficult when I didn't know what problems there are. So first identify the most common problems. Some are easier than others, 
Feynman learning technique: 
(1) Choose a topic
(2) Explain it to a 12 yr old
(3) Build something quickly, then improve after. Reflect, refine, simplify
(4) Organize and review. Share with someone more experienced then you

## Programming Fundementals Overview
My SUMMARY: The levels of languages. He used a few key terms I'll have ot further define such as general programming language. Complied 
- A computer doesn't directly understand javascript or c-sharp, it has to be compiled into something that the CPU understands. There are levels to programming languages, think of it as a scale from what humans write vs what the machine understands. The levels from bottom to top are
  - Hardware (bottom), to Machine language (Binary code), to assembly language, to general purpose languages like C C++ Rust, to interpreted languages (Python, C#, JAVA, JS)
      - C is a general purpose compiled proecural language. C++ is OOP that has more tools than C.
      - Rust Lang is modern low level language used for web and game development.
      - Java is a high level class based language. OOP. This language is compiled to bytecode for the Hava Virtual Machine (JVM).
      - Python is an interpreted language. Ruby is similar to python. Javascript is web browser language.
  - Compiled means a compiler translates the source code for the CPU to execute. Intepreted means a program, called an interpreter, run the code through a virtual machine like Python.
`Functions` are methods
`Objects` are classes that have variables, also called properties

---

</details>





<details>
 <summary>SOURCES</summary>

---
- FireShip - https://www.youtube.com/watch?v=NtfbWkxJTHw
- FireShip - https://www.youtube.com/watch?v=-uleG_Vecis
- Traversy Media - https://www.youtube.com/watch?v=2lVDktWK-pc
- freeCodeCamp - https://www.youtube.com/watch?v=zOjov-2OZ0E
---

</details>