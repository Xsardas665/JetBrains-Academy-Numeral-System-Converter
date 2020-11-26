# Numeral System Converter from JetBrains Academy
### Stage 1/6:
#### Description
In this project, you will be creating your own numeral system converter. If you don't know what a numeral system is, or simply need to brush up on the topic, browse through the relevant Wikipedia page. Also, there is a great Youtube video that explains various numeral systems and the relationship between them.

Implement a program that outputs a number in two systems: the first is decimal, and the second one is binary. This must be the same number represented in different systems; feel free to choose any number you like.

This stage is auto-graded. The grader will check that:

- you output a single line;
- there are two numbers;
- the first number is decimal;
- the second number is binary (it starts with 0b and contains only 0 and 1);
- the first number is equal to the second one.

Note that you do not need to enter anything into the program, you should print a line prepared in advance. A single String is expected to be printed.
### Stage 2/6:
#### Description 
Implement a program that calculates the last digit of the given number converted to base 8.

This stage is auto-graded. The grader will input a number in base 10, and then check that your program output matches the correct answer.

### Stage 3/6:
#### Description
Now let's implement a simple converter. It will convert the given decimal number to the given radix. You should support three radices with prefixes:

- binary (0b);
- octal (0);
- hexadecimal (0x).

To get a string with the answer, use the Long.toString(sourceNumber, destinationRadix) expression. Note that the expected output is a String, because Java implicitly converts 0/0b/0x concatenated numbers to their decimal representation.

This stage is auto-graded. The grader will input two lines (a number and a radix) and check that your output is the correct number representation in the given radix. Don't forget about the prefix!

