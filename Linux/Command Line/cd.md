# 3. cd (Change Directory)
* There are 2 different ways to specify a path
## Absolute path
* Path from the root directory (most commonly shown as a slash)
* Every time your path starts with "/" it means you are starting from the root directory
    * For example: "/home/pete/Desktop"
## Relative path
* The path from where you are currently in
* If I was in location "/home/pete/Documents" and wanted to get into a directory inside Documents called "taxes", I don't need to specify thr whole path from root like "/home/pete/Documents/taxes". I can just go to "taxes/" instead 

## The cd command
* Now that we know how paths works, we need something to help us change paths (the cd command)
    "$ cd /home/pete/Pictures"
* So now I've changed my directory location to /home/pete/Pictures, inside this directory I have a folder called "Hawaii", I can navigate to that folder with:
    * cd Hawaii
* We can just use the name of the folder becuase we were already in the directory that the folder lives in

## Shortcuts
 * . (current directory). This is the directory you are currently in.
    *  $ cd .
* .. (parent directory). Takes you to the directory above your current.
    * $ cd ..
 * ~ (home directory). This directory defaults to your “home directory”. Such as /home/pete.
    * $ cd ~
* "-" (previous directory). This will take you to the previous directory you were just at.
    * $ cd -