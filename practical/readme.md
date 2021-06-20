 asIntroducttion:
In this section you will have to put into practice some of the things we have been learning over the last few weeks. 
Some of the lessons are obvious such as command line and Linux.
Some of the lessons are not so obvious such as learning how to find answers, never giving up and discovering this massive world of computers and cybersecurity

Setup:
- You will need to be connected to a Local Area Network that has the Exam Server connected. The Exam Server in this case is a CentOS Server running on 444B's computer via Virtualbox.
- You will need to be running a distribution of Linux that you are familiar with. The following protocols will be used and you may need to be familiar with your distro's package manager if you lack any of the software for specific commands. The commands you may need to download are:
- - Ftp
- - SSH
- - GIT (if you need it to copy this repository)

Notes:
In the event of being stuck this is the following procedure:
- read any previous steps and documentation to make sure you fully understand
- if there is something you dont understand, reread the documentation
- google and use man pages
- if a command has some error text, google it!
- should personal help be requested, you will need to provide adequate evidence of what you have tried so far


Performing the practical:
The test has begun
The test is now over
The test results have been recorded and everyone has failed.
They exist in a folder on the Exam Server under /home/admin/desktop/results/
You will need to connect to the Exam Server via SSH and find the admin password so that you can log in as the admin user and change your test result
In this case, the Admin user is another user and is not the same as the root user
On the Exam Server, a user account has been created for you under a codename.
In order to connect via SSH, you will need to find your a) username and b) corresponding password

Username:
The username for each account is somewhere in the haystack.txt file that is in this repository (located in /goodluck/practical/haystack.txt )
Search the haystack.txt file for your username. It is linked to your first name
the exact spelling of your first name is listed below
- benyamin
- omri
- dvir
- moshe
the result of that search is your username that you will use to SSH into the Exam Server

Password:
The password to login to the Exam Server is the MD5 hash of a file on the ftp_dir directory of the testuser1 account
You will need to connect to the Exam Server via ftp and get the corresponding file for your username.
You will then need to figure out how to generate the MD5 hash of the file save that, and use as your password for SSH to the Exam Server

SSH:
Now that you have your username and password, you may SSH into the Exam Server. (the IP address is xxx.xxx.xxx.xxx) (this will be updated at the time of the practical)
Once in, you will have to create a new file called "artifact" in your current directory

locate the admin user password in order to access the test results and change your result to a pass

Good luck!








