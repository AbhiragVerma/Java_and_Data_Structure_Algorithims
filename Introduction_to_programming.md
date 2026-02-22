# Types of Languages 

## Procedural Languages -> 
- Specifies a series of well-structured steps and procedures to cpose a program.
- contains a systematic order of statements, functions and commands to complete a task.

## Fuctional Languages ->
- Wrtiting a program only in pure functions i.e. never modifiy variables, but onlhy create new ones as an output.
- Used in situations where we have to perform lots of defferent operations on the same set of data, like ML.
- First class Functions?

## Object Oriented ->
- Revolves around objects.
- Code + Data = objects
- Developed to make it easier to develop, debug, reuse, and maintain software.

## 

-> Collection of all this is known as Classes. And the instance from this is would be the object.

## 

# Static v/s Dynamic Languages

## Static 
- Perform type checking at comile time.
- Errors will show at compile time.
- Declare datatype before you use it.
- More control.

## Dynamic Languages
- Perform type chicking at runtime.
- Error might not show till program is run. 
- No need to declare datatype of varaiable.
- Saves time in writing code but might give error at runtime.

## 

->  there is like... ki matlab jaha jo yeh hai a = 10, toh yaha 10 jo hai object hota hai or yeh "a" refrernece hota hai or yeh 10 jo hai heap memory mei store hota hai, or yeh "a" stack memory mei hota hai.

# Java 

- the .java file (which is the human readable format).
- it goes to the compiler and created to the .class file(byte code). it compiles entire file.
- then interpter (line by line) Machine Code (0 and 1).
- this code will not directly run on a system.
- we need JVM to run this.
- Reason why Java is platform independent.

# Java Development Kit

- provides environment to develop and run the java program.
- It is  a package that includes;
    - development tools - to provide an environment to develop your program.
    - JRE - to execute your program.
    - a compiler - javac
    - archiver - jar.
    - docs generator - javadoc
    - interpreter/ loader.

# Java Runtime Envirnonment

- It is installation package that provides environment to only run the program
- it consists of;
    - Deployment technologies.
    - User interface toolkits.
    - Integration Libraries.
    - Base libraries.
    - JVM
- After we get the .class file, the next things happen at runtime;
    - class loader loads all classes needed to execute the program.
    - JVM sends code to byte code verifier to check the format of code.

# Java Source Code --> JDK --> ByteCode --> JVM --> JRE 

