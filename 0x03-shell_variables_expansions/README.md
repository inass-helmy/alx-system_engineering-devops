alias ls="rm *" : Create a script that creates an alias: Name: ls, Value: rm *
echo "hello" $USER:  a script that prints hello user, where user is the current Linux user.
export PATH="$PATH:/action": Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program
echo $PATH | tr -s ":" "\n" | wc -l: Create a script that counts the number of directories in the PATH
printenv: a script that lists environment variables
set: a script that lists all local variables and environment variables, and functions.
