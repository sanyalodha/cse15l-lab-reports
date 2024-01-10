# LAB REPORT 1: SANIYA LODHA
***
## Command: cd
# 1. *cd with no arguments*

![Screenshot](cd_1.png)

2. The working directory when running code "cd" was the home directory
3. I got no output because there were no arguments after cd so it did not change any directory and was in the same one with which we started which was home.
4. The output is not an error.

# 2. *cd with a path to a directory as an argument*
![Screenshot](cd_2.png)

2. The working directory when the command was run was the home directory
3. By using the command "cd lecture1/messages", we changed the working directory from the home directory to the messages directory
4. There was no error

# 3. *cd with a path to a file as an argument*
![Screenshot](cd_3.png)

2. The working directory was messages
3. After running "cd en-us.txt", it resulted in an error output because the file is not a directory.
4. There is an error because cd changes directories and en-us.txt is a file and not a directory.

## Command: ls
# 1. *ls with no arguments*
![Screenshot](ls_1.png)

2. Working directory was the home directory
3. I got the output lecture1 because ls shows all files in the current directory which would be only lecture1 in the home directory.
4. No errors.

# 2. *ls with a path to a directory as an argument*
![Screenshot](ls_2.png)
2. Working directory was the home directory
3. By adding a path to a directory as an argument, ls accessed the lecture1 directory and found the 4 files: Hello.class, Hello.java, messages and README which it displayed as an output.
4. We got no errors

# 3. *ls with a path to a file as an argument*
![Screenshot](ls_3.png)
2. Working directory was the home directory
3. By adding a path to the file, we get the same argument of the path back because ls found no further files inside gd.txt
4. We got no errors

## Command: cat
# 1. *cat with no arguments*
![Screenshot](cat_1.png)
2. Working directory is the home directory
3. The output changes the indent and this basically means that cat is accepting standard input which is any text you type from now onwards will be repeated as an output. So cat with no arguments enters into standard input mode.
4. No errors

# 2. *cat with a path to a directory as an argument*
![Screenshot](cat_2.png)
2. Working directory is the home directory
3. We get the output that lecture1 is a directory because cat as a command only works with directories and it is used to show the contents of a file not directories.
4. This is an error because cat does not work with directories.

# 2. *cat with a path to a file as an argument*
![Screenshot](cat_3.png)
2. Working directory is the home directory
3. When using a file as an argument like Hello.java, cat printed out the contents of Hello.java because cat is usually used to display the contents of a file
4. There is no error


