# Operators

Operators in programming languages perform the arithmetic and logic operations just as in maths.

This project gives you practice with using these operators.

## Step 1

Inside the `main()` method are some declarations of integers.

```java
//Declare the variable for the integers
int int1 = 7;
int int2 = 10;
int int3 = 21;
int int4 = 53;
```
There is also a declaration for the result.

```java
int result = -1;
```
It is conventional to intialise variables that will be used to store results of calculations as `-1`, then if it is not changed it is easier to notice.

The code then gives an example of the use of the main operators and prints out the result:

```java
//addition +
result = int1 + int2;
//output result variable
System.out.println(result);

result = int1 + int2 + int3 + int4;
System.out.println(result);
```
This is follwed by subtraction `-`, multiplication `*`, division `/` and remainder `%` (known as "mod").

### Task

- read through the code up to line `34` and make sure you understand how it works
- do the calculations ypurself so you can check the results from the code
- run the code and see if the results for Step 1 are as you expected

## Step 2

Look at the following examples showing different uses of operators.

```java
//the operators can be used in any combination
result = int1 + int2 - int3;
System.out.println(result);

//you can output a calculation directly
System.out.println(int1 * int2 - int4 + int3);

//you need to remember the precedence of the operators 
//why is this different from the above?
System.out.println(int4 + int3 - int1 * int2);
```

### Task

- read through the code from line `38` to `47` and make sure you understand how it works
- you need to remember the precedence of the operators which is the same as in maths
- do the calculations yourself so you can check the results from the code
- run the code and see if the results for Step 2 are as you expected
- change the values of the variables at the top and see how that changes things

## Step 3

The next section of code shows how you declare a constant in Java. Unlike a variable, the value of a constant cannot be changed elsewhere in the code.

```java
//declaring a constant using the "final" keyword
final double pi = 3.142;
```

### Your challenge

- drawing on the example code above, use the constant `pi` to calculate the circumference of a circle of radius `int1` and output the result

Remember the formula?

circumference = 2 π r

- similarly calculate and output the area of a circle of radius `int2`

area = π r<sup>2</sup>

There are 2 ways of squaring numbers in Java (or any power for that matter) - `r*r` and using the power function (Java does not have a primitive power operator).

### Extension

- after you have done it the first way and then see if you can look up on the internet what the power function is in Java and how to use it and do it that way.
