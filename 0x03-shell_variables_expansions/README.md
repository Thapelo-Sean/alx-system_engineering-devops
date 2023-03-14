0. command alias ls="rm *" create an alias named ls with a value of rm *
1. echo "hello $USER" prints hello user where user is the current linux user.
2. Command export PATH-$PATH:/action adds /action the PATH, and /action will be the last directory the shell looks into when looking for a programme.
3. Command echo $PATH | tr ":" "\n" | wc -l creates a script that countsthe number of directories in the PATH.
4. Command printenv lists environment variables.
5. Command set lists local variables.
6. Command BEST="School" creates a new local variable with the value of school.
7. Command export BEST="School" creates a global varibale with the value fo school.
8. Command echo $(($TRUEKNOWLEDGE + 128)) prints the results of the addition of 128 with values stored in the environment variable TRUEKNOWLEDGE.
9. Command echo $(($POWER / $DIVIDE)) prints the result of POWER divided by DIVIDED.
10. Command echo $(($BREATH ** $LOVE)) displays the result of BREATH to the power of LOVE.
11. Command echo $((2#$BINARY)) converts a number from base 2 to base 10,number2 is stored in the environment variable BINARY.
12. Command echo {a..z}{a..z} | tr ' ' '\n' | grep -v 'oo' prints all possible combinations of two letter, except oo.
13. Command printf "%.2f\n" $NUM prints a number with two decimals places, the number will be stored in the environment variable NUM.
14. Command printf "%x\n" $DECIMAL converts a number from base 10 to base 16, the number 10 will be stored in the environment variable DECIMAL.
15. Command tr 'A-Za-z' 'N-ZA-Mn-za-m' encodes and decodes text using the rot13 encryption. Assume ASCII.
16. Command paste -d, - - | cut -d, -f1 writes a script that prints every other line from the input, starting with the first line.
17. Command printf "%o\n" $(( $((5#$(echo $WATER |tr water 01234))) + $((5#$(echo $STIR | tr string. 01234))) )) | tr 01234567 bestchol adds  the two numbers stored in the environment variables WATER and STIR and prints the result, WATER is in base water, STIR is in base stir,results are in bestchol
