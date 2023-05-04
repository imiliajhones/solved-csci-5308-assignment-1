Download Link: https://assignmentchef.com/product/solved-csci-5308-assignment-1
<br>
Objectives

<ul>

 <li>Practice developing effective unit tests</li>

 <li>Practice implementing unit tests with JUnit</li>

 <li>Practice working with TDD Preparation:</li>

</ul>

<h1>Problem Statement</h1>

You have three main tasks in this assignment:

<ul>

 <li>Create a set of unit tests using for the provided classes which are already developed</li>

 <li>The correctness of the code using your unit tests and if you find any bug fix it.</li>

 <li>Use TDD to design unit tests and develop the parts of code that are missing, use the specification on the comments to do this.</li>

</ul>

<h1>Background</h1>

You have inherited some buggy and incomplete code for computing shortest path solutions to the board game Ticket to Ride. The previous developer left the company, so it is your job to finish the software. Your boss has hired you to write a comprehensive set of tests for part of the codebase.




Given a game board of rail segments and a list of routes (pairs of cities), the code is supposed to compute the total cost of building a network between the given routes, assuming that the shortest distance for each route is chosen. This can be computed by computing shortest paths for each route using Dijkstra’s shortest path algorithm.




You will be provided with a partial codebase for distance computation, a specification, some JUnit5 test class, and a list of classes for which you are to create unit tests.  Your job is to create the test suite, identify and fix the bugs (if any) and finish the methods not implemented in the classes.

<h1>Task</h1>

<ol>

 <li>Read the specification of what the code is supposed to do in docs/specification.pdf</li>

 <li>Create a set of unit tests using JUnit5 using the provided classes. Remember that each class needs to have its own test class, with several tests to check the implemented methods.

  <ul>

   <li>java</li>

   <li>java</li>

   <li>java</li>

  </ul></li>

 <li>Implement a separate test class for each of the above target classes. Some sample empty tests and real tests have been provided. For each test class

  <ol>

   <li>Create as many tests for each method of each class as needed. But remember, each method must have at least one unit test.</li>

   <li>Each test should provide an appropriate message if it fails.</li>

   <li>Use good formatting and documentation in your tests, just like for any source code.</li>

  </ol></li>

 <li>All the test classes should compile and be runnable in IntelliJ. <strong>If your test classes do not compile, you will receive 0 on the assignment.</strong></li>

 <li>Record all detected errors in a file called txt in the docs directory. Each error should have the following information:

  <ol>

   <li>Class name</li>

   <li>Method name</li>

   <li>Test name that caught the error</li>

   <li>Message that the test method generated</li>

  </ol></li>

</ol>


