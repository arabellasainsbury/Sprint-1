Without using jargon, how would you describe the command line to a lay person (e.g. your mum)?
The command line is a text interface on your computer. you can look through, change and create new files just as you would with the finder window on your mac, but rather than being graphic, everything is text based. to do this there are specific simplified commands.

List 10 terminal commands and in plain english (i.e. with minimal technical jargon) describe what they do:

1: pwd - Print working directory - will show you the names of the working directory. It is useful to show you where you are if you get lost.
2: ls - lists all files and directories in that working directory
3: cd - Change directory, cd followed by a directory name, switches into that directory
4: cd .. - will navigate you up one directory, eg from arabella/january/ to arabella/ 
5: rm -  rm deletes files, eg: $rm harrypotter.txt
That would delete the file harrypotter.txt
6: nano - nano is a text editor for the CLI accessable by keyboard input
7: touch - the touch command creates a new file within the working directory. eg:
$touch wizard.txt
would create a new file named wizard.txt inside the arabella/january directory.
If there was already a file within that directory named wizard.txt, then this function would update the modification time of the file.
8:uniq - stands for "unique", takes a file name and prints out every line, but removes any EXACT duplicates. So each name is... unique :)
9:source - activates the changes in a particular session, rather than closing and restarting, the changes are available straight away
10:Sort - takes a file and arranges the lines alphebetically and printing to standard output 
eg:
$sort fruit.txt
apple
banana
grape
orange
(They have been SORTed alphaetically)