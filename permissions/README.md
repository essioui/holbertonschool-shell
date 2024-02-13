0/-Create a script that switches the current user to the user betty ==> su betty
1/-Write a script that prints the effective username of the current user.==> id -un
2/-Write a script that prints all the groups the current user is part of.==> groups
3/-Write a script that changes the owner of the file hello to the user betty.==> chown user file
4/-Write a script that creates an empty file called hello. ==> touch hello
5/-Write a script that adds execute permission to the owner of the file hello. ==> chmod u+x hello
6/-Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.==> chmod u+x, g+x, o+x
7/-Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello==> chmod ugo+x hello
8/-Write a script that sets the permission to the file hello as follows:

    Owner: no permission at all
    Group: no permission at all
    Other users: all the permissions
===> chmod 007 hello
9/-Write a script that sets the mode of the file hello to this:==> chmod 753 hello
10/-Write a script that sets the mode of the file hello the same as olleh’s mode.==> chmod --reference=olleh hello
11/-Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.==> chmod -R ugo+X .
E
12/-Create a script that creates a directory called my_dir with permissions 751 in the working directory.==> mkdir -m 751 my_dir
13/-Write a script that changes the group owner to school for the file hello==> chown :school hello
