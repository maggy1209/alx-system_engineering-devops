***Shell, init files, variables and expansions***
Task 0 : Script that creates an alias.
        * Name: ls
        * Value: rm *
               
           alias ls="rm *"
Task 1 : Script that prints `hello user`, where user is the current Linux user.

        echo "hello $USER"
Task 2 : Script that added `/action` to the `PATH`.`/action` should be the last directory the shell looks into when looking for a program.

        PATH=$PATH:/action
Task 3 : Script that counts the number of directories in the `PATH`

        echo $PATH |tr ':' '\n' | wc -l
Task 4 : Script that lists environment variables.

        printenv
Task 5 : Script that lists all local variables and environment variables, and functions.

        set
Task 6 : Script that creates a new local variable.
        * Name: `BEST`
        * Value: `School`
        
           BEST="School"
Task 7 : Script that creates a new global variable.
        * Name: `BEST`
        * Value: `School`
