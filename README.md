# Java-Assignment-02
Assignment 2 (Variable and Data Types)


01) What do you understand by variable?

Variable in Java is a data container that saves the data values during Java program execution. Every variable is assigned a data type that designates the type and quantity of value it can hold. Variable is a memory location name of the data.


02)Name types of variables.

local variable.
instance variable.
static variable.


1) Local Variable
A variable declared inside the body of the method is called local variable. You can use this variable only within that method and the other methods in the class aren't even aware that the variable exists.

A local variable cannot be defined with "static" keyword.

2) Instance Variable
A variable declared inside the class but outside the body of the method, is called an instance variable. It is not declared as static.

It is called an instance variable because its value is instance-specific and is not shared among instances.

3) Static variable
A variable that is declared as static is called a static variable. It cannot be local. You can create a single copy of the static variable and share it among all the instances of the class. Memory allocation for static variables happens only once when the class is loaded in the memory.

Example to understand the types of variables in java
public class A  
{  
    static int m=100;//static variable  
    void method()  
    {    
        int n=90;//local variable    
    }  
    public static void main(String args[])  
    {  
        int data=50;//instance variable    
    }  
}//end of class   
Java Variable Example: Add Two Numbers
public class Simple{    
public static void main(String[] args){    
int a=10;    
int b=10;    
int c=a+b;    
System.out.println(c);    
}  
}    
Output:

20
Java Variable Example: Widening
public class Simple{  
public static void main(String[] args){  
int a=10;  
float f=a;  
System.out.println(a);  
System.out.println(f);  
}}  
Output:


10
10.0
Java Variable Example: Narrowing (Typecasting)
public class Simple{  
public static void main(String[] args){  
float f=10.5f;  
//int a=f;//Compile time error  
int a=(int)f;  
System.out.println(f);  
System.out.println(a);  
}}  
Output:

10.5
10
Java Variable Example: Overflow
class Simple{  
public static void main(String[] args){  
//Overflow  
int a=130;  
byte b=(byte)a;  
System.out.println(a);  
System.out.println(b);  
}}  
Output:

130
-126
Java Variable Example: Adding Lower Type
class Simple{  
public static void main(String[] args){  
byte a=10;  
byte b=10;  
//byte c=a+b;//Compile Time Error: because a+b=20 will be int  
byte c=(byte)(a+b);  
System.out.println(c);  
}}  
Output:

20


3)What is the difference between static and instance variables?



<img width="497" alt="difference " src="https://user-images.githubusercontent.com/102998720/170761199-6f3bd8e7-aac0-41d6-bee9-1c4a1ed6263c.png">



4)Which type of variable requires a keyword to determine its scope?

Static Veriable.


5)Which thing specifies the size and type of variable?

A primitive data type specifies the size and type of variable values, and it has no additional methods.



6)Can we use a variable without declaring it?

We can use strict mode which is a new feature in ECMAScript 5 that allows you to place a program, or a function, in a “strict” operating context. It will throw Reference error : x is not defined, when we assign a value to a variable without declaring it.


7)How can we declare a variable?

To declare (create) a variable, you will specify the type, leave at least one space, then the name for the variable and end the line with a semicolon ( ; ). Java uses the keyword int for integer, double for a floating point number (a double precision number), and boolean for a Boolean value (true or false).



8)How can we initialize a variable?

The way of initializing a variable is very similar to the use of PARAMETER attribute. More precisely, do the following to initial a variable with the value of an expression: add an equal sign (=) to the right of a variable name. to the right of the equal sign, write an expression.


9)Make a list of common Java data types.

Data types are divided into two groups:
A)Primitive data types - includes byte , short , int , long , float , double , boolean and char.
B)Non-primitive data types - such as String , Arrays and Classes (you will learn more about these in a later chapter)


10)Which data types are created by programmers and are not defined by Java?

Non-primitive types are created by the programmer and is not defined by Java. Non Primitive types can be used to call methods to perform certain operations, while primitive types cannot. A primitive type always has a value, whereas non-primitive types can be null.


11)Java has how many primitive data types?

The eight primitive data types supported by the Java programming language 
includes byte , short , int , long , float , double , boolean and char.


12)What data type would you use for storing the number of students in a class?




What data type would you use for storing the average test score in a class?
How would you declare a variable storing the tax rate?
How would you declare a variable that tells the grade (A, B, C, or D) of students?
List the name conventions you learned in class about variables.
Name the Data type used for an object 'Pen'.
Write a program and declare the variable of each data type you learned in class. Initialize each variable with appropriate values and print them.
Write a program to print your name, email, address, phone number, and id.
What do you understand by typecasting?
In which type casting Java automatically converts one data type to another data type?
Write a program to convert int to double and print a message stating which type casting you did?
Write a program to convert double to int and print a message stating which type casting you did?
Write a program to convert int to string and print a message stating which type casting you did?
Write a program to convert string to int and print a message stating which type casting you did?
Write a program to convert float to double and print a message stating which type casting you did?
Write a program to convert byte to float and print a message stating which type casting you did?
Write a Java program to get the character at the 5th index of the String “automation”.
Write a program to find the length of the string "automation".
Write a Java program to concatenate a string “Java” to the end of another string “C#”.
Write a Java program to compare a string “automation” and another string “Automation”.
Write a Java program to check whether a string “Software” ends with the contents of another string “Hardware”.
Write a Java program to replace a character “n” with character “m” in the string “Automation”.
Write a Java program to check whether a string “Java is my favorite programming Lang” starts with the contents of another string “Python is my favorite programming language”.
Write a program to get a substring of the string “Let this be the last year tha you doubt yourself, fear, change or quit. Never give up” starting from index 10 and ending at index 26.
Write a Java program to convert all the characters in a string “YourName” to lowercase.
Write a Java program to convert all the characters in a string “YourName” to uppercase.
Write a program to reverse a string “ Java is my favorite”.
Assignment 3 (Operators)
What are operators?
Write the types of operators you studied in class.
The operators used in Arithmetic expressions can be classified into which type?
Examine the following code. The programmer is not getting the same value for result and result2. Why? double result = (20-10/3); double result = ((20-10)/3);
Write a program to check if the two numbers 23 and 45 are equal.
Write a Java program to find the value of specified expression. a. 301 + 0) / 5 b. 7.0e-6 * 10000000.1 c. true && true d. false && true e. (false && false) || (true && true) f. (false || false) && (true && true)
Length and breadth of a rectangle are 9 and 5 respectively. Write a program to calculate the area and perimeter of the rectangle.
Write a program to calculate the perimeter of a triangle having sides of length 9,6 and 5 units.
Write a program to find if both the conditions 'a < 50' and 'a < b' are true when value of a is 45 and b is 67.
Write a program to find total marks and percentage of students when his marks in three subjects are 87, 39 and 52 respectively (each out of 100 ).
Write a program to convert temperature from Fahrenheit to Celsius degree. (You can take temperature of your choice)
Write a program to find largest number among three numbers: 76,54 and 89.
Write a program to find smallest number among three numbers: 76,54 and 89.
If num1=5 and num2=4 then write a program to swap values of these numbers.
Write a program to convert positive number to negative number. (You can take any number of your choice)
Consider the following code snippet. arrayOfInts[j] > arrayOfInts[j+1] a. Which operators does the code contain?
Consider the following code snippet. int i = 10; int n = i++%5; a. What are the values of i and n after the code is executed? b. What are the final values of i and n if instead of using the postfix increment operator (i++), you use the prefix version (++i))?
To invert the value of a boolean, which operator would you use?
Write a program to show the difference between postfix expr ++ and prefix ++ expr operators. In the comments of your program explain each line of code.
Write a program to show the difference between postfix expr -- and prefix -- expr operators. In the comments of your program explain each line of code.
Which operator is used to compare two values, = or == ?
Explain the following code sample: result = someCondition ? value1 : value2;
Write a program to divide 154 with 7.
Write a program to print the sum, product, difference, divide and remainder of two numbers (First number=579 and second number=17).
Write a Java program to print the area and perimeter of a circle when radius of circle is 4.2 cm.
Write a program that compares two number 13 and 16 are not equal.
Write a program to decrease value of variable by 1 without using arithmetic operator. (Value of variable is 13)
Write a program to increase value of variable by 1 without using arithmetic operator. (Value of variable is 13)
Write a program that shows the message true first number is greater than second number or third number. (First number= 23, Second number = 32 and third number = 15).
Write a program that shows message true first number is greater than second number and third number. (First number= 23, Second number = 32 and third number = 15).

