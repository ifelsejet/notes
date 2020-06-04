# 4. ls (List Directories)
* Now that we know how to move around the system, how do we figure out what is available to us?
* We use the ls command, that list the content the directory contains
    * ls  or "ls /home/pete (as an example)"
* It is important to note that not all files in a directory will be visible using ls
    * Filenames that start with "." are hidden
* We can view them using ls and pass the -a flag to it (a for all)
    * $ ls -a
* We can also use the -l flag, which shows a list of files in a long format
    * It will show you (from the left): file permissions, number of links, ower name, owner group, file size, timestamp of last modification, and file/directory name
* We can also combine flags to add more functionality (ls -la)

## More Commands
* ls -R: recursively list directory contents
* ls -r: reverse order while sorting
* ls -t: sort by modification time, newest first