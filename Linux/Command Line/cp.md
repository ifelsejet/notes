# 10. cp (Copy)
* cp fileName filePathtoCopyto
* You can copy multiple files/directories as well as use wildcards (character that can be used for pattern based selection)
## Wildcards
* "*" the wildcard of wildcards, it's used to represent all single characters or any string.
* ? used to represent one character
* [] used to represent any character within the brackets

* $ cp *.jpg /home/pete/Pictures
* This will copy all files with the .jpg extension in your current directory to the Pictures directory.

* A useful command is to use the -r flag, this will recursively copy the files and directories within a directory.