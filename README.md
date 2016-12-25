# Unix-Shell

##Description:
A shell has been developed that accepts user commands and executes them in a separate process. The shell interface has been developed in C++ language.

##It has the following features:
```
> The shell interface prompts user to enter a command, which it executes as a separate process. If the command entered by the user is valid, it’s executed otherwise an error message is displayed on the screen and no new process is executed.
> Unless specified, the parent process waits for the child process (the command that has been entered) to execute. If the child process has to be executed as a background process, symbol (&) is to be appended at the end of the command.
> The shell interface provides a history feature which shows the last 5 commands executed whenever the user enters ‘history’ on the shell. The command will on execution will show the last 5 executed commands in sequential order with numbers. Through this feature the user can check or refer to one of his previously executed commands.
> The user can execute the previous commands executed by entering ‘!!’ as an input. The user is allowed to execute the last nth command using ‘!n’ as an input the shell. For example, if the user enters: ‘!6’, the previously executed sixth command is executed.
> The user can exit the shell by executing the command ‘exit’.
> The shell can be compiled on Linux, Unix or Mac OS X system.
> The shell supports error handling in case the user enters an invalid input.
> The user can change PS1 variable using ‘PS1’ variable
> The user can even change the color of the PS1 variable using ‘CLR’ variable
```
