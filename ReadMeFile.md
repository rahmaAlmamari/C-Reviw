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

## 8.  Input/Output

 1. Which method is used to read user input from the console?

    A. Console.Read()  
    **B. Console.ReadLine()**  
    C. Input.Read()  
    D. System.Input()

 2. What is the return type of Console.ReadLine()?

    A. int  
    B. char  
    **C. string**
    D. object

 3. How do you write output to the console?

    A. print()  
    B. Console.Output()  
    **C. Console.WriteLine()** 
    D. System.Write()

 4. What does Console.Write() do differently from Console.WriteLine()?

    A. Adds a newline  
    B. Reads input  
    **C. Does not add a newline** 
    D. Adds a space

 5. How to read a single character from the console?

    A. Console.ReadChar()  
    B. Console.ReadLine()[0]  
    **C. Console.ReadKey().KeyChar**
    D. Console.Read().Char

 6. Which namespace contains console input/output functions?

    A. System.IO  
    B. System.Console  
    C. System.Text  
    **D. System**

 7. How do you format a string in WriteLine()?

    A. Console.WriteLine("Hi " + name)  
    B. Console.WriteLine("Hi {0}", name)  
    C. Console.WriteLine($"Hi{name}")  
    **D. All of the above**

 8. Which function pauses for a key press?

    A. Console.Wait()  
    B. Console.ReadLine()  
    **C. Console.ReadKey()**
    D. Console.Hold()

 9. What does Console.Read() return?

    **A. string**  
    B. char  
    C. int  
    D. object

 10. Which method is used to clear the console screen?

     **A. Console.Clear()**  
     B. Console.Erase()  
     C. Console.Reset()  
     D. Console.Flush()

 11. What is the purpose of Console.Error.WriteLine()?

     A. Display warnings  
     **B. Display errors**  
     C. Log debug  
     D. Input from user

 12. What is printed by this code?  Console.Write("X"); Console.Write("Y");

     A. X Y  
     B. X  
     **C. XY** 
     D. X\nY

 13. What happens if you enter a number and read it with Console.ReadLine()?

     **A. Stored as string**
     B. Stored as int  
     C. Compiler error  
     D. Exception

 14. How to convert string input to integer safely?

     A. Convert.ToInt32()  
     B. int.Parse()  
     C. int.TryParse()  
     **D. All of them**

 15. What happens if int.Parse("abc") is executed?

     A. 0  
     B. null  
     **C. Exception**  
     D. "abc"

 16. Which method is preferred to avoid exceptions while parsing?

     A. Convert.ToInt32()  
     B. int.Parse()  
     **C. int.TryParse()**
     D. ParseExact()

 17. What does this print?  Console.Write("A"); Console.WriteLine("B");

     A. A B  
     **B. AB** 
     C. A\nB  
     D. A \n B

 18. What does Console.BackgroundColor affect?

     A. Text color  
     B. Console window  
     **C. Console background**  
     D. Console size

 19. What method sets cursor position on screen?

     A. Console.SetCursor()  
     B. Console.MoveTo()  
     **C. Console.SetCursorPosition()**  
     D. Console.Cursor()

  20. Which method reads a key without displaying it?

      **A. Console.ReadKey(true)** 
      B. Console.ReadKey(false)  
      C. Console.Read()  
      D. Console.ReadLine()

 21. Which of these clears user input in the console?

     **A. Console.Clear()**  
     B. Console.Reset()  
     C. Console.Close()  
     D. Console.Clean()

 22. Can Console.WriteLine() output formatted values?

     **A. Yes**
     B. No  
     C. Only strings  
     D. Only variables

 23. Which method is best for secure password input?

     A. Console.ReadLine()  
     B. Console.Read()  
     C. Console.ReadKey(true)  
     **D. Console.GetPassword()**

 24. What does Console.Title = "App" do?

     A. Prints title  
     **B. Sets window title**
     C. Declares variable  
     D. Renames console

 25. Which key property can you read from Console.ReadKey()?

     **A. Key**
     B. Value  
     C. Char  
     D. Input

  26. How do you change the text color in console?

      A. Console.FontColor  
      B. Console.ForegroundColor  
      **C. Console.TextColor** 
      D. Console.Color

 27. What does Console.WriteLine("\nHello") print?

     A. Hello  
     B. \nHello  
     **C. (newline)Hello**
     D. Error

 28. What happens if you press Enter on Console.ReadKey()?

     A. It waits  
     B. It throws error  
     **C. It returns key info**
     D. It exits app

 29. Can you write to console without newline?

     **A. Yes, with Write()**
     B. No  
     C. Only WriteLine()  
     D. Only with flush

 30. What is the purpose of Console.In?

     A. Reads keyboard  
     B. Controls file output  
     **C. Handles standard input stream** 
     D. Closes console

## 9.  File Handling

 1. Which namespace is required for file operations?

    A .System.Data  
    **B. System.IO** 
    C. System.Files  
    D. System.FileHandling

 2. What class is used to read text files line by line?

    A. Stream  
    B. File  
    **C. StreamReader** 
    D. FileReader

 3. What class is used to write text to a file?

    A. FileStream  
    B. FileWriter  
    **C. StreamWriter**  
    D. TextWriter

  4. Which method reads all lines from a file into a string array?

     A. File.Read()  
     B. File.ReadLines()  
     **C. File.ReadAllLines()** 
     D. File.GetLines()

 5. Which method creates a file if it doesn't exist?

    A. File.Make()  
    **B. File.Create()**  
    C. File.Open() 
    D. File.Build()

 6. What happens if you use File.Create() on an existing file?

    A. Appends content  
    B. Deletes the file  
    C. Overwrites it  
    **D. Throws an error**

 7. What does File.Exists("data.txt") return?

    A. void  
    B. string  
    **C. bool**  
    D. file object

 8. What method is used to delete a file?

    A. File.Drop()  
    B. File.Remove()  
    **C. File.Delete()** 
    D. File.Cut()
 
 9. What type does File.ReadAllText() return?

    **A. string**  
    B. char array  
    C. int  
    D. FileStream

 10. How do you append text to a file?

     A. File.WriteAppend()  
     B. File.WriteAllLines()  
     **C. File.AppendAllText()** 
     D. File.ContinueWrite()

 11. Which stream is unidirectional and used only for reading?

     **A. StreamReader** 
     B. FileStream  
     C. StreamWriter  
     D. MemoryStream

 12. Which exception occurs if the file path is wrong?

     A. IOException  
     **B. FileNotFoundException** 
     C. PathException
     D. NullReferenceException
 
 13. What does StreamWriter.WriteLine() do?

     **A. Reads file**  
     B. Appends binary  
     C. Writes text and newline  
     D. Opens file dialog

 14. What is the default encoding used by StreamWriter?

    A. ASCII  
    **B. UTF8**  
    C. UTF16  
    D. Binary

 15. How do you close a file after reading with StreamReader?

     A. Dispose()  
     B. End()  
     **C. Close()**  
     D. Stop()

 16. What happens if StreamWriter is not closed?

     A. No issue  
     **B. File may lock or data may not write**  
     C. Exception occurs  
     D. File gets deleted

 17. Which method allows reading file content line by line in a loop?

     A. ReadAllLines()  
     **B. ReadLine()**  
     C. ReadFile()  
     D. GetNextLine()
 
18. What is the correct way to use a StreamReader with using?

    **A. using(StreamReader sr = new StreamReader(path))**  
    B. using FileReader  
    C. using.Read(path)  
    D. open sr(path)

19. What type of file can File.WriteAllBytes() handle?
    A. text only  
    **B. binary files**  
    C. csv  
    D. XML only

20. What does File.Copy(source, destination) do?

    A. Moves file  
    B. Reads source only  
    **C. Duplicates file**  
    D. Renames file

21. Which stream allows both reading and writing to a file?

    A. BinaryReader  
    **B. FileStream** 
    C. StreamReader  
    D. None
  
22. What exception occurs when writing to a read-only file?

    A. InvalidFileException  
    **B. UnauthorizedAccessException** 
    C. IOException  
    D. WriteDeniedException

23. Can you read and write to a file at the same time in C#?

    A. No  
    **B. Bl Yes, with FileStream** 
    C. Cl Only with File class  
    D. Only in async methods

24. How to overwrite a file's content?

    A. File.AppendAllText()  
    B. File.Delete() then write  
    **C. File.WriteAllText()**  
    D. File.Continue()

25. How to read binary data from a file?

    **A. BinaryReader**  
    B. StreamReader  
    C. FileTextReader  
    D. TextParser

26. What is Path.Combine() used for?

    A. Compress files  
    B. Format file content  
    **C. Combine folder and file paths**  
    D. Append data

27. How can you check file creation time?

    **A. File.GetCreationTime(path)** 
    B. File.CheckTime()  
    C. File.Info(path).Created  
    D. path.CreatedTime()

28. How do you check if a directory exists?

    A. Directory.Check()  
    **B. Directory.Exists()** 
    C. File.IsFolder()  
    D. IO.Directory.Check()

29. How to create a new folder in C#?

    A. File.CreateFolder()  
    B. IO.NewFolder()  
    **C. Directory.CreateDirectory()**  
    D. Folder.Make()

30. What method lists all files in a directory?

    **A. Directory.GetFiles()** 
    B. File.ListAll()  
    C. Directory.ReadAll() 
    D. IO.Directory.Files()