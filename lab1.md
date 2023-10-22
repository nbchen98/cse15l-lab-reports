**Command `cd`**
1. Share an example of using the command with no arguments.
![Image](cd1.png)
- The working directory when the command was run is /home/lecture1.
- The output I got was the working directory /home and I got this output because I ran cd with no arguments which takes me back to the home directory.
- This output is not an error.
2. Share an exmaple of using the command with a path to a directory as an argument.
![Image](cccd2.png)
- The working directory when the command was run is /home/lecture1
- The reason why the working directory became /home/lecture1 is because the command was ran with the argument lecture1 changing the directory to lecture1.
- The output is not an error.
3. Share an example of using the command with a path to a file as an argument.
![Image](cd3.png)
- The working directory when the command was run is /home/lecture1.
- The output received is "bash: cd: Hello.class: Not a directory". This output was received because the command cd can only be used to change the working directory.
- The output is an error because the working directory was not changed since Hello.class is a file and not a directory.

**Command `ls`**
1. Share an example of using the command with no arguments
![Image](ls1.png)
- The working directory when the command was run is /home/lecture1.
- The reason I got the output in the screenshot is because the command ls displays all the files and folders in the working directory.
- The output is not an error.
2. Share an exmaple of using the command with a path to a directory as an argument.
![Image](ls2.png)
- The working directory when the command was run is /home/lecture1.
- The reason I got the output in the screenshot is because the command shows the files in the directory, but does not change the working directory.
- The output is not an error.
3. Share an example of using the command with a path to a file as an argument.
![Image](lls3.png)
- The working directory when the command was run is /home/lecture1.
- The reason I got Hello.java as the output is because the command shows the files and folders in a directory, because Hello.java is a file, Hello.java was returned.
- The output is not an error.

**Command `cat`**
1. Share an example of using the command with no arguments.
![Image](cat1.png)
- The working directory when the command was run is /home
- The output I got was a blank line because the command prints the code from a file, but there is no file to print from.
- The output is an error because the cat command prints the code from a file, but a blank line is returned
2. Share an exmaple of using the command with a path to a directory as an argument.
![Image](cat2.png)
- The working directory when the command was run is /home
- The output I got was "cat: lecture1: is a directory" because cat prints the code from a file, but lecture 1 is a directory.
- The output is an error because cat prints code from a file not directories.
3. Share an example of using the command with a path to a file as an argument.
![Image](cat3.png)
- The working directory when the command was run is /home/lecture1
- The output I got was the code in Hello.java because cat returns the code from the file.
- The output is not an error.
