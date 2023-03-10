# Week 5 - Researching Commands

### *Alternate ways to use the command `grep`*

####  #1: `grep -i "(txt)" (filename)`

Here is an example of the case insensitive grep command. `grep -i "this" Bahamas-Intro.txt`

<img src = "images/this_input.png" width = "600">

<img src = "images/this_output.png" width = "600">

Under this command, all the lines with "this" (case insensitive) are printed out. In this case, the entirety of lines 6,7,17,19,20 are printed out. The way I used this command, although it works, isn't very useful to me because the sentences of this file aren't split by line. Individual sentences aren't being returned, rather the entire code line is. The grep -i is useful if you want to search for a text that is case insensitive in a file. If you would only like to retrieve the case sensitive word, make sure it is in its own line since this command prints out the entire line. 

Here is another example of the case senstive grep command. `grep -i "ch4.txt" find-results.txt`

<img src = "images/grepi_ch4.png" width = "600">

<img src = "images/ch4.png" width = "300">

In this case, both files `ch4.txt` and `CH4.txt` are printed out because grep-i is case insensitive. This is particularly useful when you want to find files or texts in which you do not care if there are caps. In this case, I wanted to return all files that had the name "ch4" no matter the case. 

####  #2:`grep -c "(txt)" (filename)`

This command returns how many times a certain word appears in a file. It is useful because it can let me know how many times a word appears in a text file. Here is an example: `grep -c "this" Bahamas-Intro.txt`

<img src = "images/grepc_this.png" width = "600">

Here is the amount of times "this" appears(case insensitive) `grep -i -c "this" Bahamas-Intro.txt`

<img src = "images/grep_i_c_this.png" width = "600">

Alternateively, I can figure out how many text files there are in a certain directory by saving all file names in a text file and then using this command to count the amount of files that contain the ".txt" string. 
``` 
find written_2 > find-results.txt
grep -c ???.txt??? find-results.txt
``` 
<img src = "images/txtCount.png" width = "600">

#### #3: `grep -r "(txt)"`

This command looks through all the files in the current directory for the word you are looking for and returns the line in which it is in. Here is an example: `grep -r "Lucayans"`

<img src = "images/grepr.png" width = "600">

Here is another example where I check where the text "El Abuelo" appears in the docsearch directory. `grep -r "El Abuelo"`

<img src = "images/grepr2.png" width = "600">

#### #4: `grep -v "(txt)"`

This command returns all the lines that do not contain the text specified. It is useful so that I can return the files I want to access. Here is an example: `grep -v non-fiction find-results.txt`. Here everything not in the non fiction directory is returned. 

<img src = "images/grepv_nonfiction.png" width = "600"> 

Here is another example where I return everything that is not in the travel guides directory. `grep -v travel_guides find-results.txt`

<img src = "images/grepv_travelguide.png" width = "600"> 

For all of these commands, I used the site: https://www.cyberciti.biz/faq/howto-use-grep-command-in-linux-unix/


