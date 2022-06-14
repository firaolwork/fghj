# Remi Oni and Tolulope Fakunle Shell

![alt text](https://scontent.fbjr1-1.fna.fbcdn.net/v/t39.30808-6/277680605_2113640605469803_8331666446206869536_n.jpg?stp=cp0_dst-jpg_e15_p320x320_q65&_nc_cat=108&ccb=1-7&_nc_sid=85a577&_nc_ohc=BjlfAZA-QYYAX_mdo8-&_nc_ht=scontent.fbjr1-1.fna&oh=00_AT_7AHV_e0WJkE1PAMavebmrwB3cLAQS3E0OcTuhhz766A&oe=62ADA1A5)

### Description

Remi Oni and Tolulope Fakunle Shell is a simple UNIX command interpreter that replicates functionalities of the simple shell (sh). Additional functions are also included. This program was written entirely in C as a milestone project for ALX Africa Software Engineering.

### Installation

Clone this repository into your working directory. For best results, files should be compiled with GCC and the following flags: -Wall -Wextra -Werror -pedantic -std=gnu89

### Usage

After compilation, the resulting program can run stand-alone, either in interactive or non-interactive mode.

#### Interactive Mode

In interactive mode, simply run the program and wait for the prompt to appear. From there, you can type commands freely, exiting with either the "exit" command or ctrl-D.

#### Non-Interactive Mode

In non-interactive mode, echo your desired command and pipe it into the program like this:

```sh
echo "ls" | ./shell
```

In non-interactive mode, the program will exit after finishing your desired command(s).

#### Included Built-Ins

Our shell has support for the following built-in commands:

| Command             | Definition                                                                                |
| ------------------- | ----------------------------------------------------------------------------------------- |
| exit [n]            | Exit the shell, with an optional exit status, n.                                          |
| env                 | Print the environment.                                                                    |
| setenv [var][value] | Set an environment variable and value. If the variable exists, the value will be updated. |
| unsetenv [var]      | Remove an environment variable.                                                           |
| cd [dir]            | Change the directory.                                                                     |
| help [built-in]     | Read documentation for a built-in.                                                        |


### Credits

All code written by [Remi Oni]([https://github.com/Oni-Jremi]) and [Tolulope Fakunle](https://github.com/Tolulope05).
