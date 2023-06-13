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
Task 8 : Script that prints the result of the addition of 128 with the value stored in the environment variable `TRUEKNOWLEDGE`, followed by a new line

        echo $((128 + $TRUEKNOWLEDGE))
Task 9 :  Script that prints the result of `POWER` divided by `DIVIDE`, followed by a new line.
        * `POWER` and `DIVIDE` are environment variables             

            echo $((POWER/DIVIDE))
Task 10 : Script that displays the result of `BREATH` to the power `LOVE`
    * `BREATH` and `LOVE` are environment variables
    * The script displays the result, followed by a new line
      
            echo $((BREATH**LOVE))
Task 11 : Script that converts a number from base 2 to base 10.
    * The number in base 2 is stored in the environment variable `BINARY`
    * The script should display the number in base 10, followed by a new line
      
           echo $((2#$BINARY))`
