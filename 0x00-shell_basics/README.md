#Shell, basics
Task 0: pwd - prints working directory

Task 1: ls - list directory contents

Task 2: cd - change directory

Task 3: ls -l   - list directory contents in long form

Task 4: ls -la   - list directory contents in long form, including hidden files

Task 5: ls -l -v -a   - list files and directories in an ascending order, including hidden files

Task 6: mkdir /tmp/my_first_directory  - Create a my_first_directory directory inside the tmp directory

Task 7: mv /tmp/betty /tmp/my_first_directory  - Move file betty, which is located inside the tmp directory, to the my_first_directory directory, which is also located inside the tmp directory.

Task 8: rm /tmp/my_first_directory  - Remove file betty from /tmp/my_first_directory.

Task 9: rmdir /tmp/my_first_directory  - Remove directory my_first_directory from /tmp.

Task 10: cd - Change directory to the previous directory you were in.

Task 11: ls -la . .. /boot   - lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

Task 12: file /tmp/iamafile  - Prints the file type for iamafile.

Task 13: ln -s /bin/ls __ls__  - Create a symbolic link named ls for /bin/ls

Task 14: cp -u *.html ..   - copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory. The -u option enables you copy the file into the directory if its a newer version. If the file doesn't exist in the directory, it will copy over.

Task 15: mv [[:upper:]]* /tmp/u   -  Move all files that begin with a capital letter to /tmp/u

Task 16: rm *~   -  Deletes all files in the current directory that end with a ~

Task 17: mkdir -p welcome/to/school   -  Create directory welcome in current directory. The -p option creates any intermediate directories in the path argument.

Task 18: ls -pam   -  List all files and directories of the current directory, separated by commas. Directory names should end with a '/'. The listing should be alph ordered, except for dot (.) or dot dot (..), which should be listed at the beginning. The -a option is to show any hidden files. The -p option writes a / at the end of directory names. The -m option streams the output, separating each listing with commas.

Task 19: 0 string SCHOOL school data !:mime School   -  Create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.
