# Shell Basics

## Learning Objectives

- learning what the terminal and the shell are
- learning to navigate the file system using the shell and the terminal
- learning to create, rename, remove and move files and folders in the filesystem

---

## Shell and Terminal

You are probably used to using GUIs
([Graphical User Interfaces](https://en.wikipedia.org/wiki/Graphical_user_interface)) to interact
with computers.

Often times developers interact with computers using CLIs (Command Line Interfaces) which are text
based user interfaces. That means that you type commands to interact with the computer (create /
move / delete / edit files, install software, change system settings...).

This has the following reasons / advantages:

- Many tools don't have a GUI and can only be used as a CLI.
- You can write scripts (which consist of a number of commands) to automate processes and repetitive
  tasks and ensure they are being run exactly the same way every time they are executed.

On macOS we are using zsh (z shell) as the command interpreter.[^1]

By default it is run within the Terminal app. For this course we'll use iTerm and Visual Studio Code
as alternative terminal emulators.

- A shell (like zsh) is the command interpreter that runs and executes commands on your computer and
  outputs results.
- A terminal (like Terminal, iTerm, Visual Studio Code) is a text input and output environment
  (emulating a [hardware computer terminal](https://en.wikipedia.org/wiki/Computer_terminal)) that
  sends commands to the shell and displays its output.

### Basic Shell commands

| command            | functionality                                                              |
| ------------------ | -------------------------------------------------------------------------- |
| `ls`               | list the content of the current directory                                  |
| `cd <folder name>` | change directory into a folder                                             |
| `cd ..`            | change into the parent folder                                              |
| `cd ~`             | change into your home directory                                            |
| `pwd`              | print the current directory path                                           |
| `touch example.md` | create a file called "example.md"                                          |
| `mkdir newFolder`  | create a folder called "newFolder"                                         |
| `rm <file name>`   | delete a file permanently (there is no trash bin to recover files!)        |
| `open .`           | open the current folder in the finder                                      |
| `cat <file name>`  | prints the content of a specific file                                      |
| `curl <url>`       | prints the received content from the specified url. (try `curl ipinfo.io`) |

> 💡 There are a lot of commands for any sort of action you want to perform check out
> [this cheat cheet](https://github.com/RehanSaeed/Bash-Cheat-Sheet) to look up important commands.

---

## Resources

- [terminal basics](https://mrkaluzny.com/blog/terminal-101-getting-started-with-terminal/)
- [command line cheat sheet](https://github.com/0nn0/terminal-mac-cheatsheet#english-version)

[^1]:
    Before 2019 (v10.15) macOS' shell was called bash. Most bash commands will still work with zsh
    as well. Because it was so widespread, the word bash also became a
    [metonym](https://en.wikipedia.org/wiki/Metonymy) for any shell. Keep that in mind when
    googling.
