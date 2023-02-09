# Pseudocode

## Learning Goals

- Explain what pseudocode is.
- Discuss how helpful pseudocode can be.

## What is Pseudocode?

**Pseudocode** is fake code. This is code that we can write in plain text and
will not be executed by the compiler or interpreter. It is a way for programmers
to jot their thoughts down on how they think they may write a sequence of
statements without having to worry about syntax or formatting. Pseudocode is
especially helpful when we get more into advanced programming concepts, like
data structures and algorithms.

## How to Write Pseudocode

Let's say we want to write a program to determine if a number is even or odd.
But what if we don't know where or how to start? Well the best way to do that is
to take out a text editor and write down a goal and a sequence of tasks.

```text
The goal we know is that the program will determine if an integer value is
even or odd.

if the integer is divisible by 2
    print "This number is even!"
else (this means the integer is not divisible by 2)
    print "This number is odd!"       
```

The above is considered pseudocode. It is written in plain text that can be
easily interpreted into code:

```java

Scanner scanner = new Scanner(System.in);

int number = scanner.nextInt();

if (number % 2 == 0) {
    System.out.println("This number is even!");
} else {
    System.out.println("This number is odd!");
}
```

When writing pseudocode, we should consider some of these "Dos and Don'ts".

- Dos:
  - Keep it simple and concise.
  - Remember, pseudocode is for us to clearly understand what it is we want
    to code. So we should be able to grasp the logic easily.
  - Indent and use white space.
    - Even though it might not be real code, it will help us gather our thoughts
      easier when it is time for us to implement it from pseudocode to Java.
  - Use control structures if possible.
    - If we can use keywords like `if` and `else` when writing pseudocode, it
      will help us when it is time to convert it to actual Java code.
- Don'ts:
  - Try not to be too general.
    - While pseudocode is more for us as programmers, it won't help if we
      generalize the pseudocode too much. We want to have a good idea of the
      steps and statements we may want to execute and write.
  - Don't write it too programmatic.
    - Pseudocode should be easily understood by anyone, even if they do not
      know how to code. Anyone should be able to read the pseudocode and
      understand what it may be doing.

As we learn more about the control flow of a program, keep pseudocode in mind as
it can be a helpful to gather our thoughts on how to write a program or what a
program might be doing.
