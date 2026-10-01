# Hello World!

Writing your first program in Java.

---

## Java Mechanics

Java code is written in a `.java` text file. This code is then compiled into binary code which is interpreted by the computer when it is run.
The file containing a Java class must be called by the name of the class and have a `.java` file ending. In this case your code file is called `Main.java` making the name of the class `Main`. The name of the class must match the name of the .java file.

Note the following:

- a Java class must be declared with the keyword `public`
- all code must be inside the curly brackets `{ }`
- comments have `//` in front of them

## Your Task

Write the following code in the Main.java file:
```java
public class Main{
  //the code for the main method goes here

}//end of Main class
```

Now you need to add the code for the `main()` method of your programme inside the curly brackets to enable the class to run.

```java
class Main {
  //the code for the main method goes here
  public static void main(String[] args) {
    
    //write your code here
    
  }//end of main method
}//end of Main class
```
Any code inside the curly brackets of the `main()` method will be run when the program starts.

When coding "print" refers to displaying the output in the console - "printing to screen". In Java the syntax is `System.out.print()` or `System.out.println()` to print to a new line in the console.

In the `main()` class, write the code to display the text ***Hello World!*** in the console using:

```java
System.out.println("Hello World!");
```

Note:
- the text you want to output to the console must be in the `()` and as it is a `String` it must be in " "
- you need a semi-colon `;` at the end of every line of code in Java

Hit **Run** when you are ready to compile and run the code.

Now:
- add another line to your code that uses the `System.out.println()` statement to output "It's me!"
- you will note that your output has to match **exactly** to pass the tests

Next:
- try changing the messages you are printing to the console and **Run** again after each change
- are the outputs as you expected?
