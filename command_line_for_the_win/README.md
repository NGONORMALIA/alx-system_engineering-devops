to use sftp , that's my process

1- i Use the SFTP command-line tool to establish a connection to the sandbox environment. You will need the hostname, username, and password provided to you for the sandbox environment.

2- i copy all the file required in the local directory using cp command

3- then i use the put command to upload all the file from my local machine to sandbox    e.g: 

put 0-first_9_tasks.jpg /root/alx-system_engineering-devops/command_line_for_the_win
