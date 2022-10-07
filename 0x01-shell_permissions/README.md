a script that switches the current user to the user betty, su betty
a script that prints all the groups the current user is part of, groups
a script that changes the owner of the file hello to the user betty, chown betty hello
a script that creates an empty file called hello, touch hello
a script that adds execute permission to the owner of the file hello, chmod u+x hello
a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
a script that adds execution permission to the owner, the group owner and the other users, to the file hello, chmod a+x hello
a script that sets the permission to the file hello as follows, chmod 007 hello
a script that sets the mode of the file hello to this, chmod 753 hello
a script that sets the mode of the file hello the same as olleh’s mode, chmod --reference=olleh hello
a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed, chmod a+X *
a script that creates a directory called my_dir with permissions 751 in the working directory, mkdir -m 751 dir_holberton
a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory, chown vicent:staff *
a script that changes the owner and the group owner of _hello to vincent and staff respectively, chome -h vincent:staff _hello
a script that changes the owner and the group owner of _hello to vincent and staff respectively, chown -h vincent:staff _hello
a script that changes the owner of the file hello to betty only if it is owned by the user guillaume, chown --from=guillaume betty hello
a script that will play the StarWars IV episode in the terminal, telnet towel.blinkenlights.nl
