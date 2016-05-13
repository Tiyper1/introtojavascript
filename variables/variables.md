# Introduction to JavaScript

## Variables
Variables allow you to assign values to a variable that is first declared using the var keyword. The variable then stores the value in memory for later use.
A variable can store any kind of javascript data type including another reference to a variable.
    
### Example 1
    /*
     * In this snippet we are going to declre a variable but not
     * assign a value to it.
     */
    
    var a; 
    
    console.log(a) //returns undefined cause a value has not been assigned;
### Example 2   
    /*
     * In this snippet we are going to declare a variable and then
     * assign a value to the variable.
     * /
    
    var a = "Hello, World!";
    
    console.log(a) //returns Hello, World!