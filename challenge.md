# Challenge: Security Detective

## Question 1
Answer: I am mominaasim-dev. My home folder is /home/mominaasim-dev.
Commands: whoami, pwd

## Question 2
Answer: The server name is ubuntu and it runs Ubuntu 26.04.1 LTS.
Commands: hostname, cat /etc/os-release

## Question 3
Answer: The server has 1.6Gi RAM and 12G of disk space is free.
Commands: free -h, df -h /

## Question 4
Answer: mominaasim-dev and lab5user can log in with /bin/bash.
Commands: grep bash /etc/passwd

## Question 5
Answer: About 250 processes are running.
Commands: ps aux | wc -l

## Question 6
Answer: lab5user was created at 10:45:45 and deleted at 10:49:07.
Commands: sudo grep lab5user /var/log/auth.log
