############## Linux Command ##############

1:- Command to Change User Name on Temorary bases in Terminal
    
    Command:- PS1="ROOT#"

![alt text](image.png)

2:- Command to clear screen

    Command:- clear

        Before Clear Command

![alt text](image-1.png)

        After Clear Command

![alt text](image-2.png)

3:- To check the current user
   
    Command:- whoami

![alt text](image-3.png)

4:- To Check the Present Working Directory

    Command:- pwd

![alt text](image-4.png)

5:- To check File in the directory we use

    Command:- ls and ls -la ("ls -;a" is used for listing with file with permission and file size )

![alt text](image-5.png)

6:- To Read the content of File.

    Command:- cat <FileName>

![alt text](image-6.png)

7:- Command for Swithcing to "Root" user.

    Command:- sudo -i

![alt text](image-7.png)    

8:- Command to Change Directory

    Command:- cd <Directory Name>
![alt text](image-8.png)

9:- To crete directory 

    Command:- mkdir <directory-name>

![alt text](image-9.png)

10:- Create File using "Touch" Command

    Command:- touch <file-name>

![alt text](image-10.png)

11:- Copying file from one directory to other
    
    Command:- cp <file-name> <diretory-name>

![alt text](image-11.png)

12:- Moving file from one location to another location

    Command:- mv <file-name> <directory-name>

![alt text](image-12.png)

13:- Connecting to Server with SSH

    Command:- ssh <server_user_name>@IP-Address

![alt text](image-13.png)

![alt text](image-14.png)

14:- Checking hostname

    Command:- hostname

![alt text](image-15.png)

15:- To Check basic information about Operating sytem and hardware

        Command:- uname -a

![alt text](image-16.png)

16:- To check the particular text in a file:-

    Command:- cat <filename> | grep "text-name"  

![alt text](image-17.png)

    Grep Command is a Case-Sensitive Command. To remove case-sensitiveness from text we have to use "-i" paramerter with "grep" command

    Command:- cat <filename> | grep -i "text-name"  

![alt text](image-18.png)

17:- Copy file from main sysem to server via SSH

    Command:- scp <filename> <user-name>@IP-Address:/<directory-name-with-path>

![alt text](image-19.png)

    File after coppied from main system to server

![alt text](image-20.png)

18:- Reading file line by line or page by page when content in file is very huge.

    Command:- less <file-name>

![alt text](image-22.png)

![alt text](image-23.png)

19:- Reading First Few Lines

    Command:- head <file-name>

![alt text](image-24.png)

    Reading First Selected Number of lines like 5 or 10

    Command:- Command:- head -n 5 /etc/passwd

![alt text](image-26.png)

    Reading First Selected Bytes of Data from file.

    Command:- head -c 100 /etc/passwd

![alt text](image-27.png)  

20:- Reading Last Few Lines

    Command:- tail <file-name>

![alt text](image-28.png)

    Reading Last Selected Number of lines like 5 or 10

    Command:- tail -n 5 /etc/passwd

![alt text](image-29.png)

    Reading Last Selected Bytes of Data from file.

    Command:- tail -c 100 /etc/passwd

![alt text](image-30.png)

21:- Checking IP Address details of system

    Command:- ifconfig

![alt text](image-31.png)


