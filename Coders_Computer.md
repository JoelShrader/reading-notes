# Coder's Computer

I learned of useful programs for coding and installed them along the way.
- **Windows Terminal**: A [terminal](https://en.wikipedia.org/wiki/Terminal_emulator) designed for a Windows operating system that allows more direct interaction with your computer. It utilizes command-line tools and shells to interact with the operating system
- **Windows Subsystem for Linux 2 (WSL2)**: An application that allows compatibility between Windows and Linux programs, including for coding purposes required for Code 102
- **Ubuntu**: A Linux operating system environment useful for coding inside the Windows Terminal
- **Visual Studio Code**: A code editor for web and cloud applications, used in both building and debugging them
- **GitBash**: An application for Windows that creates an [emulation](https://en.wikipedia.org/wiki/Emulator) layer for testing in different operating system environments
- **Node**: A JavaScript runtime environment, where the code is executed
- **NPM**: A software registry that helps in the sharing and development of programs
- **ESLint**: A static tool for debugging JavaScript code 

## Cheat Sheet
A list of useful commands for the Terminal from a Linux tutorial
- `pwd`: Print Working Directory. Tells you your current working directory
- `ls`: List. A more versatile version of `pwd` that allows refinement of searches
  * `ls -l` displays a list of contents
  * `ls [path]` such as `ls /home` displays a listing of contents of the `/home` directory
  * a `~` is a shortcut for the home directory. For example: `/home/UserName/Documents` and `~/Documents` point to the same location
  * a `.` references your current directory, such as `./Documents`
  * a `..` references the parent directory, so that if we were in the `/Documents` directory `../` would references `/UserName` and `../../` would reference `/home`
- `cd`: Change Directory. Self explanatory. `cd` by itself takes you back to the home directory
  * `cd Documents` would take you right to the Documents directory
  * `cd /` would take you to the root directory
  * `cd ~` would take you to the home directory

## Interesting directories
- `/etc` stores config files for the system
- `/var/log` stores log files for various programs
- `/bin` a location for many common programs for the system
- `/usr/bin` same as above

## Files
Everything is considred a file under Linux, but the extensions can be omitted
- `file`: used to determine the type of file something is, such as a .txt, .png, .exe, etc
- `file [path]`: case sensitive pathway to a specific file such as `file /Documents/File1.txt`
- spaces in names require one of two options:
  * Quotes: similar to a browser search, anything inside quotes is considered a single entity
  * Escape Characters: basically a `\` that 'escapes'/nullifies the following character to 'skip' the space
- Hidden files simply require a `.` at the start of their name. `ls -a` will show hidden files while `ls` will not

# Site Navigation 
- [Home](README.md)
- [Growth Mindset](Growth_Mindset.md)
- [Learning Markdown](Learning_Markdown.md)
- [Coder's Computer](Coders_Computer.md)
- [Revisions and the Cloud](Revisions_and_the_Cloud.md)
- [Structure Web Pages with HTML](Structure_Web_Pages_with_HTML.md)
- [Design Web Pages with CSS](Design_Web_Pages_with_CSS.md)
- [Dynamic Web Pages with JavaScript](Dynamic_Web_Pages_with_JavaScript.md)
- [Programming with JavaScript](Programming_with_JavaScript.md)
