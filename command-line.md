Question 1:

Without using jargon, how would you describe the command line to a lay person (e.g. your mum)?
@me: mom do you know how to view files in a folder?
@mom: yes i know... i double click on the folder and it opens and then i can see the files... thats simple
@me: terminal is just the same.. instead of the double click i just type the instruction like to view files in a folder i use the command l -al
@mom: ahh.. okay... but y would you want to do that.. its so much simple to just click
@me: ohh mom, this was just an example...its so much faster to write the command and execute it in many situations. With GUI you can only do what is available and with terminal you can write scripts for almost evrything.. you can even automate a lot of things. Also, each GUI system works differently, settings will be in different places like word 2007 was so different from word 2013... with these commands most of the times they are same for all linux systems.
@mom: hmm ... makes sense now... but i think ill leave it for you to use... ;)

Question 2:

List 10 terminal commands and in plain english (i.e. with minimal technical jargon) describe what they do.

1. cd filename: change directory : opens a folder/ directory if found in your current directory. else gives an error saying no such file or directory found.

2. pwd : it will give you the exact path of the current directory/ folder you are in

3. ls: it will list the files in your current directory. Used with certain options, you can see sizes of files, when files were made, and permissions of files. 

4. cp a b: creates a copy of a file a and name it as b

5. mv a b: renames file a as b and mv a ~ will move the file a to the root diectrory

6. rm a: removes or deletes a file a in your directory or will give u an erorr "no such file or directory found" if it is does not exist.

7. mkdir abcd : will create a new folder abcd in your current directory

8. rmdir abcd: this will remove an empty directory abcd if found in current directory. If not found it will return error " no such file or directory" and if found but not empty then it will return error" directory not empty"

9. touch abcd.md: will create a new empty file abcd in the current directory. Also, it can be used with various options to modify various time stamps like access time, modification time etc.

10. ./abcd: to run a file abcd in the current directory. /path_name/abcd: to run file abcd in the following path. It gives a no such file or directory found error if not found. And permission denied error if it is not executable or if you dont have valid perissions

11. echo hello : Prints hello on the command line