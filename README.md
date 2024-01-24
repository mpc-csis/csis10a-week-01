# CSIS10A Week 1 - Introduction to Variables and Types

> "Computer programming is tremendous fun. Like music, it is a skill that derives from an unknown blend of innate talent and constant practice. Like drawing, it can be shaped to a variety of ends – commercial, artistic, and pure entertainment. Programmers have a well-deserved reputation for working long hours but are rarely credited with being driven by creative fevers. Programmers talk about software development on weekends, vacations, and over meals not because they lack imagination, but because their imagination reveals worlds that others cannot see." ~ Larry O'Brien and Bruce Eckel

This week is all about getting started programming in Java, learning about different errors you can make and how to correct them, and working with variables and print statements to produce meaningful output.

## This weeks goals

By the end of this unit you will be able to:

1. compile and run Java programs in the BlueJ development environment
2. write programs using variables and print statements, and perform simple computations
3. debug basic syntax and logic errors
4. Start using git to get assignments

## Day 1

- [Survey](https://forms.gle/ZhnXcJBuhk6tU42W6)
- [Lecture 1](https://docs.google.com/presentation/d/16rVGgM_dYfxmIO0ouby6pf1Ar_hX4YKR4c-yeL4iO7o/edit?usp=sharing)
- [Lab 0 - Intro to Git](https://classroom.github.com/a/1A5I5rnW)
- [Lab 1 - Part A: The Way of the Program](https://docs.google.com/document/d/17HY3iNOAnszaR81U0djk7VWTSvZ8wHx_cJQVhF19wkw/edit?usp=sharing)

## Day 2

- [Lecture 2](https://docs.google.com/presentation/d/1Y3L-AwhMRISFrwC65jRwTdTzbuo6hSixPjBICya3t-s/edit?usp=sharing)
- [Lab 1 - Part B: Variables and Types](https://docs.google.com/document/d/17HY3iNOAnszaR81U0djk7VWTSvZ8wHx_cJQVhF19wkw/edit?usp=sharing)

## Assignment

### Tasks

1. Read chapter 1 and 2.
2. Install Java and BlueJ on your own computer.
3. Clone the repo for [assignment 1](https://classroom.github.com/a/EY8zSzIN) and follow the instructions in the README.md file.

### Submitting your work

1. Make sure your name appears in a comment within each .java file
2. Then, in BlueJ, choose Project>Create JAR File.
3. In the dialogue that pops up, check the “Include Source” box
4. Click continue, then navigate to the location you want the jar file to be placed.
5. TBD

## Developer tool of the week

### [javac](https://docs.oracle.com/en/java/javase/21/docs/specs/man/javac.html)

The Java Developement Kit (JDK) contains a command line compiler for java programs. As a programmer you should:

1. Know how to use a terminal/command window.
2. Know how to use javac from the command line!!

> [!IMPORTANT]
> __Windows Users Read THIS!!__: As discussed in class, the java and javac must be added to the Windows PATH environment variable before you can use them in PowerShell or a Command Window. Instuctions for configuring the PATH variable can be found here. You will also need to set the JAVA_HOME environment variable.

#### 1. Open a terminal/command prompt

__Windows__: Go to the start menu. Then follow the instructions here

__Mac OS X__: The Terminal application can be found at `/Applications/Utilities/Terminal.app`. Just double click it to launch it.

__Linux__: If you are running linux you should already know how to open a terminal :-)

#### 2. Compile a program using javac

1. Write a simple java program and save it. (e.g. HelloWorld.java).
2. In the terminal, change to the directory that contains the java file. On Windows, you change to the drive containing the java file and then cd to the directory.

```sh
# Windows
U:
cd \Path\To\Directory\With\Java\File.
```

```sh
# Mac/Linux
cd /Path/To/Directory/With/Java/File
```

3. Compile the java code using the command: `javac [filename]`. For example: `javac HelloWorld.java`. This example will create a file named HelloWorld.class.

#### 3. Run the program using java

A simple java program can be run using java command: `java [classname]`.

In our example it's `java HelloWorld`. Important: Notice that we do not use an extension!! When we pass 'HelloWorld' to java, it knows to look for 'HelloWorld.class'

#### Shortcut for Single file programs

Since Java 11, you can run a single file Java program without using `javac`. For example, if you have a file `HelloWorld.java`, you can compile it and run it in a single step using `java HelloWorld.java`.

### Shell Commands for Powershell/Terminal

- `rm` - Remove file e.g. `rm HelloWorld.class`
- `cd` - Change directory: `cd csisi10a`
- `ls` - list directory contents: `ls` or `ls csis10a`
- `pwd` - present working directory 
- `mkdir` - Make directory: `mkdir csis10a`

### git

- [Starter Course for GitHub](https://classroom.github.com/a/1A5I5rnW)
- [Beginner's Guide](https://developers.redhat.com/articles/2023/08/02/beginners-guide-git-version-control#)
