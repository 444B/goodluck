# Introducttion:
In this section you will put into practice some of the skills we have been developing over the last few weeks. 
</br>
Some of the lessons are obvious such as command line and Linux.
</br>
Some of the lessons are not so obvious such as learning how to find answers, never giving up and always learning something new.
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
The test has begun.</br>
The test is now over.</br>
The test results have been recorded on the Exam Server and everyone has failed.
</br>
</br>

**The objective** You have 3 hours to connect to the Exam server via SSH, locate the file and change the result to a Pass.

There are 4 tasks in this exam:
1. Find your username for the server, in the task userName
2. Find the IP address of the server, in the task serverIP
3. Find the location of the file in the server, in the task fileLocation.
4. Gain writing access to the file, in the task getPermission.
5. Make the change, completing the practical section of this exam.

### userName
The userName for the server is in the haystack.txt file. 

Search the haystack.txt file for your userName.
There are 393,216 lines of information in this file. 
Each line has an pair of Initials and encoded information on the right.
You will have to figure out the relationship between your initials on the left and the encoded information on the right.
When you decipher the encoding and locate the correct combination, you will see your userName.

### serverIP
The serverIP is in the serverHash.txt file.

This section requires teamwork.

There are 1,000 servers on this page and one of them is the correct IP for the cloud instance with your results, which you need to change. 
The IPs on the left have their corresponding Hash result on the right.

You will need to create a string that is 6 characters long, formed from the initials of your group, in capitals and from youngest to oldest. We will call this the groupString.

Without speaking, figure out, communicate and share the groupString with each other.

Generate the Hash of the groupString using any availible tool to locate it in the serverHash.txt file, which will show you the corresponding correct IP.
You may have to research common types of Hashes functions.

Once that is known, you can connect to the server as seen below
``` shell
ssh -i /path/to/private_key <userName>@<serverIP>
```
### fileLocation


### getPermission


### Getting stuck:
In the event of being stuck this is the following procedure:
- read any previous steps and read.me's to make sure you fully understand what the task is.
- if there is something you dont understand, reread the documentation
- google and use man pages
- if a command fails and returns some error text, google/search it
- should personal help be requested, you will need to provide adequate evidence of what you have tried so far




Good luck!








