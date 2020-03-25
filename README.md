# Basic-CMD-Instructions

### What is the command line?

The window, which is usually called the **command line** or **command-line interface**, is a text-based application for viewing, handling, and manipulating files on your computer. It's much like Windows Explorer or Finder on the Mac, but without the graphical interface. Other names for the command line are: cmd, CLI, prompt, console or terminal.

# WINDOWS

#### Open the command-line interface

Depending on your version of Windows and your keyboard, one of the following should open a command window (you may have to experiment a bit, but you don't have to try all of these suggestions):

- Go to the Start menu or screen, and enter "Command Prompt" in the search field.
- Go to Start menu → Windows System → Command Prompt.
- Go to Start menu → All Programs → Accessories → Command Prompt.
- Go to the Start screen, hover your mouse in the lower-left corner of the screen, and click the down arrow that appears (on a touch screen, instead flick up from the bottom of the screen). The Apps page should open. Click on Command Prompt in the Windows System section.
- Hold the special Windows key on your keyboard and press the "X" key. Choose "Command Prompt" from the pop-up menu.
- Hold the Windows key and press the "R" key to get a "Run" window. Type "cmd" in the box, and click the OK key.

### Now these are the basic commands to make you familiar with *Windows* Command Line

1. **whoami**				- tells your username
2. **cd dir_name**		- changes directory and goes to dir_name
3. **cd/**				- goes to the the C: directory
4. **cmd /?**				- prints the help page of cd and others if /? is used after command
5. **dir** 				- List files and directories
6. **mkdir practice** 	- Create directory named practice
7. **cd ..** 				- Go to previous directory
8. **cd** 				- checks location and tells where you are in computer
9. **rmdir practice** 	- deletes file name practice
13. **rmdir /S**    - delete a directory
10. **exit**				- closes the command line
11. **copy**        - copy file (**eg**.copy file_to_be_copied destination)
12. **move**        - move file (**eg**.move file_to_be_moved destination)
13. **cls**         - clears the command line

# LINUX

#### Open the command-line interface

It's probably under Applications → Accessories → Terminal, or Applications → System → Terminal, but that may depend on your system. If it's not there, you can try to Google it. :)


### Now these are the basic commands to make you familiar with *Linux* Command Line

1. **whoami**				- tells your username
2. **pwd**          - print working directory
3. **man pwd**      - prints the help page of pwd and others if man is used before command
4. **ls**           - List files and directories
5. **cd Desktop**   - change directory to Desktop
6. **mkdir practice** 	- Create directory named practice
7. **cd ..** 				- Go to previous directory
8. **rm -r practice**   - Delete directory
9. **exit**				- closes the command line
10. **cp**          - copy file
11. **mv**          - move file
12. **rm**          - delete a file
13. **clear**       - clears the command line 


***PRO tip***: if you type cd D and then hit tab on your keyboard, the command line will automatically fill in the rest of the name so you can navigate faster. If there is more than one folder starting with "D", hit the tab key twice to get a list of options.

***PRO tip***: If you don't want to type the same commands over and over, try pressing the up arrow and down arrow on your keyboard to cycle through recently used commands.

***Attention***: Deleting files using **del**, **rmdir** or **rm** is irrecoverable, meaning the deleted files will be gone forever! So be very careful with this command.

These are just a very few of the commands you can run in your command line.

If you're curious, [ss64.com](ss64.com) contains a complete reference of commands for all operating systems.
