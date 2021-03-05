# Take-the-command-challenge-Pratiksha-aquila-
ake-the-command-challenge-Pratiksha(aquila) for assignment 2
 ## Q Print the current working directory.
 Ans pwd
 op /var/challenges/current_working_directory

 ##  Q List names of all the files in the current directory, one file per line.
 Ans ls
 op  01-take.txt
02-the.txt
03-command.txt
04-challenge.txt
## Q There is a file named access.log in the current directory. Print the contents.
Ans pg access.log
op  63.56.115.58 - - [09/Jan/2017:22:29:57 +0100] "GET /posts/2/display HTTP/1.0" 200 3240
75.113.188.234 - - [09/Jan/2017:22:30:43 +0100] "GET /posts/foo?appID=xxxx HTTP/1.0" 200 1116
69.16.40.148 - - [09/Jan/2017:22:34:33 +0100] "GET /pages/create HTTP/1.0" 500 3471
225.219.54.140 - - [09/Jan/2017:22:35:30 +0100] "GET /posts/foo?appID=xxxx HTTP/1.0" 500 2477
207.243.19.2 - - [09/Jan/2017:22:38:03 +0100] "GET /bar/create HTTP/1.0" 200 1116
## Q Print the last 5 lines of "access.log".
Ans tail -n 5 access.log
OP 199.37.62.156 - - [09/Jan/2017:22:42:18 +0100] "GET /posts/1/display HTTP/1.0" 200 2477
55.74.240.123 - - [09/Jan/2017:22:44:25 +0100] "POST /posts/1/display HTTP/1.0" 200 3471
251.111.109.143 - - [09/Jan/2017:22:49:02 +0100] "GET /posts/foo?appID=xxxx HTTP/1.0" 200 2477
101.163.230.250 - - [09/Jan/2017:22:52:31 +0100] "DELETE /posts/2/display HTTP/1.0" 404 2477
200.19.168.148 - - [09/Jan/2017:22:57:11 +0100] "GET /posts/foo?appID=xxxx HTTP/1.0" 200 3471
## Q Create an empty file named take-the-command-challenge in the current working directory.
Ans touch take-the-command-challenge;
OP
## Q Create a directory named tmp/files in the current working directory
Ans mkdir tmp mkdir tmp/files
OP
## Q Move the file named take-the-command-challenge to the directory tmp/files
Ans mv take-the-command-challenge tmp/files
Op
## Q A symbolic link is a type of file that is a reference to another file.
Ans ln -s tmp/files/take-the-command-challenge
OP
## Q Delete all of the files in this challenge directory including all subdirectories and their contents.
Ans find . -delete
op 
## Q There are files in this challenge with different file extensions. Remove all files with the .doc extension recursively in the current working directory.
Ans rm -r **/*.doc
OP

 

