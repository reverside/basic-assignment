# Tools & Practices

### Congratulations !!! 
Since you are on this page, it means you have passed through previous 2 levels : 
* Basic Programming 
* Language Fundamental

#### Objective:
Objective of this level, is to ensure that you can solve a problem with a programming language using indutry standard tools and following standard practices. At this level, we assume that you have basic knowledge of programming and you understands OPPS concepts. So here, we will verify that you can apply all your learnings from last 2 levels with a source code management tool (SCM) like git , build tool like maven/dotnet CLI and can write unit test using a standard unit test library like Junit/xUnit. At this level if you still don't know about them, then you must learn and get yourself comfortable with before working on the assignment.

#### Process:

* You will be evaluated over the assignment given, you will find the assignemnt in assignment.text file here.
* You will get one week to complete the assignment with the tools & practices as mentioned below. 
* Your score will based on your understanding over scm, build tool and unit testing practices.
* Standard practices, design practices and clean code practices followed will also impact will score.
* For every mistake or violation of the rule or bad practice or defect/bug you will get -1 point
* You must score zero to clear this level  and you may get max 2 chances to clear this level.
* You may be asked questions to evalaute your understanding over the tools & practices.
* Reviewer may build your project on his/her machine and may run your application with different data file.

#### Tools & Technology :

##### Language :
* Java
* C#

##### Source Code Management :
* git (Java & C#)

##### Build Tool :
* maven (Java)
* dotnet CLI (C#)

##### Unit Test:
* JUnit (Java)
* xUnit (C#)

#### Few Common Mistakes:
* Don't create the project with any IDE, initial project must be created using build tools like maven or dotnet CLI. Later on you can import the project to any IDE for rapid development. But the project must be created with a build tool and one should be able to build the project with the build tool without any IDE. Project structure must follow standard build tool suggested structure (maven/dotnet CLI) and should be made clean, simple and meaningful as much as you can. Must follow standard practices while working with your scm tool.
* Don't distribute your source code through email, rather put your source code on any cloud based git server (like github) and share the source code as a link to your respository. Don't keep the files/folders generated by IDE or generated during build process in git server, rather ignore them using .gitignore. Only those files/folders should be kept in repository which are necessary to build the code after a fresh checkout. Must provide a README.md file formatted with github format, at the root of the project documenting how to build and run the project and the minimal tools/softwares needed (with version number) to build and run the project on a new machine.
* Standard naming convention must be followed through out the project like project name, namespace, classes, methods, varaibles etc. Proper access specifier for members must be used and must keep the source code clean and properly aligned. Dont keep anything unused or not required. Every word, line, file you keep in your source code must have some significance and you must understand what this is for and why it is required. 
* Don't all logic inside main method, rather keep main method just as an entry point to start your application. Don't keep all your logic in one class/method , rather design it with following OOPS concepts and Design Principles. Possible exception scenarios must be analyzed and handled appropriately. Methods should not lengthy, rather split it into smaller methods appropriately. 
* You must have a test module for unit testing as prescibed by the build tool. You must use the mentined test libraries for your unit tests. Each public method in a class containing logic should have corresponding unit tests to cover all scenarios. You may skip unit tests for DTO classes, which generally contains getters and setter for its properties. Both positive and negative scenarios must be covered as a part of your unit tests.

###### NB:
Above are some basic practices which must be followed. But you must learn more detail about them as well as read upon standard practices & clean code to apply in your project. And you must know the fundametals of the tools and must apply best practices in your project using them.

#### Frequnty Asked Questions:
Following are some frequently asked questions, which you may be asked to you during evaluation and it will also make you think to go more detail on the tools.

##### SCM (Git)
* What is SCM & Why we need a SCM ?
* What are some commonly used scm products in market ?
* What is git and how it is different from other SCM products in market ?
* Explain git architecture 
* What are the few commonly used git commands and explain them
* What is the difference between git and github ?
* What is the difference between git commit and push ?
* How to install a git client ?
* How to know if git client is installed on a machine or not ?
* What is cloning ?
* How to enable git to an existing folder and how you link it to am existing remote repository ?
* Difference between git pull , push and fetch
* How to know the current git branch ?
* How to switch branches ?
* How to create a new branch locally ?
* What is a tag and how to create a tag ?
* How to merge two branches ?
* How to rollback all your changes if you dont want to commit ?
* How to find which files you have chnagesand what you you have changes in a file before any commit ?
* When and how often you must commit ?
* When and how often you must push ?

##### Build Tool (Maven)
* What is maven ?
* Why we need maven ?
* Explain maven life cycle
* Explain each phase of maven life cycle
* What are some commonly used maven commands , exlain  ?
* How to install maven ?
* How to know maven is installed on a machine ?
* What is setting.xml and where it typically stays ?
* Where you can find your local repsitory ?
* Explain maven project structure

##### Build Tool (dotnet CLI)
* What is dotnet CLI ?
* How to install dotnet CLI ?
* How to find cli is installed on a machine or not ?
* Most commonly used cli commands and its meaning 
* How to add a new library to your project using cli ?
* Depedency management using cli 
* How to create a new project and it's test module ?
* Explain standard CLI project structure 

##### Unit Testing (JUnit/xUnit)
* What is unit testing ?
* What is typical unit test module structure suggested by your build tool ?
* How to write a unit test ?
* How to run a unit test from cmd ?
* How to run all tests from cmd?
* How to skip tests during build?
* How to ignore a test ?
* Explain some of the assert methos available in your unit test lib
* How many minimal tests you should write for  a method ?
* What is Test Driven Development (TDD)?
* What is mocking and how to mock in unit testing ?
* Why do you need mocking while writing unit tests ?
* What is difference between unit test and integration test ?
* What is unit test coverage and how to calculate it ?

#### Reference :

##### Source Code Management :
* git : https://www.atlassian.com/git/tutorials

##### Build Tool :
* dotnet CLI(C#) : 
* http://www.tutorialsteacher.com/core/net-core-command-line-interface
* https://www.youtube.com/watch?v=FcGf69qYGoA

* maven   (Java) : 
* https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html
* https://www.youtube.com/watch?v=XulPrVct_xQ

##### Unit Test :
* xUnit(C#)   : https://docs.microsoft.com/en-us/dotnet/core/testing/unit-testing-with-dotnet-test
* JUnit(Java) : https://dzone.com/articles/junit-testing-part-i-setup-with-simple-example

##### Best Practices:
* https://www.khanacademy.org/computing/computer-programming/programming/writing-clean-code/e/quiz--clean-code
* https://www.codingdojo.com/blog/clean-code-techniques/
* http://www.garshol.priv.no/blog/105.html
* https://www.git-tower.com/learn/git/ebook/en/command-line/appendix/best-practices
* https://www.codeproject.com/Articles/768052/Golden-Rules-Of-Good-OOP
* https://medium.com/mindorks/how-to-write-clean-code-lessons-learnt-from-the-clean-code-robert-c-martin-9ffc7aef870c

