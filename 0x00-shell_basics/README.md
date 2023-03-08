pwd : prints the absolute path name of the current working directory
ls: Display the contents list of your current directory
cd ~ :  a script that changes the working directory to the user’s home directory
ls -l : Display current directory contents in a long format
ls -la : Display current directory contents, including hidden files (starting with .)
ls -na: Display current directory contents in Long format, with user and group IDs displayed numerically, And hidden files (starting with .)
mkdir /tmp/my_first_directory: Create a script that creates a directory named my_first_directory in the /tmp/ directory
mv /tmp/betty /tmp/my_first_directory : Move the file betty from /tmp/ to /tmp/my_first_directory
rm /tmp/my_first_directory/betty: Delete the file betty is in /tmp/my_first_directory
rm -r /tmp/my_first_directory: delete the folder my_first_directory from /temp
cd - : a script that changes the working directory to the previous one
ls -la .  .. /boot: a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long forma
file /tmp/iamafile: a script that prints the type of the file named iamafile
ln -s /bin/ls ./__ls__: Create a symbolic link to /bin/ls, named __ls__
cp -u ./*.html ../: Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
mv ./[A-Z]* /tmp/u/: Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u
