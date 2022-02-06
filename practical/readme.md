# Introduction:
In this section you will put into practice some of the skills we have been developing over the last few weeks. 
</br>
Some of the lessons are obvious such as command line and Linux.
</br>
Some of the lessons are not so obvious such as learning how to find answers, never giving up, teamwork and troubleshooting.
</br>
Read this entire page from top to bottom before beginning. There is a compulsory 10 minute reading time before starting the exam.

### Setup:  
- You will need to be running a distribution of Linux that you are familiar with.   
- Required packages/software  
  - VIM  
  - SSH  
  - GIT  
- You can access the cloud environment from any OpenSSH compatible terminal, whether it is on Windows, Linux or Mac.  
- You will require access to your private SSH key to access the server. If you have lost you private key, you can generate a new one and provide the instructor with the public key which they will place in the server in your user account.  
- You are free to use whatever resources you can find on the internet and are encouraged to take breaks and grab a coffee when you are stuck. Just remember to keep an eye on the time :)  


# The practical:
The test has begun.
Owing to a bug in the exam system, the exam completed prematurely and recorded everyone as having failed.</br>
The test results have been recorded on the Exam Server in the following location /home/admin/results.json
</br>
</br>

**The objective** You have 3 hours to connect to the Exam server via SSH, locate the file and change the result to a Pass.
</br>
![Student Exam Overview](https://github.com/444B/goodluck/blob/Second-Draft/practical/Student%20Exam%20Overview.png?raw=true "Student Exam Overview")
</br>
There are 4 tasks in this exam:  
1. Find your username for the server, in the task userName  
2. Find the IP address of the server, in the task serverIP  
3. Gain writing access to the file, in the task getPermission.  
4. Make the change, completing the practical section of this exam.  


### userName

The userName for the server is in the haystack.txt file. 
</br>
Search the haystack.txt file for your userName.  
There are 393,216 lines of information in this file.   
Each line has an pair of your Initials on the left and encoded information on the right.  
You will have to figure out the relationship between your initials on the left and the encoded information on the right.  
When you decipher the encoding and locate the correct combination, you will see your userName on the same line.  
</br>
### serverIP

The serverIP is in the serverHash.txt file.
</br>
This section requires teamwork. When you are ready to begin this session, signal the Instructor. Once everyone is ready, the instrcutor will announce that you can start talking to each other.
</br>
There are 1,000 servers on this page and one of them is the correct IP for the cloud instance with your results.
The IPs on the left have their corresponding Hash result on the right.
</br>
You will all need to create a string that is 6 characters long, formed from the initials of your group, in capitals and from youngest to oldest. We will call this the groupString.  
</br>
Your task is to figure out, communicate and share the groupString with each other and correctly locate the serverIP together.  
</br>
Generate the Hash of the groupString using any availible tool to locate it in the serverHash.txt file, which will show you the corresponding correct IP.  
You may have to research common types of Hashing functions and use trial and error.  
</br>
Once that is known, you can connect to the server as seen below  
``` shell 
ssh -i /path/to/private_key <userName>@<serverIP>
```

### getPermission  
You have succesully made it into the server.  
You will find in your users home directory a directory called diretoryMaze.  

All you need to do now is to change the results in /home/administrator/results.json  
The file can be read by everyone and only edited by the "administrator" user  
The Permissions are as such  
-rwxr--r--

To edit this file, you will need the password for the "administrator" user  
The password is in a file called "loginCredential.txt" somewhere in directoryMaze  
directoryMaze is a series of 16 folders 0-F (hex counting) where each folder has 16 folders inside and each of those folders has 16 folders inside  
There are a total of 4,368 sub folders here  
You will need a faster way to map out the directories or find the loginCredentials.txt file within the directories  

Once you have read the contents of the loginCredentials.txt file, you should be able to edit your mark and complete the practical  


### Getting stuck:
In the event of being stuck this is the following procedure:  
- read any previous steps and read.me's to make sure you fully understand what the task is.  
- if there is something you dont understand, reread the documentation  
- google and use man pages / tldr  
- if a command fails and returns some error text, google/search it  
- should personal help be requested, you will need to provide adequate evidence of what you have tried so far  


# Good luck!  








