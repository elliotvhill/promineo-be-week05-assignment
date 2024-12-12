# Week 5 Assignment: Object Oriented Programming

Repository for submission for week 5 coding assignment.

## Instruction

Follow the **Exercises** below to complete this assignment.

- In Eclipse, or an IDE of your choice, write the code that accomplishes the objectives listed below. Ensure that the code compiles and runs as directed.
- Create a new repository on GitHub for this week's assignment and push your completed code to this dedicated repo.
- Create a video showcasing your work:
    - In this video: record and present your project verbally while showing the results of the working project.   


**_Easy way to Create a video:_**  Start a meeting in Zoom, share your screen, open Eclipse with the code and your Console window, start recording & record yourself describing and running the program showing the results. When you click "End Meeting" it will save the video on your computer.

- Create a video, up to five minutes max, showing and explaining how your project works with an emphasis on the portions you contributed.

- This video should be done using screen share and voice over.  

- This should then be uploaded to a publicly accessible site, such as YouTube. Ensure the link you share is PUBLIC or UNLISTED!


## Coding Steps

### 1. Create an **interface** named `Logger`.


### 2. **Add two void methods to the `Logger` interface**; each should take a `String` as an argument.

&emsp;a. `log`  
&emsp;b. `error`  


### 3. Create **two classes** that implement the `Logger` interface

&emsp;a. `AsteriskLogger`  
&emsp;b. `SpacedLogger`  


### 4. Implement the **AsteriskLogger** methods:  

&emsp;_**Note:** The `AsteriskLogger` will use the asterisk or `*`._

&emsp;a. The `log` method on the `AsteriskLogger` should print out the String it receives between 3 asterisks on either side of the String (e.g. if the String passed in is `Hello`, then it should print `***Hello***` to the console).

&emsp;b. The error method on the AsteriskLogger should print the String it receives inside a box of asterisks, with the String preceded by the word “ERROR:”. For example, if “Hello” is the argument, the following should be printed:

```java
    ****************

    ***Error: Hello***

    ****************
```

### 5. Implement the SpacedLogger methods:

&emsp;_**Note:** The `SpacedLogger` should add a space or "` `" between each character of the String argument passed into its methods._


&emsp;a. If the `log` method received `Hello` as an argument, it should print `H e l l o`

&emsp;b. The `error` method should do the same, but with `ERROR:` preceding the spaced out input (i.e. `ERROR: H e l l o`)


### 6. Create a class named `App` that has a `main` method.

&emsp;a. In this class instantiate an instance of each of your logger classes that implement the `Logger` interface.

&emsp;b. Test both methods on both instances, passing in Strings of your choice.
