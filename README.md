# Simple Shell (Markdown in process)

[![Simple Shell Holberton School
Project](https://www.bing.com/images/blob?bcid=Tk1OuGVZDzUBYw "Simple
Shell Holberton School
Project")](https://www.bing.com/images/blob?bcid=Tk1OuGVZDzUBYw
"Simple Shell Holberton School Project")

## DESCRIPTION

This project consists of creating our own version of a simple shell which is capable of interacting directly with the user through commands, we
create a system that is capable of handling a path that is in charge
of detecting if the arguments entered by the user are found and then
executing them, differentiating what type they are, whether they are
built-in commands or not, to go through the forking process. which
immediately handles calls to the execv system, running according to
the process and finally exiting with exit or ^D.

## HOW TO INSTALL & COMPILE ##
To have this repository and its content, you must execute the following on
your terminal:
~~~
$ git clone https://github.com/AlisonQuinter17/simple_shell.git
$ cd simple_shell
$ ls
~~~

And execute the following in your terminal:
~~~
$ gcc -Wall -Werror -Wextra -pedantic *.c -o hsh
$ ./hsh
WORK$ |
~~~

## Description of the files contained. ##

| File  name   | Description   |
| ------------- |:-------------:|
| simple_shell.h | Header file, contains the prototypes of the functions used that can be found in the other files. |
| main_shell.c      | Contains...|
| read_tokenize.c    | Contains... |
| compare_execute.c    | Contains...|
| builtin_functions.c | Contains...|
| auxiliar_functions.c | Contains...|
| control_errors.c | Contains...|
| man_1_simple_shell   | Custom manual for our basic shell.|
| AUTHORS   | Conatains...|

### Note ###
If you want to review the manual of our Simple Shell function you can execute
in your terminal:
~~~
$ man ./man_1_simple_shell
~~~

##### EXAMPLES #####
Here are some examples of how our simple shell works:

- Command
  + Output:

- Command
  + Output:

- Command
  + Output:

- Command
  + Output:

- Command
  + Output:

## Environment ##
* Language: C
* OS: Ubuntu 14.04 LTS
* Compiler: gcc 4.8.4
* Style guidelines: [Betty style](https://github.com/holbertonschool/Betty/wiki)
and
[Betty-doc](https://github.com/holbertonschool/Betty/blob/master/betty-doc.pl)

## Authors

- Valeria Trujillo - vtrujillorodriguez70@gmail.com / https://twitter.com/@valtrurodriguez
- Alison Quintero - alisondanellaquintero@hotmail.com / https://twitter.com/AlisonQuinter17
