# Processes in Linux

1:- 'top' Command is similar to Task manager in windows. It shows all the running processes

        Command:- top

![alt text](image-60.png)

![alt text](image-61.png)

2:- 'ps aux' It is similar to 'top' Command.

        Command:- ps aux

![alt text](image-62.png)

3:- Just Check What user have open in his system

    Command:- ps aux | <user-name>

![alt text](image-63.png)

    To stop working him from that woking typ below command

    For Root User:- 
        
        Command :- kill <PID>

    For Non-Root User:-

        Command :- sudo kill <PID>

![alt text](image-64.png)

    To Stop forcefull we have to use below command:-
        
        Command:- sudo kill -9 <PID>

![alt text](image-65.png)

    To Stop all the running process by and stopping them by piping:-

        Command:- ps -ef | grep <user-name>| grep -v 'grep'| awk '{print $2}'|sudo xargs kill -9

![alt text](image-66.png)