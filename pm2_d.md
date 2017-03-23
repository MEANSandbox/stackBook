# [PM2](https://github.com/Unitech/pm2) (for nodejs) 

1. production **process manager** for nodejs Application
2. Build-in **Load Balancer**
3. keep Application **alive** forever 

#### Key Terms

1. process
2. application
3. spawning 
   1. a function that **loads and execute** a new child process
   2. the current process may wait for the child to terminate 
   3. or may continue to execute asynchronously
   4. creating new sub process requires enough memory in which both the child and process and the current program can execute
4. daemon
   1. a computer program that runs as a background process rather than being under the direct control of and interractive user
   2. traditionally the process names of a daemon end with the letter d for clarification that the process is infact a daemon
   3. in UNIX environment, ofter the parent process of a daemon is **init** process
   4. a daemon is usually either created by a process forking a child process and then immediatly exiting, thus causing init to adopt the 
   child process 
   5. or by init process directly launching the daemon 
   5. in addition a daemon launched by forking and exiting typically must perform other operations, such as dissociating the process from 
   any controlling terminal(tty) 
   


child process api or cluster api
** fork mode vs cluster mode**
running multiple server on a single port which will then be load-balanced by HAProxy or Nginx.
why do i need to install pm2 globally
in point 3.4 will OS ocupy the memry for master ever if we terminate master after creating a child 
