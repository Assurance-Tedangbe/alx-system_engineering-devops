0x00. Shell, basics

Exercise 0: pwd   prints the absolute path name of the current working directory

Exercise 1: ls  Display the contents list of your current directory.

Exercise 2: cd  changes the working directory to the user’s home directory.

Exercise 3: ls -l  Display current directory contents in a long format

Exercise 4: ls -la   Display current directory contents, including hidden files (starting with .). Use the long format.

Exercise 5: ls -la  Display current directory contents.

Long format with user and group IDs displayed numerically
And hidden files (starting with .)

Exercise 6: mkdir -p /tmp/my_first_directory     Create a directory named my_first_directory in the /tmp/ directory

Exercise 7: mv /tmp/betty  /tmp/my_first_directory    Move the file betty from /tmp/ to /tmp/my_first_directory

Exercise 8: rm /tmp/my_first_directory/betty     Delete the file betty

Exercise 9: rmdir /tmp/my_first_directory        Delete the directory my_first_directory that is in the /tmp directory.

Exercise 10: cd - changes the working directory to the previous one.


Exercise 11: ls -la . .. /boot      List all files/directories, including hidden files/directories, from 3 separate directories: current directory, parent of working directory, and /boot directory. The ls command allows multiple directories to be listed separated by spaces.

Exercise 12: file /tmp/iamafile    Prints the type of file iamafile.

Exercise 13: ln -s /bin/ls  _ls_   Create a symbolic link named _ls_ for /bin/ls

Exercise 14: cp *.html  ..   or   cp -u *.html ..    Copy all html files from the current directory to the parent directory, but only copy files that didn't exist in the parent directory or are newer versions than the ones that already exist in the parent directory. The -u option didn't show on the terminal manual page. The -u option copies the file into the directory if its a newer version. If the file doesn't exist in the directory, it will copy over. The -n option works for copying files that don't exist in the parent directory, but it doesn't check if the file is a newer version or not.

Exercise 15: mv ./[A-Z]* /tmp/u  or  mv [[:upper:]]* /tmp/u     Move all files that begin with a capital letter to /tmp/u

Exercise 16: rm *~ Deletes all files in the current directory that end with a ~

Exercise 17: mkdir -p welcome/to/school   Create directory welcome in current directory. Create directory to inside directory welcome. Create directory holberton inside directory to. The -p option creates any intermediate directories in the path argument.

Exercise 18: ls -pam      List all files and directories of the current directory, separated by commas. Directory names should end with a /. The listing should be alph ordered, except for dot (.) or dot dot (..), which should be listed at the beginning. The -a option is to show any hidden files. The -p option writes a / at the end of directory names. The -m option streams the output, separating each listing with commas.

Exercise 19: 
0 string SCHOOL School data 
!:mime School

Create a magic file called school.mgc that can be used with the command file to detect School data files. School data files always contain "SCHOOL" at offset 0.
