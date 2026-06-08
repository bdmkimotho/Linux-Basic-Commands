# Linux-Basic-Commands
Linux Basic Commands for Data Engineers

# 1 Login to remote Linux server
>ssh <username@serverip>
Example for server with ip 159.65.222.96 and user as root
>ssh root@159.65.222.96

# 2 List directories
>ls 
# 3 List directories showing the long format and data about the files like date,size and owner
>ls -l
 
# 4 Create directories
>mkdir <directoryname>
For example make a directory named bkassignment
>mkdir  bkassignment
 
# 5 Navigate Directories

>cd directoryname
For example to move to bkassignment directory
>cd bkassignment
 
# Files Management
Create files using nano or vim editor

# 6 Create files with nano
>nano filename
For example create  .txt file with the name usingvim
nano usingnano.txt

# 7 Create files with vim
>vim filename
For example create  .txt file with the name usingvim
>vim usingvim.txt
 
# 8 View file contents
>cat filename
For example view file name as usingvim.txt
cat usingvim.txt


# 9 Delete files
>rm filename
For example delete file name usingvim.txt
>rm usingvim.txt

# 10 Delete with confirm before delete(interactive)
>rm -i  filename
For example delete file name usingvim.txt
>rm usingvim.txt
  
# 11 Rename files
>mv  oldfile   newfile
For example rename usingvim.txt to usingvimupdated.txt
>mv usingvim.txt usingvimupdated.txt

# 12 Copy files 
>cp sourcefile destinationfile
For example create a copy of usingvimupdated.txt and name it usingvimcopy.txt
>cp usingvimupdated.txt usingvimcopy.txt

Before
 
After
 


Change from root user to created users
cat  /etc/passwd



