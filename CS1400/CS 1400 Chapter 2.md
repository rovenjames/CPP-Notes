# Java Fundementals
## Parts of a Java Program
### <u>Class</u>
- A Java source code file contains one or more Java classes
- If more than one class is in a source code file, only one of them may be public
- The public class and the filename of the source code file must match.
  - ex: A class named **Simple** must be in a file named **Simple.java**
- Each Java class can be separated into parts
- 
 <u>"Simple" Example</u>

 ```java
 {
    // A simple Java program.

    public class Simple
    {
        // This area is the body of the class "Simple."
        // All of the data and methods for this class 
        // will be between these curly braces

        public static void main (String[] args)
        // This is the method header for the main method. 
        // The main method is where a Java application begins.
        {
            // This area is the body of the main method
            // All of the actions to be completed during
            // the main method will be between these curly braces
        }
    }
 }
 ```

 ## Class Example: MakeChange.java
 ```java
 {
    // This program will make change with coins

    public class MakeChange
    {
        public static void main(String[] args)
        {
            
        }
    }
 }