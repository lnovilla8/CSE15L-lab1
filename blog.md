# Lab Report 1 - Remote Access and FileSystem
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

## ls

## cat
