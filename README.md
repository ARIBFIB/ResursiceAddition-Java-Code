# RecursiceAddition-Java-Code

Youtube Link: https://youtu.be/DgDKvcYSfPQ
Also Watch Resurssion Fucntion YT Link: https://youtu.be/s3zu68-ANLs
![image](https://github.com/ARIBFIB/ResursiceAddition-Java-Code/assets/125716994/e42aa328-07ab-4672-a5c1-334eb8755f21)



# Output
![image](https://github.com/ARIBFIB/ResursiceAddition-Java-Code/assets/125716994/3e61a9e7-f0a9-4a79-a650-c403e1b1c7a4)

Okay, let's address this query in the context of the provided YouTube video content.

```java
public class RecursiveAddition {
    public static int add(int n) {
        if (n == 0) {
            return 0;
        } else {
            return n + add(n - 1);
        }
    }

    public static void main(String[] args) {
        int result = add(10);
        System.out.println("The sum of numbers from 0 to 10 is: " + result);
    }
}
```

This Java code defines a recursive function `add()` that calculates the sum of all numbers from 0 up to the given input `n`. The function works as follows:

1. If `n` is 0, the function returns 0 (the base case).
2. Otherwise, the function returns the sum of `n` and the result of calling `add(n-1)` (the recursive case).

The `main()` function calls the `add()` function with `n = 10` and prints the result, which is the sum of all numbers from 0 to 10, which is 55.

The provided YouTube video demonstrates this recursive function and its execution flow using a call stack diagram, which is shown in the image below.

![Recursive Addition Call Stack][]

The call stack starts with `add(10)` and grows as the function calls itself recursively, until it reaches the base case of `add(0)`. Then, the call stack unwinds, with each function call returning its result to the previous call, until the final result is returned to the `main()` function.

The output of the program is:```
The sum of numbers from 0 to 10 is: 55```

This matches the expected result of the recursive addition of all numbers from 0 to 10.

Readme File Description:

Here's a suggested README.md file with a beautiful layout, icons, and bullet points:

# Recursive Addition in Java![Java][]

This is a Java program that demonstrates a recursive function to calculate the sum of all numbers from 0 up to a given input.

## Table of Contents

- [Description](#description)
- [Usage](#usage)
- [Call Stack Diagram](#call-stack-diagram)
- [Output](#output)
- [Contributing](#contributing)
- [License](#license)

## Description

The program defines a `RecursiveAddition` class with two methods:

- `add(int n)`: A recursive function that calculates the sum of all numbers from 0 up to `n`.
- `main(String[] args)`: The entry point of the program, which calls the `add()` function with `n = 10` and prints the result.

## Usage

To run the program, you can copy the following code and save it in a file named `RecursiveAddition.java`:```java
public class RecursiveAddition {
    public static int add(int n) {
        if (n == 0) {
            return 0;
        } else {
            return n + add(n - 1);
        }
    }

    public static void main(String[] args) {
        int result = add(10);
        System.out.println("The sum of numbers from 0 to 10 is: " + result);
    }
}```

Then, compile and run the program using the following commands:```
javac RecursiveAddition.java
java RecursiveAddition```

## Call Stack Diagram

The following diagram shows the call stack as the `add()` function calls itself recursively:![Recursive Addition Call Stack][]

## Output```
The sum of numbers from 0 to 10 is: 55```

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
