# Terminal Cheatsheet

[Back to Syllabus](../README.md)

The following commands will work in Mac and Linux terminals as well as Windows PowerShell.

## Terminal Navigation

| Action                    | Command                       |
| ------------------------- | ----------------------------- |
| Display current directory | `pwd`                         |
| Show directory contents   | `ls`                          |
| Change directory          | `cd <directory_name>`         |
| Go up a directory         | `cd ..`                       |
| Create a directory        | `mkdir <directory_name>`      |
| Delete a directory        | `rm -r <directory_name>`      |
| Move a file or folder     | `mv <filename> <destination>` |
| Create a new file         | `touch <filename>`            |
| Cancel current operation  | `ctrl + C` / `Command + C`    |

## Python in the Terminal

Each operating system has a different shortcut for executing Python's `.py` files in the terminal.

| Command                 | Mac      | Linux    | Windows  |
| ----------------------- | -------- | -------- | -------- |
| `py <filename>.py`      | &#10007; | &#10007; | &#10003; |
| `python3 <filename>.py` | &#10003; | &#10003; | &#10007; |
| `python <filename>.py` | &#10007; | &#10003; | &#10007; |

Things to note:
- You can set your "Python" command to always be "Python 3".
- When `py` or `python` commands are ran without the `filename`, the **Python** **_interpreter_** will run in the terminal.
- To run a file, you need to navigate to the folder containing that file.

[Back to Syllabus](/README.md)