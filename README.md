# Java-Day-04-Arithmetic-Operators
# Java Day 4 - Arithmetic Operators

This program takes two numbers from the user and performs basic arithmetic operations.

## Operations Used

* Addition `+`
* Subtraction `-`
* Multiplication `*`
* Division `/`
* Remainder `%`

## Example Input

```text
Enter first number: 20
Enter second number: 6
```

## Output

```text
Addition = 26
Subtraction = 14
Multiplication = 120
Division = 3
Remainder = 2
```

## Concepts Used

* Scanner
* User input
* Integer variables
* Arithmetic operators
* `System.out.println()`

## How It Works

1. The program creates a `Scanner` object.
2. It takes two numbers from the user.
3. Arithmetic operators are used to perform calculations.
4. The results are displayed on the screen.
5. The Scanner is closed at the end.

## Java Code

```java
import java.util.Scanner;

public class Main
{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter first number: ");
        int num1 = sc.nextInt();

        System.out.print("Enter second number: ");
        int num2 = sc.nextInt();

        System.out.println("Addition = " + (num1 + num2));
        System.out.println("Subtraction = " + (num1 - num2));
        System.out.println("Multiplication = " + (num1 * num2));
        System.out.println("Division = " + (num1 / num2));
        System.out.println("Remainder = " + (num1 % num2));

        sc.close();
    }
}
```

## Goal

The goal of this project is to understand basic arithmetic operators and practice taking numeric input in Java.
