# Introduction to Debugging in IDE

## Learning Objectives
- Know how to debug a Java application
- Understand breakpoints
- Understand the debugger console
- Know how to evaluate code fragments

## Task
As an introduction to debugging:
- watch the following video: [Intro to Debugging video](https://youtu.be/ErVZrVWZrko)


Answer the following questions:
1. What is the purpose of a breakpoint?
* To mark a part of the code we want to debug (like a test not passing)

2. Does the line of code on a breakpoint run when you start debugging?
* No, the debug will run normally until it reach the breakpoint. It will stop just before it is run.

3. How do we debug the next line of code?
* Press the "step over" button

4. What does the step into command do?
* "Step into" will get us inside of the method or line being debugged, starting from
the beggining. For example: Going into "Game.deal()" will jump the view to the
part of the code where "deal()" works, showing us the code/variable and letting us
to debug that part of the code.

5. What is the difference between evaluate expression and evaluate code fragment?
* Evaluate expression will check one individual expression on our project
* Evaluate code fragment will allow us to evaluate several lines of code, along
  with new code we can write, just like a java playground file created on our project. 
