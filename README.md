# Java
### Java Programming Language
- Java is one of the most popular and widely used programming languages and platforms.
- Java is fast, reliable, and secure.
-  Java is used in every nook and corner from desktop to web applications, scientific supercomputers to gaming consoles, cell phones to the Internet.
### Steps to Implement Java Program
1. Creating the program
2. Compiling the program
3. Running the program
### Data Types
- Data types in Java are of different sizes and values that can be stored in the variable that is made as per convenience and circumstances to cover up all test cases.
- Java has two categories in which data types are segregated
  - **Primitive Data Type:** such as boolean, char, int, short, byte, long, float, and double. The Boolean with uppercase B is a wrapper class for the primitive data type boolean in Java.
  - **Non-Primitive Data Type or Object Data type:** such as String, Array, Class, Object, Interfaces, enum  etc. <br>
  ![data-types-in-java](https://github.com/user-attachments/assets/139afede-6fe2-4905-8c15-ce177eea992d)

#### Primitive Data Types
- A primitive data type specifies the type of a variable and the kind of values it can hold.
- **Integer types** stores whole numbers, positive or negative (such as 123 or -456), without decimals. Valid types are `byte`, `short`, `int` and `long`.
- **Floating point types** represents numbers with a fractional part, containing one or more decimals. There are two types: `float` and `double`.
 ![Primitive](https://github.com/user-attachments/assets/7107fc99-a9b2-4c94-bbed-3373fe6826e3)

#### Non-Primitive Data Types
- Non-primitive data types are called reference types because they refer to objects.
- They are unable to immediately store the value of a variable in memory. They save the variable's memory address.
- They are String, Array, Class, Object, Interfaces, enum  etc.

#### Java Variables
- Variables are the containers for storing the data values or you can also call it a memory location name for the data.
- Every variable has a:
  - **Data Type** – The kind of data that it can hold. For Example:
    - `String` - stores text, such as "Hello". String values are surrounded by double quotes
    - `int` - stores integers (whole numbers), without decimals, such as 123 or -123
    - `float` - stores floating point numbers, with decimals, such as 19.99 or -19.99
    - `char` - stores single characters, such as 'a' or 'B'. Char values are surrounded by single quotes
    - `boolean` - stores values with two states: true or false
  - **Variable Name** - To identify the variable uniquely within the scope.
  - **Value** - The data assigned to the variable.
#### Types of Java Variables
- **Local Variables**
  - A variable defined within a block or method or constructor is called a local variable.
    ```java
    // Java Program to show the use of local variables
    import java.io.*;

    class GFG {
        public static void main(String[] args)
        {
            // Declared a Local Variable
            int var = 10;

            // This variable is local to this main method only
            System.out.println("Local Variable: " + var);
        }
    }
    ```
- Instance Variables
  - Instance variables are non-static variables and are declared in a class outside of any method, constructor, or block.
    ```java
    class GFG
    {
    // Instance Variables
    public String name;
    public int age;

    // Constructor to initialize instance variables
    public GFG()
    {
        this.name = "John Doe";
        this.age = 25;
    }

    public static void main(String[] args)
    {
        // Create an object
        GFG obj = new GFG();

        // Access instance variables
        System.out.println("Name: " + obj.name);
        System.out.println("Age: " + obj.age);
    }
    }
    ```
- Static Variables
  - Static variables are also known as class variables. These variables are declared similarly to instance variables. The difference is that static variables are declared using the static keyword within a class outside of any method, constructor, or block.
    ```java
    import java.io.*;

    class GFG {
        // Declared static variable
        public static String geek = "Shubham Jain";
  
        public static void main(String[] args)
        {
            // Accessing the static variable without object creation
            System.out.println("Geek Name is : " + GFG.geek);

        
        }
    }
    ```
### Java Keywords
- Keywords are the Reserved words in a programming language that are used for some internal process or represent some predefined actions. These words are therefore not allowed to use as variable names or objects.
  ![java-keywords](https://github.com/user-attachments/assets/0f0d4a02-a444-49cb-96b9-0109255c05b7)
  <br>
<details>
<summary>Click to expand and see explanations for Java keywords</summary>

### Java Keywords Explained

1. **`abstract`**: Used to declare an abstract class or method, which cannot be instantiated directly and must be extended or implemented.

2. **`assert`**: Used for debugging purposes to test assumptions in the code. If the assertion is false, an `AssertionError` is thrown.

3. **`boolean`**: A data type that can hold only two values: `true` or `false`.

4. **`break`**: Used to exit a loop or switch statement prematurely.

5. **`byte`**: A data type that can hold an 8-bit integer value.

6. **`case`**: Used in switch statements to define a block of code to be executed if the case matches the switch expression.

7. **`catch`**: Used in exception handling to catch exceptions thrown in a `try` block.

8. **`char`**: A data type that can hold a single 16-bit Unicode character.

9. **`class`**: Used to declare a class, which is a blueprint for creating objects.

10. **`const`**: Reserved for future use (not currently used in Java).

11. **`continue`**: Used to skip the current iteration of a loop and proceed to the next iteration.

12. **`default`**: Used in switch statements to define a block of code to be executed if no case matches the switch expression.

13. **`do`**: Used to create a do-while loop, which executes a block of code at least once before checking the loop condition.

14. **`double`**: A data type that can hold a 64-bit floating-point number.

15. **`else`**: Used in if-else statements to define a block of code to be executed if the if condition is false.

16. **`enum`**: Used to define a set of named constants (enumerations).

17. **`extends`**: Used to create a subclass that inherits from a superclass.

18. **`final`**: Used to declare a constant variable, a method that cannot be overridden, or a class that cannot be extended.

19. **`finally`**: Used in exception handling to define a block of code that will always be executed, regardless of whether an exception is thrown.

20. **`float`**: A data type that can hold a 32-bit floating-point number.

21. **`for`**: Used to create a for loop, which repeats a block of code a specified number of times.

22. **`goto`**: Reserved for future use (not currently used in Java).

23. **`if`**: Used to create an if statement, which executes a block of code if a specified condition is true.

24. **`implements`**: Used to implement an interface in a class.

25. **`import`**: Used to import classes or packages into the current file.

26. **`instanceof`**: Used to check if an object is an instance of a specific class or interface.

27. **`int`**: A data type that can hold a 32-bit integer value.

28. **`interface`**: Used to declare an interface, which is a collection of abstract methods.

29. **`long`**: A data type that can hold a 64-bit integer value.

30. **`native`**: Used to indicate that a method is implemented in native code (e.g., C/C++).

31. **`new`**: Used to create a new object or array.

32. **`package`**: Used to declare a package, which is a namespace for organizing classes.

33. **`private`**: An access modifier that restricts access to the declared member to within the class.

34. **`protected`**: An access modifier that restricts access to the declared member to within the package and subclasses.

35. **`public`**: An access modifier that allows access to the declared member from anywhere.

36. **`return`**: Used to return a value from a method.

37. **`short`**: A data type that can hold a 16-bit integer value.

38. **`static`**: Used to declare a class-level variable or method that belongs to the class rather than an instance of the class.

39. **`strictfp`**: Used to ensure consistent floating-point calculations across different platforms.

40. **`super`**: Used to refer to the superclass (parent class) of the current object.

41. **`switch`**: Used to create a switch statement, which allows a variable to be tested for equality against a list of values.

42. **`synchronized`**: Used to create synchronized methods or blocks, which ensure that only one thread can access the resource at a time.

43. **`this`**: Used to refer to the current object.

44. **`throw`**: Used to explicitly throw an exception.

45. **`throws`**: Used in method declarations to specify the exceptions that the method might throw.

46. **`transient`**: Used to indicate that a variable should not be serialized.

47. **`try`**: Used to define a block of code that might throw an exception.

48. **`void`**: Used to indicate that a method does not return any value.

49. **`volatile`**: Used to indicate that a variable's value may be modified by multiple threads.

50. **`while`**: Used to create a while loop, which repeats a block of code as long as a specified condition is true.

</details>

### Java Operators
- Java operators are special symbols that perform operations on variables or values. They can be classified into several categories based on their functionality.
- Java divides the operators into the following groups:
  - Arithmetic Operators
  - Assignment Operators
  - Comparison Operators
  - Logical Operators
  - Bitwise Operators

<details>
<summary>Click to expand and see explanations for Java Operators</summary>
  
#### **Arithmetic Operators**
| Operator | Name          | Description                          | Example     |
|----------|---------------|--------------------------------------|-------------|
| `+`      | Addition      | Adds together two values             | `x + y`     |
| `-`      | Subtraction   | Subtracts one value from another     | `x - y`     |
| `*`      | Multiplication| Multiplies two values                | `x * y`     |
| `/`      | Division      | Divides one value by another         | `x / y`     |
| `%`      | Modulus       | Returns the division remainder       | `x % y`     |
| `++`     | Increment     | Increases the value of a variable by 1 | `++x`      |
| `--`     | Decrement     | Decreases the value of a variable by 1 | `--x`      |

#### **Assignment Operators**
| Operator | Name                  | Description                          | Example     |
|----------|-----------------------|--------------------------------------|-------------|
| `=`      | Assignment            | Assigns a value to a variable        | `x = 5`     |
| `+=`     | Addition Assignment   | Adds and assigns a value             | `x += 3`    |
| `-=`     | Subtraction Assignment| Subtracts and assigns a value        | `x -= 2`    |
| `*=`     | Multiplication Assignment | Multiplies and assigns a value    | `x *= 4`    |
| `/=`     | Division Assignment   | Divides and assigns a value          | `x /= 2`    |
| `%=`     | Modulus Assignment    | Assigns the remainder of a division  | `x %= 3`    |

#### **Comparison Operators**
| Operator | Name                  | Description                          | Example     |
|----------|-----------------------|--------------------------------------|-------------|
| `==`     | Equal to              | Checks if two values are equal       | `x == y`    |
| `!=`     | Not equal             | Checks if two values are not equal   | `x != y`    |
| `>`      | Greater than          | Checks if one value is greater than another | `x > y`  |
| `<`      | Less than             | Checks if one value is less than another    | `x < y`  |
| `>=`     | Greater than or equal to | Checks if one value is greater than or equal to another | `x >= y` |
| `<=`     | Less than or equal to | Checks if one value is less than or equal to another    | `x <= y` |

#### **Logical Operators**
| Operator | Name          | Description                          | Example       |
|----------|---------------|--------------------------------------|---------------|
| `&&`     | Logical AND   | Returns true if both conditions are true | `x && y`    |
| `||`    | Logical OR    | Returns true if at least one condition is true | `x || y` |
| `!`      | Logical NOT   | Reverses the result of a condition   | `!x`          |

#### **Bitwise Operators**
| Operator | Name                  | Description                          | Example     |
|----------|-----------------------|--------------------------------------|-------------|
| `&`      | Bitwise AND           | Performs AND operation on bits       | `x & y`     |
| `|`      | Bitwise OR            | Performs OR operation on bits        | `x | y`     |
| `~`      | Bitwise NOT           | Inverts all the bits                 | `~x`        |
| `<<`     | Left Shift            | Shifts bits to the left              | `x << 2`    |
| `>>`     | Right Shift           | Shifts bits to the right             | `x >> 2`    |
| `>>>`    | Unsigned Right Shift  | Shifts bits to the right (unsigned)  | `x >>> 2`   |

</details>

### Statements
- Decision-making statements in Java execute a block of code based on a condition.
- A programming language uses control statements to control the flow of execution of a program based on certain conditions. These are used to cause the flow of execution to advance and branch based on changes to the state of a program.
- **Types of Decision Making Statements in Java**
  - if, 
  - if-else, 
  - else-if, 
  - nested-if-else
  - Switch-case
1. **if statement**
   - `if` statement is used to specify a block of Java code to be executed if a condition is `true`.
   - Syntax
     ```java
     if (condition) {
        // block of code to be executed if the condition is true
     }
     ```
   - Example:
     ```java
     int x = 20;
     int y = 18;
     if (x > y) {
       System.out.println("x is greater than y");
     }
     ```
  2. **if-else statement**
     - `else` statement is used to specify a block of code to be executed if the condition is `false`.
     - Syntax
       ```java
       if (condition) {
         // block of code to be executed if the condition is true
       } else {
         // block of code to be executed if the condition is false
       }
       ```
     - Example
       ```java
       int time = 20;
       if (time < 18) {
         System.out.println("Good day.");
       } else {
         System.out.println("Good evening.");
       }
       // Outputs "Good evening."
       ```
  3. **else-if Statement**
     - `else if` statement is used to specify a new condition if the first condition is `false`.
     - Syntax
       ```java
       if (condition1) {
         // block of code to be executed if condition1 is true
       } else if (condition2) {
         // block of code to be executed if the condition1 is false and condition2 is true
       } else {
         // block of code to be executed if the condition1 is false and condition2 is false
       }
     - Example:
       ```java
       int time = 22;
       if (time < 10) {
         System.out.println("Good morning.");
       } else if (time < 18) {
         System.out.println("Good day.");
       } else {
         System.out.println("Good evening.");
       }
       // Outputs "Good evening."
       ```
  4. **nested-if Statement**
     - A nested if is an if statement that is the target of another if or else. Nested if statements mean an if statement inside an if statement. i.e, we can place an if statement inside another if statement.
     - Syntax
     ```java
     if (condition1)  {    
     // Executes when condition1 is true    
     if (condition2)
     {       
     // Executes when condition2 is true    
     }
     else
     {
     // Executes when both condition is false
     }
     }
     ```
     - Example:
       ```java
       int age = 20;
       boolean hasID = true;
       if (age >= 18) {                  // Outer if
       if (hasID) {                  // Nested if (inner if)
        System.out.println("Welcome! You can enter.");
       } else {
        System.out.println("You need an ID to enter.");
       }
       } else {
       System.out.println("You are too young to enter.");
       }
       ```
  5. **Switch Case**
     - The switch statement is a multiway branch statement. It provides an easy way to dispatch execution to different parts of code based on the value of the expression.
     - Syntax
       ```java
       switch (expression) {
           case value1:
                // code to be executed if expression == value1
                break;
           case value2:
                // code to be executed if expression == value2
                break;
           // more cases…
           default:
               // code to be executed if no cases match

       }
       ```
     - Example:
       ```java
       // Java program to demonstrates the
       //  working of switch statements
       import java.io.*;

       class Geeks {
           public static void main(String[] args)
           {
               int num = 20;
               switch (num) {
               case 5:
                   System.out.println("It is 5");
                   break;
               case 10:
                   System.out.println("It is 10");
                   break;
               case 15:
                   System.out.println("It is 15");
                   break;
               case 20:
                   System.out.println("It is 20");
                   break;
               default:
                   System.out.println("Not present");
               }
           }
       }
       ```
6. **jump Statements**
   - Java supports three jump statements: `break`, `continue` and `return`. These three statements transfer control to another part of the program.
   - `break` -  Terminates a sequence in a switch statement (discussed above).
   - `continue`
     ```java
     // Java program to demonstrates the use of
     // continue in an if statement
     import java.util.*;

     class Geeks {
     public static void main(String args[])
     {
        for (int i = 0; i < 10; i++) {
          
            // If the number is even
            // skip and continue
            if (i % 2 == 0)
                continue;

            // If number is odd, print it
            System.out.print(i + " ");
        }
        }
        }
     ```
   - `return` - The return statement is used to explicitly return from a method. i.e, it causes program control to transfer back to the caller of the method.
     ```java
     // Java program to demonstrate the use of return
      import java.util.*;

      public class Geeks {
      public static void main(String args[])
      {
        boolean t = true;
        System.out.println("Before the return.");

        if (t)
            return;

        // Compiler will bypass every statement
        // after return
        System.out.println("This won't execute.");
      }
      }
     ```



### Java Strings
A string is an object that stores a sequence of characters in double quotes, using UTF-16 encoding (16 bits per character). It behaves like a character array. Java offers a powerful API for string operations like concatenation, comparison, and manipulation.
- Example:
```java
// Java Program to demonstrate String
public class Geeks {
    // Main Function
    public static void main(String args[])
    {
        // creating Java string using new keyword
        String str = new String("The one and only Gyanaaraaanjaan Mallick");
        System.out.println(str);
    }
}
```
- Ways of Creating a Java String
  - String Literal
    - To make Java more memory efficient (because no new objects are created if it exists already in the string constant pool).
    - Example:
      ```java
      String demoString = “data-given”; 
  - Using new Keyword
    - ```String s = new String(“Welcome”);```
    - In such a case, JVM will create a new string object in normal (non-pool) heap memory and the literal “Welcome” will be placed in the string constant pool. The variable s will refer to the object in the heap (non-pool).

### Arrays in Java
- Arrays are fundamental structures in Java that allow us to store multiple values of the same type in a single variable. They are useful for storing and managing collections of data.
-  Arrays in Java are objects.
-  Example:
```java
public class Main {
    public static void main(String[] args)
    {
        // initializing array
        int[] arr = { 1, 2, 3, 4, 5 };
        // size of array
        int n = arr.length;
        // traversing array
        for (int i = 0; i < n; i++)
            System.out.print(arr[i] + " ");
    }
}
// output: 1 2 3 4 5
```
### Stream In Java
Stream API is used to process collections of objects. A stream in Java is a sequence of objects that supports various methods that can be pipelined to produce the desired result. 
- Stream API is a way to express and process collections of objects.
- Enable us to perform operations like filtering, mapping, reducing, and sorting.
- Syntax
```java
Stream<T> stream;
```
- Here `T` is either a class, object, or data type depending upon the declaration.

### Classes and Objects in Java
- In Java, classes and objects are basic concepts of Object Oriented Programming (OOPs).
- The class represents a group of objects having similar properties and behavior.
Here’s a table summarizing the differences between a **Class** and an **Object**:

| **Aspect**               | **Class**                                                                 | **Object**                                                                 |
|--------------------------|---------------------------------------------------------------------------|----------------------------------------------------------------------------|
| **Definition**           | A blueprint or template for creating objects.                            | An instance of a class.                                                   |
| **Memory Allocation**    | No memory is allocated when a class is declared.                         | Memory is allocated when an object is created.                            |
| **Nature**               | A logical entity.                                                        | A physical entity.                                                        |
| **Purpose**              | Represents a group of similar objects.                                   | Represents a real-world entity (e.g., book, car, etc.).                   |
| **Declaration/Creation** | A class is declared once.                                                | Objects can be created multiple times as per requirement.                 |
| **Example**              | A class can be "Car."                                                    | Objects of the class "Car" can be BMW, Mercedes, Ferrari, etc.            |

### Java Classes
- A class in Java is a set of objects which shares common characteristics and common properties.
