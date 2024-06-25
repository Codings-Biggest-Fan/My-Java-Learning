# My Java Learning
## Basic Syntax
- At The end of each line add a **; (Like In Java Script)**
- Pay attention to Upper an lowercase, it matters
- Never forget these Starter Lines

```
public class Main {
    public static void main(String[] args) {
    }
}
```
if you dont add these your code wont work
## Printing Text to the Console

If you want to print text in the same line use:
```java
System.out.print("Text");
System.out.print("Another line of Text");
```
The output would look like this:
```
TextAnotherLine of Text
```

If you want to print text in different lines then use:
```java
System.out.println("Text");
System.out.println("Another line of Text");
```
The output would look like this:
```
Text
AnotherLine of Text
```
Another way to do this is to add \n into your string like `"Hello\n"`

An Shortcut to type `System.out.println();` in InteliJ is to type `sout` then press tab

If you Want to add a tab use \t `"\t hello"`

And if you want to add double quotations surround your code with \s like this `"\"Hello\""`,same with backslashes `"\\hello\\"`
This is because \s are escape characters since quotations and backslashes have another purpose you need to escape it of course youmcan escape other characters also
## Comments
For a sinle line comment just do `//comment`

For multiline comments:
```
/*
 *Comment
 *Can
 *Go
 *Here
 */
```
## Variables
First of all an variable is a storage for a value which you can use over and over in your code 

For example lets say you are making a timed game and you want to show the time and use it to stop the game so you need to use it two times so you would use a variabe it makes your life much easier
The types of Variables:
There are many types bet here are the main ones you need to remember:
1. Boolean: true or false ex.`true`
2. Int: Integers from  -2 bil to 2 bil ex. `8652345`
3. Double: Fractions to 15 digits ex. `9.232323456767895`
4. Char: a letter in a string ex. `"a"`
5. String: A sequence of characters in a Quote ex.`"hello"`

These are some infrequently used types

1. Byte:-128 to 127 ex. `-128`
2. Short:-32728 to 32767 ex. `32500`
3. Long: Integers fo -9 quintillion to 9 quintillion ex. `9000000000`
4. Float: Fractions from 6-7 digits ex. `2.134587`
