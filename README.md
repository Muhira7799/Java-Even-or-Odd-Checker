# Java Even or Odd Checker

A small Java console program that reads an integer and tells whether it is even or odd.

## What It Demonstrates

```java
if (number % 2 == 0) {
    System.out.println(number + " is an even number");
} else {
    System.out.println(number + " is an odd number");
}
```

The remainder operator `%` gives what is left after division. An even number leaves a remainder of `0` when divided by 2.

## Sample Runs

```
Enter a number: 8
8 is an even number
```

```
Enter a number: 7
7 is an odd number
```

| Input | Result |
|-------|--------|
| 8 | even |
| 7 | odd |
| 0 | even |
| -3 | odd |

## Requirements

- Java Development Kit (JDK) 8 or higher

## Getting Started

```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
javac EvenOdd.java
java EvenOdd
```

## Notes

- Entering something that is not a whole number, such as `2.5` or `abc`, throws an `InputMismatchException`.

## Project Structure

```
.
├── EvenOdd.java
└── README.md
```

## Possible Improvements

- Handle invalid input with `hasNextInt()` or `try-catch`
- Keep asking for numbers until the user quits
- Count how many even and odd numbers were entered
