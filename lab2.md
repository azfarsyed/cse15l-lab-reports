# Week 3 - Servers and Bugs 

## Part 1 

Here is a no argument screenshot: 

<img src = "images/404NotFound.png" width = "700">

Only the `return "404 Not Found!";` segment runs as there is no argument passed in the query.

Here is a screenshot of the argument `/add-message?s=Hello` being passed 

<img src = "images/Hello.png" width = "700">

This argument returns the message `Hello` on the page. The part of the code segment that runs is shown below: 

<img src = "images/argument.png" width = "400">

## Part 2

Here is a failure inducing input for the `reversed` function 
`
int[] input = {1, 2, 3, 4};
assertArrayEquals(new int[]{4, 3, 2, 1}, ArrayExamples.reversed(input));`
