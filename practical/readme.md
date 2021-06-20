# Introducttion:
In this section you will have to put into practice some of the things we have been learning over the last few weeks. 
</br>
Some of the lessons are obvious such as command line and Linux.
</br>
Some of the lessons are not so obvious such as learning how to find answers, never giving up and always learning something new
</br>
Read this entire page from top to bottom before beginning

### Setup:
- You will need to be connected to a Local Area Network that has the Exam Server connected. The Exam Server in this case is a CentOS Server running on 444B's computer via Virtualbox.
- You will need to be running a distribution of Linux that you are familiar with. The following protocols will be used and you may need to be familiar with your distro's package manager if you lack any of the software for specific commands. The commands you may need to download are:
  - Ftp
  - SSH
  - GIT (if you want to copy this repository)
- Any other software or commands should come installed on your computer but feel free to make use of additional resources to get the job done

### Getting stuck:
In the event of being stuck this is the following procedure:
- read any previous steps and documentation to make sure you fully understand
- read any readme.txt that you find
- if there is something you dont understand, reread the documentation
- google and use man pages
- if a command fails and returns some error text, google/search it if it doesnt make sense to you
- should personal help be requested, you will need to provide adequate evidence of what you have tried so far


# The practical:
The test has begun</br>
The test is now over</br>
The test results have been recorded on the Exam Sever under /home/admin/results/ and everyone has failed.
</br>
</br>

**The objective** You will need to connect to the Exam server via SSH as the admin user, login and change the result to a Pass
</br>
The Exam Server has many user accounts on it. Root, admin, and a few classified ones (admin does not mean the same as root)
</br>
You will need to perform the following steps:
1. Find your username for logging in to the Exam Server
2. Find your password
3. Log in
4. Find the admin username and password
5. Log in
6. Pass

#### Finding Username:
The username for each account is somewhere in the haystack.txt file that is in this repository (located in /goodluck/practical/haystack.txt )
Search the haystack.txt file for your Username. It is linked to your first name
</br>
The exact spelling of your first name may be requested if there are any issues with this step
</br>
The result of that search is your username that you will use to SSH into the Exam Server

#### Password:
The password for logging in via ssh is specific to each user. </br>
You can find your password by using the FTP (File Transfer Protocol) to fetch a file from the Exam Server that will instruct you on how to find your password </br>
</br>
Once connected to the ftp server, read the readme and continue with the excercise
The details of the ftp username and password will be given at the time of the exam


#### SSH:
Now that you have your username and password, you may SSH into the Exam Server. </br>
(the IP address is 192.168.0.6) (this will be updated at the time of the practical)</br>
Once in, you will have to create a new file called "artifact" in your current directory before proceeding to find the admin account details</br>
Once you have the admin account details, its a home run to the finish line</br>

Good luck!








