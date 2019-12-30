# Language parser

> Created as a Coursework for Formal Languages course at the University of Warwick

## Example of language
-   Simple functional language
-   Can do addition and multiplication
-   Can create functions
-   Has a main function

See the example in `input.txt`

## How to use
Create the java parser files using the `javacc` command.

```bash
javacc Grammar.jj
```

This should create a number of java files. Compile them all with:

```bash
javac *.java
```

You can then use the created Grammar command to parse and execute the file.

```bash
java Grammar < input.txt > output.txt 2> err.txt
```
