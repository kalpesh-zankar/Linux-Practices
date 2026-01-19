
# Linux Environment Setup & Exploration

This repository documents my hands-on practice with Linux environment setup as part of a DevOps learning journey.

## 📁 Repository Structure

1.Install Ubuntu Linux either on VirtualBox, VMware, or via WSL and ensure you can
successfully log in using terminal access.

2.Explore directory structure using commands like
#pwd-present working dir   
#ls-list
#cd-chnage directory

understand root vs home directory.


3.Create directories and files using 
#mkdir
#touch
remove them safely using 
#rm
#rmdir

4.Practice file viewing and editing using 
#cat 
#head 
#less 
#nano 
#vim 

5.Understand file permissions by running 
#ls -l 
modifying permissions using 
#chmod 

Change ownership 
#chown.

6.Learn system monitoring basics with 
#top
#htop
#df -h
#free -m




## 🚀 What I Learned

### 1. **Ubuntu Installation**
-Successfully launched EC2 instance using UBUNTU
- Successfully connected instane on mobaxtrm
- Learned to use terminal for all operations
- 

### 2. **Directory Navigation**
- Mastered essential commands:
                               #pwd
                               #ls
                               #cd
- Understood Linux filesystem hierarchy
- Differentiated between root (/) and home (~) directories
                                                         / -Top-level directory of Linux filesystem
                                                         ~ -Local user home dir 

### 3. **File & Directory Management**
- Created files and directories using
                                  #mkdir
                                  #touch
  
                                                          #mkdir dir1 dir2
                              
                                                          #touch file1.txt
                               
- Removed items safely with
 #rm---------this command remove file

                                                #rm file1.txt
  
 #rmdir-----this command remove empty dir
 
                                           #rmdir dir1
- Practiced recursive operations with  -r flag


### 4. **File Operations**
- Viewed files using this commands
  
                             #cat
                             #less
                             #head
                             #tail
  
- Edited files with
  -           #nano text editor
- Learned basic
-            #vim navigation

### 5. **Permissions & Ownership**
- Understood file permission notation (rwx) read,write,exicute
  
- Modified permissions using
-              #chmod (numeric and symbolic)
-          
- Changed ownership & chnaged group of user with
-                      #chown--chnaged woner of  user
                      #chgrp--chnaged group of user
- Learned about #sudo privileges

### 6. **System Monitoring**
- Monitored processes with
-                     #top 
                     #htop
- Checked disk  with
-                    #df -h
  
  - command is used to check memory (RAM) #free -m 
               total        used        free      shared  buff/cache   available
Mem:            3934         876        1643          21        1414        2801
Swap:           2048           0        2048

- 
- Learned to check system uptime and load average
-                                                        #uptime
-                                                            #output---->  10:45:21 up 15 days  3:12 2 users load average: 0.45  0.30  0.25
-                                                         



