0:  Script switches the current user to the user `betty` . 
    
    su betty
Script that prints the effective username of the current user
	  
    whoami
Script that prints all the groups the current user is part of.
	  
    id -Gn
Script that changes the owner of the file `hello` to the user `betty`
	  
    chown betty hello
	
Script that creates an empty file called `hello`
	  
    touch hello
Script that adds execute permission to the owner of the file `hello`
	  
    chmod u+x hello
Script that adds execute permission to the owner and the group owner, and read permission to other users, to the file `hello`
	  
    chmod 745 hello	 
Script that adds execution permission to the owner, the group owner and the other users, to the file `hello`.
	  
    chmod ugo+x hello
A script that sets the permission to the file `hello` as follows:
      * Owner: no permission at all
      * Group: no permission at all
      * Other users: all the permissions
    
    chmod 008 hello
