
## Linux Fundamentals

Find 
-- find -name passwords.txt where the command will look through every folder in our current directory for that specific file

grep
--grep "81.143.211.90" access.log
grep to search the entire contents of this file for any entries of the value that we are searching 

# shell

Operator "&"
This operator allows us to execute commands in the background

Operator "&&"
Unlike the "&" operator, we can use "&&" to make a list of commands to run for example command1 && command2. However, command2 will only run if command1 was successful.

Operator ">"
--Output director
echo hey > welcome, where we want the file created with the contents "hey". It always override it

Operator ">>"
Not overwriting any content just put it at the end