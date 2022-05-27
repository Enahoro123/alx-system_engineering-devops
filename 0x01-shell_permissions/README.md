Task 0: su betty script that switches the current user to the user  to betty.

Task 1: id -un script that prints the effective username of the current user.

Task 2: id -Gn Prints all the groups the current user is part of.

Task 3: chown betty hello Changes the owner of the file hello to the user betty

Task 4: touch hello Creates hello as an empty file

Task 5: chmod u+x hello Adds execute permission to the owner of the file hello

Task 6: chmod ug+x,o+r hello Adds execute permission to owner and group owner, and read permission to others for file hello

Task 7: chmod ugo+x hello Adds execution permission to all for file hello.

Task 8: chmod 007 hello Sets permissions for file hello so owner and group don't have any permissions and other users have all permissions.

Task 9: chmod 753 hello Set permissions so owner has all permissions, group has read and execute permissions and others have write and execute permissions.

Task 10: chmod --reference=olleh hello Copies the mode of file olleh to file hello.

Task 11: chmod -R +X . Adds execute permission to all subdirectories of the current directory for the owner. Without regular files being changed.

Task 12: mkdir -m 751 dir_holberton Create a directory called my_dir with permissions 751 in the working directory. User has all read, write, and execute permissions. Group has read and execute permissions. Others have just execute permission.

Exercise 13: chgrp school hello Change group owner to school for the file hello

Exercise 14: chown vincent:staff * Changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.

Exercise 15: chown -h vincent:staff _hello Changes the owner and the group owner of _hello to vincent and staff respectively.

Exercise 16: chown --from=guillaume betty hello Changes the owner of the file hello to betty only if it is owned by the user guillaume

Exercise 17: telnet towel.blinkenlights.nl Plays the Star Wars IV episode in the terminal.

Exercise 18: Create a manual that looks as provided.
