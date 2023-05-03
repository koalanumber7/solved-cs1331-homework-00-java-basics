Download Link: https://assignmentchef.com/product/solved-cs1331-homework-00-java-basics
<br>






Hello, and welcome to your first homework assignment! This assignment just serves to make sure you have installed Java properly on your machine and that you know how to run a Java program.

<h1>Part 1: Installing Java</h1>

In this class, we will be using Java 11 (openjdk). Make sure you have this version installed, even if you already have a previous version of Java. We have detailed instructions for this on the course website, see below:

Install guide

Check to see which version of Java you have installed by running javac -version and java -version.

After running javac -version, you should see this output:

After running java -version, you should see this output:

<h1>Part 2: Writing and Compiling a Java Class</h1>

In order to create a Java class, you must first create a file with the .java extension. In our example here, we will use Test.java. Within the class, you will need to write a class header. For now, just memorize that you need to write public class before your class name. We will go more in depth about what exactly this means later. As for the class name, it must exactly match the name of the file.

Thus, our example should look like this:

Now that you have written a Java class, you should be able to compile your code! Navigate to the directory where you have saved this file in the command line.

After navigating to the proper directory, you will be able to compile the Java class you’ve just created! You do this by using the command javac FileName.java. Since we named our Java example file Test.java, we compile it using javac Test.java.

This should create a new file in your directory called Test.class! Created by the Java compiler, this file will contain Java bytecode, and it will not make much sense to you if you open it up. However, it makes a lot of sense to the Java Virtual Machine, or the JVM (a computing machine that allows our program to run).

If a new file was not created, your program did not compile. Read the compilation error produced in your command prompt, and fix it before proceeding!

<h1>Part 3: The main Method</h1>

Remember, the method signature should look like this:

This method is critical for a Java class to be “runnable.”

Write a main method for your Test class. All of the rest of the code will be written inside of your main method!

Now, you can write the contents of your first Java program! Simply, try these steps:

<ol>

 <li>Print out “Hello, world!”</li>

 <li>Declare three variables</li>

</ol>

An integer x

An integer y

An integer k

<ol start="3">

 <li>Assign a value of 8 to the variable x</li>

 <li>Assign a value of 5 to the variable y</li>

 <li>Assign x * y + 2 to the variable k</li>

 <li>Print out the value of the variable k</li>

</ol>

Try to compile as you make changes. This will help you correct any errors you may make as you go instead of dealing with them all at the end.

To run your program, use the command java FileName. Since we named our file Test.java, we will use the command java Test. Note that we <strong>didn’t</strong> include the .class extension after Test; it won’t run if you do java Test.class. If you ever want to run a new version of your program after making alterations, know that you must recompile before doing so.





