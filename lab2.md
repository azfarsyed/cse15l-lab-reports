# Week 3 - Servers and Bugs 

## Part 1 

Here is a no argument screenshot: 

<img src = "images/404NotFound.png" width = "700">

Only the `return "404 Not Found!";` segment runs as there is no argument passed in the query.

Here is a screenshot of the argument `/add-message?s=Hello` being passed 

<img src = "images/Hello.png" width = "700">

`if (url.getPath().equals("/add-message")) {
  String[] parameters = url.getQuery().split("=");
  if (parameters[0].equals("s")) {
    message +=  parameters[1] + "\n";
    return message;
    }
} `
