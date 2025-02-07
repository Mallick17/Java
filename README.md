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
  




