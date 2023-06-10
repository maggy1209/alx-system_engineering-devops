0:  Script switches the current user to the user `betty` . 
    
    su betty
1.Script that prints the effective username of the current user
	  
    whoami
2.Script that prints all the groups the current user is part of.
	  
    id -Gn
3.Script that changes the owner of the file `hello` to the user `betty`
	  
    chown betty hello
	
4.Script that creates an empty file called `hello`
	  
    touch hello
5.Script that adds execute permission to the owner of the file `hello`
	  
    chmod u+x hello
6.Script that adds execute permission to the owner and the group owner, and read permission to other users, to the file `hello`
	  
    chmod 745 hello	 
7.Script that adds execution permission to the owner, the group owner and the other users, to the file `hello`.
	  
    chmod ugo+x hello
8.A script that sets the permission to the file `hello` as follows:
      * Owner: no permission at all
      * Group: no permission at all
      * Other users: all the permissions
    
    chmod 008 hello
9.Script that sets permissions such that the owner has all permissions, group has read     and execute permissions and others have write and execute permissions.
	  
    chmod 753 hello
10.Script that sets the mode of the file `hello` the same as `olleh` ’s mode
	  
    chmod --reference=olleh hello
 11.Script that adds execute permission to all subdirectories of the current directory       for the owner, the group owner and all other users. Regular files are not changed.
    
    chmod -R +X .
12: Script that creates a directory called `my_dir` with permissions 751 in the working     directory.
	  
    mkdir -m 751 my_dir
Script that changes group owner to `school` for the file `hello`
	  
    chgrp school hello
13:Script that changes owner to `vincent` and the group owner to `staff` for all files     and directories in the working directory.
    
    chown vincent:staff *
