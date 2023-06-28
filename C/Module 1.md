# Module 1: Introduction to Programming and C Basics
### 1.1: Introduction to computer programming
   - Computer programming is the process of creating instructions for a computer to perform specific tasks.
   - It is a fundamental skill that enables us to solve problems, automate tasks, and develop software applications.
   - Programming requires logical thinking, attention to detail, and the ability to break down complex problems into manageable steps.

### 1.2: Overview of C programming language
   - C is a powerful and widely used programming language that has been around for several decades.
   - Developed by Dennis Ritchie in the early 1970s, C is known for its efficiency, flexibility, and close-to-hardware capabilities.
   - C has influenced many modern programming languages and is used in various domains, including operating systems, embedded systems, and game development.

### 1.3: Setting up the development environment
   - Before we start writing code in C, we need to set up our development environment.
   - First, we need to choose a C compiler, such as GCC or Clang, based on the operating system you are using.
   - Next, we will install the compiler and the necessary tools required for C programming.
   - Finally, we will configure our development environment, either by setting up an Integrated Development Environment (IDE) or using a simple text editor.

### 1.4: Writing and running a basic C program
   - In C, programs are composed of functions. The main function serves as the entry point of our program.
   - We start by writing a simple "Hello, World!" program to understand the basic structure of a C program.
   - We will write the code, including comments to provide explanations (comments begin with '//' or '/*'), and save it with the `.c` extension.
   - Once the program is written, we will compile it using the chosen C compiler and execute it to see the output.
   ```
   #include <stdio.h> //this line includes the standard input/output library; contains the 'printf' function

   int main() //starting point of program execution
   {
       printf("\n Hello, World!"); //syntax for 'printf' function
       return 0;
   }
   ```

### 1.5: Variables and data types
   - In programming, variables are used to store and manipulate data. They have a specific type that determines the kind of data they can hold.
   - C provides various data types, such as integers, floating-point numbers, characters, and more.
   - We declare variables by specifying their type and give them meaningful names.
   - Variables can be initialized with an initial value and assigned new values during the program's execution.
   - We can assign new values to variables using the assignment operator (`=`).
   ```
   int age; // Declaration of an integer variable named 'age'
   float temperature = 98.6; // Declaration and initialization of a floating-point variable named 'temperature'
   char grade = 'A'; // Declaration and initialization of a character variable named 'grade'
   ```

### 1.6: Input and output operations
   - Input and output operations allow us to interact with the user and display information on the console.
   - In C, we use the standard input/output library, `stdio.h`, which provides functions like `printf` and `scanf`.
   - The `printf` function is used to display output to the console, while `scanf` is used to read input from the user.

#### Working of the 'printf' function
The `printf` function takes a formatted string as an argument and displays the formatted output on the console. Let's see an example:
   ```
   int age = 20;
   printf("I am %d years old.\n", age);
   ```
In the above example, `%d` is a format specifier for integers. It is replaced by the value of the variable `age` when displayed.

#### Working of the 'scanf' function
The `scanf` function allows us to read input from the user and store it in variables. Let's look at an example:
   ```
   int number;
   printf("Enter a number: ");
   scanf("%d", &number);
   printf("The number you entered is: %d\n", number);
   ```
In the above example, `%d` is the format specifier for integers. The `&` sumbol before `number` in the `scanf` function is used to obtain the memory address of the variable.

### 1.7: Arithmetic and assignment operators
   - Arithmetic operators are used to perform mathematical operations in C, such as addition, subtraction, multiplication, and division.
   - The assignment operator (`=`) is used to assign values to variables.
   - C also provides compound assignment operators (`+=`, `-=`, `*=`, `/=`) to perform an operation and assign the result to the same variable.
   ```
   int x = 5, y = 3;
   int sum = x + y;
   int difference = x - y;
   int product = x * y;
   int quotient = x / y;
   int remainder = x % y;

   x += 2;  // Equivalent to x = x + 2
   y -= 1;  // Equivalent to y = y - 1
   ```
In the above example, we perform addition, subtraction, multiplication, division, and modulo operations. We also demonstrate the use of compound assignment operators to modify the values of variables.

### 1.8: Control flow: if-else statements and loops
   - Control flow statements allow us to control the execution flow of a program based on certain conditions.
   - The if-else statement is used to execute a block of code if a condition is true and a different block if it is false.
   - Loops enable repetitive execution of a block of code based on a given condition. C provides three types of loops: the while loop, do-while loop, and for loop.
   ```
   int num = 10;

   if (num > 0)
   {
       printf("The number is positive.\n");
   }
   else if (num < 0)
        {
             printf("The number is negative. \n");
        }
        else
        {
             printf("The number is zero. \n");
        }

   int i = 1;
   while (i <= 5)
   {
       printf("%d ", i);
       i++;
   }
   printf("\n");
   ```
In the above example, we use an if-else statement to check if a number is positive, negative, or zero. We also demonstrate a while loop to print numbers from 1 to 5.

A do-while loop is similar to a while loop but with one key difference. In a do-while loop, the loop body is executed at least once before checking the loop condition. Here's an example:

```
#include <stdio.h>

int main()
{
    int num = 1;

    do
    {
        printf("%d\n", num);
        num++;
    }
    while (num <= 5);

    return 0;
}
```

In this program, the loop body will execute at least once because the condition is checked after the first iteration. It will continue to execute as long as the condition `num <= 5` is true. Inside the loop, we print the value of `num` and increment it by 1 using the `num++` statement.

The output of this program will be the numbers 1 to 5, inclusive.

The for loop is a compact and versatile loop structure that combines initialization, condition, and iteration in a single line. Here's an example:

```
#include <stdio.h>

int main()
{
   for (int i = 1; i <= 5; i++)
   {
      printf("%d\n", i);
   }

   return 0;
}
```

In this program, the `for` loop consists of three parts:

1. Initialization: `int i = 1` initializes a loop control variable `i` to the starting value of 1.

2. Condition: `i <= 5` specifies the condition that must be true for the loop to continue executing.

3. Iteration: `i++` increments the value of `i` by 1 after each iteration.

The loop will continue executing as long as the condition `i <= 5` is true. Inside the loop, we print the value of `i`. The output will be the numbers 1 to 5, inclusive.

The for loop provides a compact and organized way to control the flow of your program when you know the number of iterations in advance. It is commonly used when iterating over arrays, performing calculations, or repeating a block of code a fixed number of times.

