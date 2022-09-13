# The Command Line
### Text Based Interfaces
* Terminal
* Command Line

#### Command Line
  - Presents you with a prompt
  - Command line arguments (-l)
   - Option
      - First command line argument
  - Output
    - Result once you run a command

#### Terminal
  - For MAC 
    - Terminal is under applications and then utilities or comma plus space
    - Within a terminal you have a shell
    - Part of the operating system that defines how the terminal will behave and looks after running commands for you.
    - Most common shell is Bash
        - Bourne Again Shell
        - You can check which shell you are using by using the command ***echo***
  
# Basic Navigation
### PWD
  - Print Working Directory 
    - Present Working Directory
  - List
    - What is in the current location
    - Normal File or Directory
  - ls/etc - List the contents of the directory
    
#### Paths
  - Absolute
    - Specify a location (file or directory) in relation to the root directory. Always begins with a forward slash
  - Relative
    - Specify a location (file or directory) in relation to where we currently are in the system. They will not begin with a slash.
      - Root Directories - single slash
      - Subdirectories come after
  
  - Tilde is a shortcut for your home directory
  - Dot - This is a reference to your current directory
  - dotdot - This is a reference to the parent directory. You can use this several times in a path to keep going up the hierarchy
  
 cd
  - Location
  - If you run this command without any arguments then it will always take you back to your home directory.
      
 Files
   - Everything is a file
   - Linux is an extensionless system - it reads what is inside not what type of file it is
   - .exe is an executable file or program
   - .txt is a plain text file
   - .png, gif, jpg are image files
    
 Escape Characters
   - It is a back slash and it escapes or nullifies the special meaning of the next character.
    
 Hidden Files and Directories
   - The command *ls* will not list hidden files and directories by default.
   - It can be modified by including the command line option -a so that it does show hidden files and directories.
    
