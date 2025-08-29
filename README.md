# Lab-Classes Project
Vanier - Programming 1 - Lab 1 - Part 5
## Answers:

**What happens when *getName()* is called on an object from the class *Student*?**  
When *getName()* is called, several thing happen.  
When the student was first created,  a string was given, its value was stored in *fullName*
``` java
public Student(String fullName, String studentID)
```
Then, the value of *fullName* was moved to *name*.
``` java
name = fullName;
```
When *getName();* is called, the value of *name* is returned.
``` java
return name;
```