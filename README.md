[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=8474195&assignment_repo_type=AssignmentRepo)
# Overview

Very simple example including an App and a few tests 
(illustrating different testing styles).

# Running the app

    sbt run

# Running the tests

    sbt test

# Determining test coverage

    sbt coverage test
    sbt coverageReport
	
Now open this file in a web browser:

    target/scala-2.13/scoverage-report/index.html
    
# Running a Scala console

This allows you to explore the functionality of the classes in this
project in a Scala REPL while letting sbt set the classpath for you.

    sbt console
