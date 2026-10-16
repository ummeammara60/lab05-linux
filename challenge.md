## Question 1
Answer: I am ummeammara60. My home folder is /home/ummeammara60.
Commands: whoami, pwd

## Question 2
Answer: The server name is ubuntu and it runs Ubuntu 26.04.1 LTS.
Commands: hostname, cat /etc/os-release | head -2

## Question 3
Answer: The server has 1.6Gi of RAM and 2.6G of free disk space.
Commands: free -h, df -h /

## Question 4
Answer: Two users can log in with /bin/bash: root and ummeammara60.
Commands: grep bash /etc/passwd

## Question 5
Answer: 240 processes are running right now.
Commands: ps aux | wc -l

## Question 6
Answer: lab5user was created at TIME_CREATED and deleted at TIME_DELETED.
Commands: sudo grep lab5user /var/log/auth.log
