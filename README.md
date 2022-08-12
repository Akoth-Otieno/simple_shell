# The Unix Simple Shell Project
### Task: To write a simple Unix command line interpreter.
[![unix.png](https://i.postimg.cc/jjYs4Kmt/unix.png)](https://postimg.cc/RWG5MrvD)
## The Shell
A Unix shell is a command-line interpreter or shell that provides a command line user interface for Unix-like operating systems. The shell is both an interactive command language and a scripting language, and is used by the operating system to control the execution of the system using shell scripts.
In essence, a shell is a program that takes user commands from the command line via the terminal, and gives them to the operating system to execute.
## About This Project
* This project is a simple version of the linux shell, as part of the requirements of the ALX Africa software engineering program's low level programming.
* The predominant programming Language used is **C**. 
* The simple shell should have the basic functionality of a normal shell.
## Functionality of the Simple Shell:
* Displays a prompt and waits for user input.
* Runs all commands of type "executable program".
* Runs the built_in commands **exit**, **env**, **setenv** and **unsetenv**.
* Handles commands with arguments.
* Handles the PATH global variable.
* Handles the EOF (End Of File) condition.
* Handles the Ctrl + C signal, meaning it terminates a process without exiting the shell.
## Project Requirements.
### List of allowed functions and system calls for this project
* <span style="color: red"> access </span> (man 2 access)
* <span style="color: red"> chdir </span> (man 2 chdir)
* <span style="color: red"> close </span> (man 2 close)
* <span style="color: red"> closedir </span> (man 3 closedir)
* <span style="color: red"> execve </span> (man 2 execve)
* <span style="color: red"> exit </span> (man 3 exit)
* <span style="color: red"> fflush </span> (man 3 fflush)
* <span style="color: red"> fork </span> (man 2 fork)
* <span style="color: red"> free </span> (man 3 free)
* <span style="color: red"> getcwd </span> (man 3 getcwd)
* <span style="color: red"> getline </span> (man 3 getline)
* <span style="color: red"> isatty </span> (man 3 isatty)
* <span style="color: red"> kill </span> (man 2 kill)
* <span style="color: red"> malloc </span> (man 3 malloc)
* open (man 2 open)
* opendir (man 3 opendir)
* perror (man 3 perror)
* read (man 2 read)
* readdir (man 3 readdir)
* signal (man 2 signal)
* stat (__xstat) (man 2 stat)
* lstat (__lxstat) (man 2 lstat)
* fstat (__fxstat) (man 2 fstat)
* strtok (man 3 strtok)
* wait (man 2 wait)
* waitpid (man 2 waitpid)
* wait3 (man 2 wait3)
* wait4 (man 2 wait4)
* write (man 2 write)
# USAGE
## Prerequisites
To use our simple shell, ensure you have installed:
* git.
* Ubuntu 20.04 LTS/ any linux distribution.
* gcc 7.3 or below

**Step 1** : Clone this repository
<copy-button>
    git clone https://github.com/Akoth-Otieno/simple_shell
<copy-button>

**Step 2** : Make sure you are in the directory containing the simple shell.
    cd simple_shell

**Step 3** : Compile all the c files in the directory as follows:
    gcc -Wall -Werror -Wextra -pedantic *.c -o hsh

**Step4** : Run the shell
    ./hsh




