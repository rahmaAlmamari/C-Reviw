#  **C# Multiple Choice**

## 1. Functions

 1. What keyword is used to define a function in C#?

    **A. method**   
    B. func  
    C. def  
    **D. void**

 2. What is the return type of a function that doesn't return anything?

    A. null  
    **B. void**  
    C. empty  
    D. none

 3. How do you call a method named Greet()?

    A. Greet[]  
    B. call Greet()  
    **C. Greet()**  
    D. Greet;

 4. What is the correct way to define a method with no parameters?

    A. void Hello[]  
    **B. void Hello()** 
    C. Hello{}  
    D. function Hello()

 5. What is the correct syntax to return a value from a method?

    A. send value;  
    B. value return;  
    **C. return value;** 
    D. break value;

 6. Where are parameters defined in a method?

    A. After return  
    B. Inside curly braces  
    **C. Inside parentheses**  
    D. Outside method body

 7. What does ref keyword do in method parameters?

    A. Copies value  
    B. Sends data by value  
    **C. Passes parameter by reference**  
    D. Returns multiple values

 8. What is a method signature?

    A. Only return type  
    B. Method name only  
    **C. Method name + parameter types**  
    D. Complete method body

 9. Can two methods have the same name with different parameters?

    A. No  
    B. Only in classes  
    **C. Yes, called overloading** 
    D. Only with ref parameters

 10. Which keyword stops method execution?

     A. break  
     B. stop  
     C. halt  
     **D. return**

 11. What does params keyword allow?

     A. Pass no parameters  
     B. Accept multiple fixed parameters  
     **C. Accept variable number of arguments**  
     D. Restrict parameter type

 12. What is a recursive function?

     A. Returns to main method  
     B. Repeats loop  
     **C. Calls itself**  
     D. Has multiple parameters

 13. What is the default return type if none is specified?

     A. int  
     B. object  
     C. void  
     **D. Error**

 14. What does static keyword in method mean?

     A. Can only run once  
     B. Belongs to instance 
     **C. Belongs to class**  
     D. Cannot return

 15. What is an anonymous method?

     A. Method with no return type  
     **B. Method with no name**  
     C. Static method  
     D. Global method

 16. Can a method return an array?

     **A. Yes**  
     B. No  
     C. Only void methods  
     D. Only using out

 17. What is the output type of int Add(int x, int y)?

     A. void  
     B. string  
     **C. int** 
     D. object

 18. What does out keyword do?

     A. Pass parameter by copy  
     **B. Return multiple values** 
     C. Prevent returning  
     D. Throw exception

 19. Can a function call itself in C#?

     A. No  
     B. Only in main  
     **C. Yes, that is recursion**  
     D. Only with loop

 20. What is the keyword to define a method inside a class?

     A. new  
     B. def  
     C. method  
     **D. void/int/etc**

 21. Which of the following is NOT a valid return type?

     A. int  
     B. string  
     C. decimal  
     **D. method**

 22. Can we have a method inside another method in C#?

     A. Yes  
     **B. No** 
     C. Only in main  
     D. Only using static

 23. How many return statements can a method have?

     A. Only one  
     B. None  
     **C. Multiple**  
     D. Unlimited if void

 24. What is the purpose of Main() method?

     A. Debugging  
     B. Default constructor  
     **C. Entry point**  
     D. Error handler

 25. Which of these can be method names?

     A. 1Method  
     B. method$  
     **C. _Method**  
     D. class

 26. How do you return nothing from a method?

     A. return null;  
     B. return void;  
     **C. return;** 
     D. void return;

 27. Can a method be both static and public?

    A. No  
    **B. Yes** 
    C. Only private  
    D. Only with void

 28. What happens if a non-void method doesn't return a value?

     A. Nothing  
     **B. Error** 
     C. Warning only  
     D. Null returned

 29. What is method overloading?

     A. Calling many methods  
     **B. Two methods with same name but different parameters**  
     C. Defining same method twice  
     D. Using loops in methods

 30. What is the purpose of async keyword in C# functions?

     A. Faster compile time  
     B. Enable multi-threading  
     **C. Allow await/async operations**  
     D. Return multiple results

## 2.  Loops

 1. Which loop guarantees at least one execution?

    A. for  
    B. while  
    **C. do-while**  
    D. foreach

 2. What is the output of this loop: for (int i = 0; i < 3; i++) Console.Write(i);?

    A. 123  
    **B. 012**  
    C. 345  
    D. 013

 3. Which keyword exits the current loop?

    A. return  
    B. stop  
    **C. break**  
    D. exit

 4. What does continue do inside a loop?

    A. Stops all loops  
    B. Skips the next loop  
    **C. Skips current iteration**  
    D. Ends loop

 5. Which loop is best when number of iterations is known?

    A. while  
    B. do-while  
    **C. for** 
    D. goto

## 3.  Arrays

1. What is the correct way to declare an array of 5 integers?

   A. int arr[5];  
   B. int arr = new int[5];  
   **C. int[] arr = new int[5];** 
   D. array<int> arr = 5;

 2. What is the index of the first element in a C# array?

    A. 1  
    **B. 0** 
    C. -1  
    D. Depends on OS

 3. How do you access the third element in an array named numbers?

    A. numbers(3)  
    **B. numbers[2]** 
    C. numbers{3}  
    D. numbers<3>

 4. What is the result of int[] x = new int[3];?

    A. x has 0 elements  
    **B. x has 3 elements all set to 0**
    C. x has null values  
    D. Syntax error

 5. What is the length of int[] a = {1, 2, 3, 4};?

    A. 3  
    **B. 4**  
    C. 5  
    D. Cannot be determined

## 4.  Exceptions

1. What keyword is used to catch exceptions?

   A. handle  
   **B. catch**  
   C. except  
   D. trap

 2. What does the try block do?

    A. Stops code  
    B. Tests a value  
    **C. Contains risky code**  
    D. Always runs first

 3. What is thrown when dividing by zero?

    A. ArithmeticException  
    **B. DivideByZeroException**
    C. NullReferenceException  
    D. ArgumentException

 4. Which block must follow a try block?

    A. handle  
    B. finally  
    **C. catch** 
    D. exit

 5. What does the finally block do?

    A. Runs only on error  
    B. Runs after catch  
    **C. Always runs** 
    D. Skips if no error

## 5.  Data Types

1. What is the default value of an int in C#?

   A. -1  
   B. null  
   **C. 0** 
   D. 1

 2. Which of the following is a value type?

    A. string  
    B. object  
    **C. int**  
    D. class

 3. What keyword is used to declare a variable that cannot be changed?

    A. static  
    B. readonly  
    **C. const**  
    D. immutable

 4. Which data type is used to store true or false values?

    A. int  
    B. boolean  
    **C. bool**  
    D. bit

 5. What is the size of a float in C#?

    A. 2 bytes  
    **B. 4 bytes**  
    C. 8 bytes  
    D. 1 byte

## 6. Operators

 1. What is the result of 5 + 3 * 2?

    **A. 11** 
    B. 16  
    C. 13  
    D. 10

 2. Which operator is used to check equality?

    A. =  
    B. :=  
    **C. ==** 
    D. ===

 3. What does the % operator do?

    A. Division  
    B. Multiplication  
    **C. Remainder** 
    D. Percentage

  4. Which operator is used to increase a value by 1?

     A. +=  
     **B. ++**
     C. inc  
     D. add

 5. What is the output of true && false?

    A. true  
    **B. false** 
    C. error  
    D. null

## 7.  Access Modifiers

 1. Which access modifier allows access from any class?

    A. private  
    **B. public** 
    C. internal  
    D. protected

 2. Which modifier restricts access to the same class only?

    A. public  
    B. protected  
    **C. private** 
    D. static

 3. What does the internal modifier mean?

    A. Access within same namespace  
    B. Access from other assemblies  
    C. Access only inside methods  
    **D. Access within same assembly**

 4. Which modifier allows access in derived classes only?

    A. private  
    **B. protected**
    C. internal  
    D. public

 5. What is the most restrictive access modifier?

    A. internal  
    B. protected  
    **C. private**
    D. sealed