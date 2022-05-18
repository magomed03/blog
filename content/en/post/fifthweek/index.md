---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Fifth week"
subtitle: "A post about the fifth past week"
summary: "A post about the fifth past week"
authors: 
  - admin
  - 吳恩達
tags:
  - Academic
  - 开源
categories:
  - Demo
  - 教程
date: 2022-05-06T17:46:50+03:00
lastmod: 2022-05-06T17:46:50+03:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

## Introduction

Over the past week, I have completed laboratory work No. 11 and No. 12, the topics of which were "Programming in the UNIX OS command processor. Branching and loops" and "Programming in the UNIX OS command processor. Advanced programming".

## Laboratory work No. 12

The purpose of this laboratory was to learn the basics of programming in the UNIX OS shell, to learn how to write more complex command files using logical control structures and loops.

Tasks that I have completed:

1. Write a batch file implementing a simplified semaphore mechanism. The batch file should wait for some time t1
for the resource to be released, giving a message about it, and after waiting for its release, use
it for some time t2<>t1, also giving information that
the resource is being used by the corresponding batch file (process). Run
a batch file in one virtual terminal in the background, redirecting
its output to another (> /dev/tty#, where # is the number of the terminal to which it is redirected
output), in which this file is also running, but not in the background, but in privileged
mode. Modify the program so that there is a possibility of interaction of three
or more processes.
2. Implement the man command using a batch file. Examine the contents of the /usr/share/man/man1 directory. It contains archives of text files containing
help for most of the programs and commands installed in the system. Each archive
can be opened with the less command immediately after viewing the contents of the help. The command
file should receive the command name as a command line argument and as
the result is to issue a help about this command or a message about the absence of help
if the corresponding file is not in the man1 directory.
3. Using the built-in variable $RANDOM, write a batch file that generates a random sequence of letters of the Latin alphabet

## Laboratory work No. 11

The purpose of this laboratory was to learn the basics of programming in the UNIX OS shell, learn how to write more complex command files using logical control structures and loops.

Tasks that I have completed:

1. Using the getopts grep commands, write a command file that analyzes the command line with the keys:
– -iinputfile — read data from the specified file;
– -ooutputfile — output data to the specified file;
– -template — specify the template for the search;
– -C — distinguish between large and small letters;
– -n — output line numbers.
and then searches in the specified file for the necessary strings defined by the -p key.
2. Write a program in C that enters a number and determines whether it is greater than zero, less than zero or equal to zero. Then the program terminates using the exit(n) function, passing information about the termination code to the shell. The batch file should call this program and, after analyzing it with the $? command, give a message about what number was entered.
3. Write a batch file that creates the specified number of files numbered sequentially from 1 to 𝑁 (for example, 1.tmp, 2.tmp, 3.tmp,4.tmp, etc.). The number of files to be created is passed to the command line arguments. The same batch file should be able to delete all files created by it (if they exist).
4. Write a batch file that uses the tar command to archive all files in the specified directory. Modify it so that only those files that were changed less than a week ago are packed (use the find command).

## Conclusion

As a result, I learned how to write more complex command files.