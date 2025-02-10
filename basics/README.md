./0-current_working_directory = pwd = prints the absolute path name of the current working directory.

./1-listit = ls = Display the contents list of your current directory.

./2-bring_me_home = cd ~ = changes the working directory to the user’s home directory.

./3-listfiles = ls -l = Display current directory contents in a long format

./4-listmorefiles = ls -la = Display current directory contents, including hidden files (starting with .). Use the long format.

./5-listfilesdigitonly = ls -la --numeric-uid-gid = Display current directory contents, long format, with user and group IDs displayed numerically, and hidden files (starting with .)

./6-firstdirectory = mkdir /tmp/my_first_directory = creates a directory named my_first_directory in the /tmp/ directory.

./7-movethatfile = mv /tmp/betty  /tmp/my_first_directory = Move the file betty from /tmp/ to /tmp/my_first_directory.

./8-firstdelete = rm /tmp/my_first_directory/betty = Delete the file betty.

./9-firstdirdeletion = rm -r /tmp/my_first_directory = Delete the directory my_first_directory that is in the /tmp directory.

./10-back = cd - = script that changes the working directory to the previous one.

./11-lists = ls -la . .. /boot = a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

./12-file_type = file /tmp/iamafile =  a script that prints the type of the file named iamafile.

./13-symbolic_link = ln -s /bin/ls __ls__ = Create a symbolic link to /bin/ls, named __ls__.

./14-copy_html = cp -u *.html .. = a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

./15-lets_move = mv [A-Z]* /tmp/u = a script that moves all files beginning with an uppercase letter to the directory /tmp/u.


