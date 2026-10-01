# Conditionals

## Combining Conditionals

There are often circumstances where you need to test for more than one condition to achieve the result you want.

You can combine as many conditions in the `()` as you wish as long as they are Separated by the boolean operators `AND` or `OR`. 

In Java `AND` is `&&` and `OR` is `||`.

So if the government decided shoe size was a requirement along with age for school - the code could look like this:

```java
int age = UserInput.getInteger("Please enter your age");
int size = UserInput.getInteger("Please enter your shoe size");

//conditional using OR
if(age < 5 || size < 4){
  System.out.println("You are too young or your feet are too small for school");
}
//conditional using AND
else if(age <=18 && size < 12){
  System.out.println("You should be in school");
}
//catch the rest with a default else
else{
  System.out.println("You have finished school or your feet are too big for school");
}
```

### Task

- read the code and make sure you understand how it works
- try out some combinations and see if your prediction is correct
- run the code and make sure your predictions are correct

Just be warned that when you do this you really have to make sure that the logic you are trying to achieve is carried out by the code - it can get quite tricky! So test, test, test.

## Nested conditionals

You can also have conditionals inside conditionals, so the same approach - with a bit more finesse - could be achieved with:

```java
System.out.println("More finessed version:");

//conditional using nested
if(age < 5){
  System.out.println("You are too young for school");
  if(size < 4){
    System.out.println("And your feet are too small for school");
  }
  else{
    System.out.println("But your feet are large enough for school");
  }
}
//conditional using AND
else if(age <=18 && size < 12){
  System.out.println("You should be in school");
}
//catch the rest with a default else
else{
   System.out.println("You have finished school or your feet are too big for school");
}
```

### Challenge

- copy and paste this code into your
- look at the logic above - there is a combination of conditions that is not dealt with
- can you work out which it is? You can try testing verious combinations inside and outside the ranges to work it out
- can you work out a way of dealing with the missing coverage?

We will look at this in more detail further down the line.