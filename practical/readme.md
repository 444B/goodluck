Introducttion:
In this section you will have to put into practice some of the things we have been learning over the last few weeks. 
Some of the lessons are obvious such as command line and Linux.
Some of the lessons are not so obvious such as learning how to find answers, never giving up and discovering this massive world of computers and cybersecurity

Setup:
- You will need to be connected to a Local Area Network that has the Target machine connected. The Target machine in this case is a CentOS Server running on 444B's computer via Virtualbox.
- You will need to be running a distribution of Linux that you are familiar with. The following protocols will be used and you may need to be familiar with your distro's package manager if you lack any of the software for specific commands. The commands you may need to download are:
- - Ftp
- - SSH
- - GIT (if you need it to copy this repository)


Performing the practical:
The test has begun
The test is now over
The test results have been published and everyone has failed.
They exist in a folder on the target machine under /home/admin/desktop/results.txt
You will need to connect to the Target Machine via SSH and become the Sudo user so that you can change your test result
On the Target machine, a user account has been created for you.
In order to connect via SSH, you will need to find that username and the corresponding password

Username:
The username for each account is somewhere in the haystack.txt file that is in this repository (located in /goodluck/practical/haystack.txt )
Search the haystack.txt file for your username. It is linked to your first name
the exact spelling of your first name is listed below
- benyamin
- omri
- dvir
- moshe

Password:
The password to login to the target machine is the MD5 hash of a file on the ftp_dir directory of the testuser1 account
You will need to connect to the target machine via ftp and get the corresponding file for your username.
You will then need to figure out how to generate the MD5 hash of the file save that, and use as your password for SSH to the target machine

SSH:
Now that you have your username and password, you may SSH into the target machine. (the IP address is xxx.xxx.xxx.xxx) (this will be updated at the time of the practical)
Once in, you will have to locate the admin user password in order to access the test results and change your result to a pass

Good luck!








