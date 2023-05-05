# Lab Report 3: Researching Commands
## grep command: command line options
1. ``` grep -c "<string>" fileName.txt ```
This command counts the number of matches in a file or set of file but doens't print the matches. 
2. ``` grep -r "<string>" ```
The -r command tells grep to search for files recursively in a directory and its subdirectories. 
3. ``` grep -v "<string>" ```
This command works opposite to the grep command in that it prints all the lines that don't match the specified pattern. 
## grep command: alternative commands with similar behavior
1. ``` ack```
This command searches for files for a specified pattern but works differently to grep in that it doesn't ignore certain files by default. 
2. ```ag```
This command is designed to be faster than grep and supports serching through files with certain extensions only
3. ```sed```
This command can be used to find and replace text in a file. 
[DDBeck.com](https://ddbeck.com/better-than-grep-for-writers/)
[Software Testing Help](https://www.softwaretestinghelp.com/grep-command-in-unix/)
