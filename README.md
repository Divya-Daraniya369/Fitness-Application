# FitnessApp

An App that aids in Health Maintenance 
### Features :
- Major Basal metabolic rate(BMR)
- Know Your Body Mass Index
- Find Your Daily Calorie Needs
- Get Calorie, Fat, Protein and Sugar for your food

### GUI of Application
- [HomePage](https://github.com/Divya-Daraniya369/Fitness-Application/blob/main/GUI_1.png)
- [User_Choice](https://github.com/Divya-Daraniya369/Fitness-Application/blob/main/GUI_2.png)

## Exercise A for Advanced Software Engineering

### General
A Fitness Application is found in this repository. That user can assess their BMR(Basal Metabolic Rate), BMI(Body Mass Index), and track their calories depending on activity levels, as well as a wide range of dietary ingredients such as protein, carbs, fat, sugar, and vitamins. Furthermore, this software makes their lives easier, particularly in terms of health.

## Exercise B for Advanced Software Engineering

### 1 Git

I used Git to commit and publish my work to GitHub on a regular basis, and I did everything in my IDE (PyCharm), regularly uploading my code to GitHub through IDE.

### 2 UML

For this application, I produced three separate UML diagrams. If colors are used, green indicates that these features will be implemented. The purple hues indicate that the function has been activated.

- Characterize the system's dynamic characteristics An [Activity Diagram](https://github.com/Divya-Daraniya369/Fitness-Application/blob/main/Activity%20Diagarm.png) is essentially a flowchart that depicts the flow from one activity to another.

- A [Use Case Diagram](https://github.com/Divya-Daraniya369/Fitness-Application/blob/main/Use%20Case%20Diagram.png) is a visual representation of a user's potential interactions with a technology.

- A [State Diagram](https://github.com/Divya-Daraniya369/Fitness-Application/blob/main/State%20Diagram.png), it describes the state of the components as well as state changes caused by an event.


### 3 DDD

I created a [problem space](https://github.com/Divya-Daraniya369/Fitness-Application/blob/main/DDD%20Problem%20Space%20Final.png) with several subdomains that needed to be implemented for the project.  As shown in green color that part already has  been implemented, , while others will be implemented in the future, as shown in yellow color , once I will  receive the investment from Edlich.


### 4 Matrics

I utilized SonarQube, which automatically analyzes the submitted source code based on various criteria. SonarQube is an open-source tool for continuous code quality inspection that does automated inspections with static code analysis to find bugs and code smells, as well as many other Matrices.

### 5 Clean Code Development
This project was created with the Python programming language.

-  Used either ' ' or " " throught out the application develpoment. I used " " for this application. 
-  Use Constant for avoid re-write same code.
-  Give meaningful name to variables and functions. 
-  Naming Conventions 
-  Give meaningful comment whenever possible, it allows anyones to understand your code better. 

### 6 Build Management

Maven is used for build management.

Just to learn how to use a building tool I wrote this Java program using Maven. However, For build in CI /CD Pipelines i utilizing GitHub Actions.

This is not a part of my FitnessApp Project, but for the purpose of build management. I wrote java code. My Java [Code](https://github.com/Divya-Daraniya369/Fitness-Application/blob/main/AppTest.java).


### 7 Unit-Tests

I've written a 5 test case to test each of my features before they go into production.

I've also provided a [snapshot](https://github.com/Divya-Daraniya369/Fitness-Application/blob/main/test_case.png) of all passed test cases.

Also, you can see my test cases [here](https://github.com/Divya-Daraniya369/Fitness-Application/blob/main/test_bmi.py).

### 8 Continuous Delivery

I utilized GitHub Actions for the continuous delivery pipeline. Every time I push to my repository, a new build is initiated, and test cases are executed.

Also, i have created 2 Jobs. 1)  Build 2)  Test

I have an attached 2 scripts files for [build](https://github.com/Divya-Daraniya369/Fitness-Application/blob/main/build.yml) and [test](https://github.com/Divya-Daraniya369/Fitness-Application/blob/main/test.yml).

You can see successful implementation of both the Jobs. For [Build](https://github.com/Divya-Daraniya369/Fitness-Application/blob/main/cd_build.png) and [Test](https://github.com/Divya-Daraniya369/Fitness-Application/blob/main/cd_test.png).




### 9 IDE 

For this application development, I utilized PyCharm as an IDE. PyCharm is a development tool for the Python programming language.

PyCharm has numerous capabilities , one of which is an integrated git plugin for committing, pushing and pulling.

Shortcuts I used while making this application :

- Ctrl + Shift + K : For Push Commit to application.
- Ctrl + k : For commit.
- Used TAB: For automatic get variable or function name  when typing.
- Ctrl +/ : Add/remove line or block comment
- Ctrl+Shift+/ : Comment out a line or block of code.







### 10 DSL

This DSL has no relevance on my FitnessApp project ( it written be in python language)

In this program, individuals can find out how much they eat in terms of calories, sugar, protein, and sugar. Overall, what they eat and how much calorie, sugar, protein, and sugar they consume on a daily basis from dawn to night. This will assist them in tracking food measurement.

The external DSL code is stored in the [.dsl file](https://github.com/Divya-Daraniya369/Fitness-Application/blob/main/fitness.dsl). The [interpreter](https://github.com/Divya-Daraniya369/Fitness-Application/blob/main/fitness.py) converts the .dsl file into Python code and runs each line.

### 11 Functional Programming

I created python code to compute BMI (Body Mass Index). It is not part of my project, however I am interested in learning about functional programming techniques.

- ### Final data structures: 
    Often known as immutables, are data structures that cannot be changed after they have been formed. Using final data structures in functional programming helps to avoid side effects and make programs more predictable. 

- ### Side effect free functions: 
    Pure functions are those that have no side effects. They receive inputs, calculate them, and return a value without affecting any state outside of their scope. 

- ### Higher-order functions: 
   Higher-order functions are those that accept other functions as arguments and return other functions as results. This enables you to write more abstract, reusable code. 

- ### Functions as arguments and return values : 
    Functions can be supplied as parameters to other functions and also returned as a function's result. This enables the creation of functions that may be constructed and reused in a variety of ways. 

- ### Closures / anonymous functions: 
    Closures are functions that continue to have access to variables defined in the scope in which they were defined after the scope has finished. Anonymous functions, also known as lambda expressions, lack a specified identifier and are frequently utilized as parameters to higher-order functions.






