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
Task 12 : Script that prints all possible combinations of two letters, except`oo`.
    * Letters are lower cases, from `a` to `z`
    * One combination per line
    * The output is alpha ordered, starting with `aa`
    * Does not print `oo`
    * Script file contains maximum 64 characters.
      
            echo {a..z}{a..z} | tr ' ' '\n' |grep -v "oo"
Task 13 : Script that prints a number with two decimal places, followed by a new line.
 The number will be stored in the environment variable `NUM`.

      printf '%.2f\n' $NUM
****ADVANCE TASK ***
Task 14 : Script that converts a number from base 10 to base 16.
        * The number in base 10 is stored in the environment variable `DECIMAL`
        * The script should display the number in base 16, followed by a new line
        
            printf "%x\n" $DECIMAL
Task 15 : Script that encodes and decodes text using the rot13 encryption. Assume ASCII.

      tr 'a-zA-Z' 'n-za-mN-ZA-M'
Task 16 : Script that prints every other line from the input, starting with the first line.

      cat -n | grep [13579][[:space:]] | tr -s ' ' | cut -f2
Task 17 : Script that adds the two numbers stored in the environment variables `WATER` and `STIR` and prints the result.
      * `WATER` is in base `water`
      * `STIR` is in base `stir`.
      *  The result should be in base `bestchol`

            printf "%o\n" $((5#`echo $WATER | tr 'water' '01234'` + 5#`echo $STIR | tr 'stir.' '01234'`)) | tr '01234567' 'bestchol'

