# Lab-Classes Project
Vanier - Programming 1 - Lab 1 - Part 5
## Answers:

**What happens when *getName()* is called on an object from the class *Student*?**  

When *getName()* is called, several thing happen.  
When the student was first created,  a string was given, its value was stored in *fullName*
``` java
public Student(String fullName, String studentID)
```
Then, the value of *fullName* was assigned to *name*.
``` java
name = fullName;
```
When *getName();* is called, the value of *name* is returned.
``` java
return name;
```

**Call *numberOfStudents()* for the LabClass object. What does it do?**  

It returns 0.

## Data Types
0 :int  OR byte, short, long
"hello" : String
101 : int OR byte, short, long
-1 : int OR byte, short, long
true : Boolean
"33" : String
3.1415 : float OR double

**What would you have to do to add a new field, for example one called name, to a circle object?**  
``` java
private String name;
```
**Write the header for a method named send that has one parameter of type String, and does not
return a value.**  
``` java
public send(String)
```
**Write the header for a method named average that has two parameters, both of type int, and
returns an int value.**  
``` java
public average(int value1, int value2)
```
**. Look at the book you are reading now. Is it an object or a class? If it is a class, name some objects.
If it is an object, name its class.**  

**My** book is an object. Its class is the idea of a book.  
  
**Can an object have several classes?**  
Yes. A class defines an objects properties, some properties are shared. For example, a square could also be a rectangle, and a sphere and ellipse.


