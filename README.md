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
---
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


</details>
---

  - Assignment Operators
  - Comparison Operators
  - Logical Operators
  - Bitwise Operators




