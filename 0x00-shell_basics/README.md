a script that prints the absolute path name of the current working directory  "pwd"
Display the contents list of your current directory "ls"
a script that changes the working directory to the user’s home directory  "cd"
Display current directory contents in a long format . "ls -l"
Display current directory contents, including hidden files   "ls -la .."
Display current directory contents :- Long format, with user and group IDs displayed numerically, And hidden files "ls -lna"
Make directory "mkdr"
move file "mv"
delete a file "rm"
delete directory "rm -r"
a script that changes the working directory to the previous one "cd -"
Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format "ls -al . .. /boot"
Write a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script "file /tmp/iamafile"
Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory. "ln -s/bin/ls _ls_"
Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.  "cp -un*.html .."
