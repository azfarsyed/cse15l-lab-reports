# Week 9 - Researching Commands RELOADED

### *Alternate ways to use the command `find`*

####  #1: `find /dir -size (+,-)(specified size)`

This command finds all the files under or over a specified size in a directory. 

Here is an example using the less than feature(-(size)): `find travel_guides/berlitz1 -size -2k`

<img src = "images/find_size.png" width = "600">

In this case, the command prints out all the files in the berlitz1 folder that are less than 2 kilobytes of data. 

Here is an example using the greater than feature(+ size): `find travel_guides/berlitz1 -size +2k`

<img src = "images/find_size_plus.png" width = "600">

In this case, the command prints out all the files in the berlitz1 folder that are greater than 2 kilobytes of data(There are many more files in this command output that I just did not include to save space). 


####  #2: `grep -i "(txt)" (filename)`







####  #3: `grep -i "(txt)" (filename)`







####  #4: `grep -i "(txt)" (filename)`
