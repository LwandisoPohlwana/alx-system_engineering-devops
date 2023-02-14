0-alias (alias ls="rm *") a script that creates an alias NAME=ls VALUE=rm *

1-hello_you (echo "hello "$USER) a script that prints hello user, where user is the current Linux user

2-path (PATH=$PATH:/action) Adding /action to the PATH. /action should be the last directory the shell looks into when looking for a program

3-paths (echo $PATH | tr ':' '\n' | wc -l) a script that counts the number of directories in the PATH

4-global_variables (printenv) a script that lists environment variables

5-local_variables (set) a script that lists all local variables and environment variables, and functions

6-create_local_variable (BEST="School") a script that creates a new local variable NAME=BEST VALUE=School

7-create_global_variable (export BEST="School")  a script that creates a new global variable NAME=BEST VALUE=School

8-true_knowledge ( echo $((TRUEKNOWLEDGE + 128)) ) a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line

9-divide_and_rule ( echo $((POWER / DIVIDE)) ) a script that prints the result of POWER divided by DIVIDE, followed by a new line

10-love_exponent_breath ( echo $((BREATH ** LOVE)) ) a script that displays the result of BREATH to the power LOVE

11-binary_to_decimal (echo "$((2#$BINARY))") a script that converts a number from base 2 to base 10

12-combinations (echo {a..z}{a..z} | tr " " "\n" | grep -v "oo") a script that prints all possible combinations of two letters, except oo Letters are lower cases, from a to z, One combination per line
The output should be alpha ordered, starting with aa and Do not print oo

13-print_float (printf "%.2f\n" $NUM)  a script that prints a number with two decimal places, The number will be stored in the environment variable NUM followed by a new line
