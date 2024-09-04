Notes ->
- cd -> change directory
- when you run the program 1st you change the directory then you write node "folder name".


Javascript :- 

- javascript is a programming language which helps to write code to building sone logics.
- javascript is a high level programming language for building web apllication.
- jvascript works both frontend site and backend site.
- javascript is come from echma script so we see the latest version of javascript in the form of echma script.
- now we use javascript version 6 i.e ES6(Echma script)
- in another way echma script as the vanilla javascript.

variable:-

- variable is container to store the data.
- there are 3types of variable present over the javascript.

 1. LET:-

- let is type of variable which is used for changing variable name lettet.
- now a days,most of the cases we used let for creating variable.
- let is a block scope code so we have been using let for more cases.

2.VAR:-

- var is type of variable which is also used for changing the variable later stage.
- var is used in oldest broswer so now a days we are don't use var most of cases.

3.Const:-

- const is a type of variable where we can't change our further data.
- const means constant to store some data like numbers,integers etc.

Rules Foe creating variable:-

- variable names are case sensitive "a",&"A" is different.
- only letter,digit,underscore & is allowed.(not even space)
- only letter ,underscore or $ should be first character only.
-  reserved words cannot be variable names.

example of variable naming :- 
let ariz = "boy";
let ARIZ = "boy";
let _canada = "people"
let rudra = "good"

Data type in js:-

- data types in attributes associated with a peace of data tells a computer system how to interpet its value.
- in data types we used "tyepof" operator to know what type of data it is.
- mainly in javascript there are 2 types of data types.

1.Primitive:-

- in javascript their are 7 types of primitive data types.

1.Number- Number are the type of data type those it contain some numericall value
2.Boolean- in Boolean data types we got boolean value like true or false.
3.Undefined- in Undefined data types the data is not defined so that it will show undefined.
4.Null-in this data types we get null for the vlue means nothing.
5.biglnt-in biglnt we will get integer value.
6.symbol-in symbol we will get wholes symbol as well as the value we get for the data type.
7.string-String is a type of data type that can hold some character like name....

8.Referance or non-premitive:-

-> non primitive data type are the types of data type that can hold multiple items in a single time.
-> non primitive data type are -object array,function etc...
-> object is a non primitive data types which can hold multiple of item in one single entity..
-> mainly objects are workingb on (key value) pair.
-> the left side part is our key of object & right side part are the object of project.ex. object-
let student ={name:"rudra prasad pradhan", mob no-9861231580,college-"ceb"}

Operator in js:-

- operatior are the key features to do some task or operate some task.
- ex.A+B
- in this above example A,B are the operands & "+" is the operatior.
- there are 5 types of operatior are their in javascript.
 
1. arithmetic operator  
    (+,-,*,/)
    modulus -> %
    exponentiation -> **

2. unary operator 
    increment (++)
    decreament (--)

3. assignment operator
    (assign some values to the variables)
    (=, +=, -=, =, %=, *=)

4. comparison operator
    (compair the values)
    it gives the result of true or false. 
    equal to -> ==
    not equal to -> !=
    equal to & type -> ===
    not equal to & type -> !==

5. logical operator 
    checks the logic of the operator(true/false)
    logical AND (&&) -> table of logical AND operator is -> 
    cond1  cond2  res(&&)
    T       T      T
    T       F      F
    F       T      F
    F       F      F

    logical OR (||) -> table of logical OR operator is -> 
    cond1  cond2  res(&&)
    T       T      T
    T       F      T
    F       T      T
    F       F      F

    logical Not (!)

     there are 3 types of conditional statement are there 

1. if condition :- 
    - if condition is true then statement is true otherwise false. 
    syntax - 
    if(condition){
        statemeconditional statement :- 

- to implement some condition in the code.
- there nt
    }

2. if-else condition :- 
    - if condition is true then if bloack is executed otherwise its terminate to else condition.
    syntax - 
    if(condition){
        statement
    } else {
        statement
    }

3. else-if condition :- 
    - its check the condition multiple times where the condition is true. 
    syntax - 
    if(condition){
        statement
    } else if(condition){
        statement
    } else if(condition){
        statement
    } else {
        statement
    }

Loops in JS :- 

- loops are used to execute a piece of code again and again.
1. For Loop :-
    syntax - 
    for (initialization; condition; updation){
        statement
    }
    ex - 
    for(let i = 1;i <= 5; i++){
        console.log("web bocket")
    }

    web bocket
    web bocket
    web bocket
    web bocket