## JavaScript Performance

How to speed up your JavaScript code.

### Reduce Activity in Loops

Each statement in a loop, including the for statement, is executed for each iteration of the loop.

Statements or assignments that can be placed outside the loop will make the loop run faster.

### Reduce DOM Access

If you expect to access a DOM element several times, access it once, and use it as a ***local variable***.

### Reduce DOM Size

Keep the number of elements in the HTML DOM small,this will always improve page loading, and speed up rendering, especially on smaller devices.

### Avoid Unnecessary Variables

Don't create new variables if you don't plan to save values.

### JavaScript Functions

A JavaScript function is a block of code designed to perform a particular task, function is executed when "something" invokes it.

### Why Functions?

You can reuse code: Define the code once, and use it many times.