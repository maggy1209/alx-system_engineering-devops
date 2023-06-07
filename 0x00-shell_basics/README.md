
0. Script that prints the absolute path name of the current working directory
        
	pwd

1. Display the contents list of your current directory.
        
        ls -l

2. Script that changes the working directory to the user’s home directory.

        cd

3. Current directory contents in a long format.
  
        ls -l

4. Display current directory contents, including hidden files (starting with `.`). Using the long format.
        
        ls -la

5. Display current directory contents.

    *Long format
    *with user and group IDs displayed numerically
    *And hidden files (starting with `.`)
 
        ls -lna

6. Script that creates a directory named `my_first_directory` in the `/tmp/` directory.

        mkdir /tmp/my_first_directory


7. Move the file betty from `/tmp/` to `/tmp/my_first_directory`.
        
        mv /tmp/betty /tmp/my_first_directory

8. Delete the file `betty`
        
        rm /tmp/my_first_directory/betty

9. Delete the directory `my_first_directory` that is in the `/tmp directory`.
       
       rmdir /tmp/my_first_directory

10. Script that changes the working directory to the previous one.

        cd -

11. Script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the `/boot` directory (in this order), in long format.

        ls -al . .. /boot

