Null Pointer Exception Demo
This project demonstrates how to intentionally generate and handle a NullPointerException in Java. It includes two classes: Main and NullPointerDemo.

Project Structure
NullPointerDemo: Contains a method that deliberately generates a NullPointerException by attempting to access the length of a null string.
Main: Calls the generateNullPointerException method and handles the exception using a try-catch block.
How It Works
The NullPointerDemo class includes a method generateNullPointerException() which creates a null string and attempts to call the length() method on it, causing a NullPointerException.
The Main class invokes this method and catches the exception.
The caught exception is handled as follows:
A custom error message is printed.
The exception's stack trace is displayed.
The exception's toString() method is called to print a brief description of the exception.
Prerequisites
Java Development Kit (JDK) 8 or higher.
How to Run
Compile the program: javac Main.java NullPointerDemo.java
Run the program: java Main
Example Output
When the program is executed, the following output will appear:

Occurred exception NullPointerException: java.lang.NullPointerException
java.lang.NullPointerException
    at NullPointerDemo.generateNullPointerException(NullPointerDemo.java:5)
    at Main.main(Main.java:5)
Notes
This example is designed for educational purposes to demonstrate exception handling in Java.
Avoid generating NullPointerException in real-world applications without proper handling mechanisms.
