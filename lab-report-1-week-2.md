# [VScode]
The first step in logging into a course-specific account on ieng6 is to install VScode.
You can find the website for VScode [here](https://code.visualstudio.com/). Since I am on Windows, I downloaded the Windows version from the dropdown menu. Find the appropriate version for your computer and follow the instructions to complete installation. 

# [Remotely Connecting]
The next step in order to remotely connect to the server is to download a program called [OpenSSH](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse) which will allow a connection between the client and server. Once the program is installed, you will need to locate your course-specific account in order to access the server later on. You can find your unique information here(https://sdacs.ucsd.edu/~icc/index.php).

Once all this is done, open a terminal in VSCode and enter in the command: `ssh cs15lwi22zz@ieng6.ucsd.edu` making sure to replace “zz” with your course specific letter from the page above. If it is your first time connecting to the server, you will see a message asking if you would like to continue connecting; type yes, hit enter, and provide your password. When typing your password, your keystrokes will not record visually; this is normal. Once you are logged in, your terminal should look like this:
(screenshot5.png)




