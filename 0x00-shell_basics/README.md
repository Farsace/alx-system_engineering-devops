pwd = prints the absolute path name of the current working directory.

ls = Display the contents list of your current directory.

cd = changes the working directory to the user’s home directory.

ls -l = Display current directory contents in a long format

ls -la = Display current directory contents, including hidden files (starting with .). Use the long format.

ls -la -n = Display current directory contents.
               Long format
               with user and group IDs displayed numerically
               And hidden files (starting with .)

mkdir /tmp/my-first-directory = Create a script that creates a directory named my-first-directory in the /tmp/ directory.

mv /tmp/betty /tmp/my-first-directory = Move the file betty from /tmp/ to /tmp/my-first-directory.
rm /tmp/my-first-directory/betty = Delete the file betty from the /tmp/my-first-directory

rm -r /tmp/my-first-directory = Delete the my-first-directory from the /tmp directory

cd - = changes the working directory to the previous one.

ls -la . .. /boot = lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

file /tmp/iamafile = prints the type of the file named iamafile which is inside the /tmp directory.

ln -s /bin/ls __ls__ = Create a symbolic link to /bin/ls, named __ls__ inside the working directory

cp -un *.html ../ = Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.


