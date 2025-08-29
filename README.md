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




