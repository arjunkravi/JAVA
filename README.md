# JAVA Programming & Environment setup
This will guide you to setup and compile a java program

### 1. Download java JDK
From the following [link](http://www.oracle.com/technetwork/java/javase/downloads/jdk10-downloads-4416644.html) download the jdk and proceed the installation for JRE and JDK installations .

### 2. Setup the Path
* In the start menu , search for **_edit the environment variables_**
* Select the **_Environment Variables.._** button
* Under the `System Variables` , click the **_New_** button .
* You will be provided with two text box , fill them respective like mentioned below :
```
variable name : JAVA_HOME
Variable value : Directory to which the java JDK is installed not to bin of that DIR
```
* In the list of System variables , find **_Path_** variable . We will need to edit it .
* Click the **_Edit_** button .
* Now you will be provided with a new window . Click on **_New_** button and type the following `%JAVA_HOME%\bin`
* Click **_OK_** for all the windows .

### 3. Run the command 

`javac` which will provide you with additional tags which can be used with javac command .

### 4. Save a *.java file and Run the *.class 
* Save a java program
```
//myfile.java
class myfile
{
 public void static main (String args[])
 {
  System.out.println("Hello World");
 }
}
```

* compile the script

**>java myfile.java**

* then a .class file will be generated in the directory . Run the script by running the command :

**>javac myfile**

### 5. You can begin the java scripting now .. 

### Happy coding :heart:
