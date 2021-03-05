# Take-the-command-challenge-Pratiksha-aquila-
Take-the-command-challenge-Pratiksha(aquila) for assignment 2
 ## Q 1Print the current working directory.
 Ans pwd
 ##  2 Q List names of all the files in the current directory, one file per line.
 Ans ls
## Q 3 There is a file named access.log in the current directory. Print the contents.
Ans pg access.log
## Q 4 Print the last 5 lines of "access.log".
Ans tail -n 5 access.log
## Q 5 Create an empty file named take-the-command-challenge in the current working directory.
Ans touch take-the-command-challenge;
OP
## Q 7 Create a directory named tmp/files in the current working directory
Ans mkdir tmp mkdir tmp/files
OP
## Q 8 Move the file named take-the-command-challenge to the directory tmp/files
Ans mv take-the-command-challenge tmp/files
Op
## Q 9 A symbolic link is a type of file that is a reference to another file.
Ans ln -s tmp/files/take-the-command-challenge
OP
## Q 10 Delete all of the files in this challenge directory including all subdirectories and their contents.
Ans find . -delete
op 
## Q 11 There are files in this challenge with different file extensions. Remove all files with the .doc extension recursively in the current working directory.
Ans rm -r **/*.doc
OP
## Q 12 There is a file named access.log in the current working directory. Print all lines in this file that contains the string "GET".
Ans grep GET acess.log
OP
## Q 13 Print all files in the current directory, one per line (not the path, just the filename) that contain the string "500".
grep 500 -rl
OP
## Q 14 Print the relative file paths, one path per line for all filenames that start with "access.log" in the current directory.
Ans ls
OP access.log
access.log.1
access.log.2
 ## Q 15 Print all matching lines (without the filename or the file path) in all files under the current directory that start with "access.log" that contain the string "500"
Ans grep 500 -rh
OP 

