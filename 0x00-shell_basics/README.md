
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

12. Script that prints the type of the file named `iamafile`. The file `iamafile` will be in the `/tmp` directory when we will run your script.

        file /tmp/iamafile
13. Script that creates a symbolic link to `/bin/ls`, named `__ls__`. The symbolic link should be created in the current working directory.

        ln -s /bin/ls __ls__

14. Script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory considering the extension `.html`

        cp * .html ..

100. Script that moves all files beginning with an uppercase letter to the directory `/tmp/u`.

          mv [[:upper:]]* /tmp/u

101. Script that deletes all files in the current working directory that end with the character `~`.

          rm *~


