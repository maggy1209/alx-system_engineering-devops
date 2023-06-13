***Shell, init files, variables and expansions***
Task 0 : Script that creates an alias.
        * Name: ls
        * Value: rm *
               
           alias ls="rm *"
Task 1 : Script that prints `hello user`, where user is the current Linux user.

        echo "hello $USER"
Task 2 : Script that added `/action` to the `PATH`.`/action` should be the last directory the shell looks into when looking for a program.

        PATH=$PATH:/action

