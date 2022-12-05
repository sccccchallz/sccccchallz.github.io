# Introduction
This is a note for AP Computer Science A. Although there is a major part of this will be shown on the reference during the AP test; however, it is still important to know how to use them and know and understand how to use additional vital ones for this test. This note is done after finishing the AP test. It is suggested to type one by yourself 

# What should you know for the APCS
## CONTENT
- [[#Basic]]
	1. [[#Style]]
	2. [[#Structure]]
	3. [[#Use of Other Classes]]
1. [[#Common Classes]]
	1. [[#Math Class]]
	    1. [[#Math Class Methods]]
2. [[#Data Types]]
	1. [[#Primitive Types]]
	2. [[#Non-Primitive Types]]
3. [[#Conditional Statements]]


## Basic
### Style
1. **Naming Style**
	When we are going to name the method, variable, anything in Java, it is recommended to use this `wordWord` style (only use a `word` for most of the variable name). For example, when we are trying to name a method for calculating the length of a String, we can use `stringLength`
1. Bracket Style
	- In AP course, `{` is used in the next line:
	   ```java For example
	   public int methodName(String a)
	   {
	   }
	   ```
	- in google style, `{` is used right after the word of the line:
	   ```java 
	   public int methodName(String a){
	   }
```
	- some other style, `{` is used after the word of the line with a space:
	```java
       public int methodName(String a) {
	   }
```
	- All the styles use the `()` after the word ***without*** space, except condition statements
	   ```java
	   methodName(String a);
	   
	   but:
	   if (x = a) {
	   }
```
	- The ***Ending*** bracket `}` should be listed like this:
	   ```java
    code block
			}
	    }
	}
	   
```
3. Sign Style
It is recommended to put the signs like `+, -, *, /, =` in between two spaces; like how I did in the if statement above.

### Structure
The basic structure of a java program should look like this:
```java
/**
*
*@author Some Body
*@version modified date of this version of the program
*
*Purpose of this program
*/
public class Class {
	public static void main(String[] args) {
		//code to operate
	}
	/**
	*Purpose of this method
	*
	*@param parameter   What is the type and purpose of this parameter
	*
	*@see method result What are you expected to see when you use this method in main
	*/
	public void methodYouNeed(int parameter) {
	}
}
```
The method other than main is not necessary to write a basic program, but it is need when you write this program in **Object-Oriented Program(OOP)** style.

***It is extremely important to write a comment for your program and every single method that is not clear to see the function(for instance, you don't need to write a comment for getter and accessor method. it is just going to waste your space)***

### Use of Other Classes
It is common to use classes that is not written in this class, such as `Math or Scanner` class. To use them, we need to import them first. (Here we are only discussing the use of class that is in the Java package. )
1. Import
	We need to add a line `import java.util.*` to import them all; change to `java.util.Scanner` if you only want to use `Scanner` class; this apply to other class.  
2. Use class method
	Usually, we import these method to use their method, for example we want to get a random number. 
	`double randomNum = Math.random();`


## Common Classes
for how to use these class, see [[#Use of Other Classes]]
### Math Class
This class have a lot of the math references that is static. 
#### Math Class Methods
1. **Math.random()**
    - random() class is to generator a random number in the program; however, it is ***not a true random*** number like many programming languages. 
    - The range of the method is 0 <= x < 1
    - Common usage is: `int random = (int)Math.random()*`
     


## Data Types
*Data types have the difference of primitive and non primitive which basically can be recognized by the way the wrote*

###### Primitive Types
This type are usually in all lower case, in the APCS-A course, people usually have these following types:
	- int 
	- double
	- boolean

###### Non-Primitive Types
This type usually in the style that STARTS there name with a capitalized letter, which means that they are actually a class that Java have. It means that when using the non-primitive data type, the style of creating new instance of the class could be applied, at the same time, these types can call some methods.

Here are some common ones in the Java language:
	- String
	- Integer
	- Boolean
	- Array

### Declaration, Initialization and Assignment
Declaration

## Conditional Statements
