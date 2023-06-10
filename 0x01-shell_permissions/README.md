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
	  
    chmod 1250 hello	 
