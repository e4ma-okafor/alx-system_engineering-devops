Project: command line for the win

CMD CHALLENGE is a pretty cool game challenging you on Bash skills.

STEPS I FOLLOWED TO USE THE SFTP COMMAND-LINE TOOL
1. From the alx intranet Ubuntu 20.04 sandbox, copy the SFTP command by clicking the SFTP button.
2. Paste this command in a terminal or command prompt on your local machine. Press enter key
3. It will give a prompt -
	Are you sure you want to continue connecting (yes/no/[fingerprint])?
4. Type "yes". Press enter key
5. It will prompt for password. 
6. Copy and paste the password from the alx sanbox. Press enter
This will establish a connection between your local machine and the remote sandbox.
7. After it has connected, you will see "sftp>"
8. Type "pwd" to check the current remote working dir
9. Navigate to the directory you want to upload the files to.
10. Use "lpwd" to check the current local working dir
11. Type "lcd" to navigate to the local dir you want to get the files from.
12. Type " lls" to see you have the files you need in the local dir.
13. Type "put <name of file>" to upload the files
14. After uploading the files, type "ls" to confirm that you have uploaded the files to the remote machine
15. Use "bye" command to close the connection.
