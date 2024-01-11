# Lab Report 1 - Remote Access and FileSystem
(Folders & Files Used)

![Image](files.png)
![Image](360_F_217188426_smgwnDFnQC5DHQ8mKGkdsMO7oDDP5nZn.jpg)

## cd 
**Use of cd command with *no* arguments**


**Terminal:**
```
[user@sahara ~/lecture1]$ pwd
/home/lecture1
[user@sahara ~/lecture1]$ cd
[user@sahara ~]$
[user@sahara ~/lecture1]$ pwd
/home
```
**Explanation:**

When using the cd command without arguments, the output returns an empty line. However, the current directory in the command propt is removed and the working directory is changed into /home. This is not an error.

**Use of cd command with a path to a directory as an argument**


**Terminal:**
```
[user@sahara ~]$ pwd
/home
[user@sahara ~]$ cd lecture1
[user@sahara ~/lecture1]$ 
[user@sahara ~/lecture1]$ pwd
/home/lecture1
```
**Explanation:**

When using the cd command with a path to a directory as an argument, the output returns an empty line. However, the current directory in the command propt adds the inputted directory and the working directory is changed into /home/<'argument'>. This is not an error.

**Use of cd command with a path to a file as an argument**


**Terminal:**
```
[user@sahara ~]$ pwd
/home
[user@sahara ~]$ cd Hello.java
bash: cd: Hello.java: No such file or directory
```
**Explanation:**

When using the cd command with a path to a file, it outputs, "bash: cd: Hello.java: No such file or directory". This is an error because the cd command only works with a path to a folder or directory. You cannot change the directory to a file.

## ls
**Use of ls command with *no* arguments**


**Terminal:**
```
[user@sahara ~]$ pwd
/home
[user@sahara ~]$ ls
lecture1
```
**Explanation:**

When using the ls command with no arguements, it prints out a list of the files/folders in the current directory. In the example, the current working directory is /home which contains the folder lecture1. This is not an error.

**Use of ls command with a path to a directory as an argument**


**Terminal:**
```
[user@sahara ~]$ pwd
/home
[user@sahara ~]$ ls lecture1
Hello.class  Hello.java  messages  README
```
**Explanation:**

When using the ls command with a directory as the argument, it lists out the files/folders in that directory. This is not an error.

**Use of ls command with a path to a file as an argument**


**Terminal:**
```
[user@sahara ~]$ pwd
/home
[user@sahara ~]$ ls /home/lecture1/Hello.java
/home/lecture1/Hello.java
```
**Explanation:**

When using the ls command with a path to a file as an argument, it outputs the file path. This is not an error.

## cat
