
# Calculator


## Introduction
 
This project is used to create a calculator in Maven using Scala programming Language.


## Technology

Calculator is implemented in Scala programming language. Scalatest library was used for testing Calculator's implementation and Maven for project building.


## Requirements

* Java 11
* Scala 2.13.5


## Commands

###clean

This command cleans the maven project by deleting the target directory. The command output relevant messages.

 ```
 mvn clean 
 ```

###compile
This command compiles the scala source classes of the maven project.

```
 mvn compile 
 ```
###package
This command builds the maven project and packages them into a JAR, WAR, etc.

```
 mvn package
 ```
###install
This command builds the maven project and installs the project files (JAR, WAR, pom.xml, etc) to the local repository.

```
 mvn install
 ```

## Library dependencies

* scalatest - test driven development
* scala

More details about project libraraies (e.g. version etc..) can be found in file **pom.xml**




## Functionality


### Calculations


This functionality supports addition, subtraction, multiplication, division, power, Absolute and Modulus  on Double, Long and integer numbers.

e.g.

 ```
 2+5
 ```

A number of samples is given in test file **Calculatorimplementationspec** and **calculatorspec**.


Source files that are implementing this functionality are:

* Calculator.scala
* CalculatorImplementation.scala
