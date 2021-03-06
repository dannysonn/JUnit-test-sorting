# Test Sorting

This exercise is about getting familiar with unit testing and JUnit 4.12 in particular.

Design and code a simple sorting method in the [Sorting](src/main/java/com/epam/rd/autotasks/Sorting.java). Here are some details:
- The method sorts an integer array in the ascending order.
- The integer array is passed as a parameter to the method.
- When the given array is null, the method must throw an IllegalArgumentException.

Complete the test methods in the [SortingTest](src/main/java/com/epam/rd/autotasks/SortingTest.java) class. 
Use assertions to check your sorting methods. Be sure to use @Test annotation parameters to catch expected exceptions.

To pass the exercise, your tests must correctly detect flaws of some other sorting method implementations.
There are special tests in the [SortingTestsTest](src/test/java/com/epam/rd/autotasks/SortingTestsTest.java) class
that apply your tests to your implementation and some other problematic (“bad”) ones.
Your sorting method must pass your tests while other implementations must fail your tests in some cases.