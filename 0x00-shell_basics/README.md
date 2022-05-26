#Shell, basics
Task 0: pwd - print working directory

TaskTask 1: ls - list directory contents

Task 2: cd - change directory

Task 3: ls -l - list directory contents in long form

Task 4: ls -la - list directory contents in long form, including hidden files

Task 5: ls -la -v  - list files and directories in an ascending order, including hidden files

Task 6: mkdir /tmp/holberton Create a holberton directory inside the tmp directory

Task 7: mv /tmp/betty /tmp/holberton/betty Move file betty, which is located inside the tmp directory, to the holberton directory, which is also located inside the tmp directory. This exercise required some dir traversing.

Task 8: rm /tmp/holberton/betty Remove file betty located in tmp/holberton directory.

Task 9: rmdir /tmp/holberton Remove directory holberton located in directory tmp.

Task 10: cd - Change directory to the previous directory you were in.

Task 11: ls -la . .. /boot List all files/directories, including hidden files/directories, from 3 separate directories: current directory, parent of working directory, and /boot directory. The ls command allows multiple directories to be listed separated by spaces.

Task 12: file /tmp/iamafile Prints the type of file iamafile.

Task 13: ln -s /bin/ls ls Create a symbolic link named ls for /bin/ls

Task 14: cp -u *.html .. Copy all html files from the current directory to the parent directory, but only copy files that didn't exist in the parent directory or are newer versions than the ones that already exist in the parent directory. The -u option didn't show on the terminal manual page. The -u option copies the file into the directory if its a newer version. If the file doesn't exist in the directory, it will copy over. The -n option works for copying files that don't exist in the parent directory, but it doesn't check if the file is a newer version or not.

Task 15: mv [[:upper:]]* /tmp/u Move all files that begin with a capital letter to /tmp/u

Task 16: rm *~ Deletes all files in the current directory that end with a ~

Task 17: mkdir -p welcome/to/holberton Create directory welcome in current directory. Create directory to inside directory welcome. Create directory holberton inside directory to. The -p option creates any intermediate directories in the path argument.

Task 18: ls -pam List all files and directories of the current directory, separated by commas. Directory names should end with a /. The listing should be alph ordered, except for dot (.) or dot dot (..), which should be listed at the beginning. The -a option is to show any hidden files. The -p option writes a / at the end of directory names. The -m option streams the output, separating each listing with commas.

Task 19: 0 string SCHOOL school data !:mime School Create a magic file called school.mgc that can be used with the command file to detect Holberton data files. school data files always contain "SCHOOL" at offset 0.
