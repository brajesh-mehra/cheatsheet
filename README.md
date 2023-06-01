# cheatsheet
Will Store helpful commands - cheatsheet

# Windows important commands
get all Java process:
jps -m

Kill tasks one by one:
taskkill /F /PID <ProcessID>


# openssl
Create a certificate signing request
openssl req -newKey rsa:4096 -keyout client.key -out client.csr

Generate and sign the server certificate
openssl x509 -req -CA rootCA.crt -CAKey rootCA.key -in client.csr -out

# NGINX 
cd to the location
nginx -s stop	fast shutdown
nginx -s quit	graceful shutdown
nginx -s reload	changing configuration, starting new worker processes with a new configuration, graceful shutdown of old worker processes
nginx -s reopen	re-opening log files

# Gradle Commands
https://docs.gradle.org/current/userguide/command_line_interface.html
Execution a task:
gradle :myTask

Help:
gradle --help

Listing tasks:
gradle tasks

Gradle Clean:
gradle clean


Mfc helpers tasks
-----------------
mfcBuildConnectorsAndReDeployConnectors
mfcCleanAppData
mfcReBuildAllAndReDeployConnectors
mfcRunFarm
mfcRunFarmDebug
mfcRunFarmDebugWithoutWait

------------------------
Java Interview Questions:
1. What is LinkedList? 
2. What is the difference between LinkedList and List?
3. Insertion and deletion operation in LinkedList?
4. Garbage collector start collecting event? 
5. What is heap memory?
6. Different segment of heap?
7. what is volatile keywords?
8. What are modules in spring boot?
	- Spring data JPA
	- ORM
	- JMS
	- AOP
9. How do you lazy load entity in hibernate?
10. How do beans register in spring boot?
11. What are the beans type those get registered in IOC?
12. Programming question - find shortest missing integer from an array
13. Difference between HashTable and HashMap?
14. Where we should not use indexing in database?
15. What is difference between RDBMS and NoSql databases?
16. ps -ef | java
17. 
=================================================
Sorting algo
Data structure 
Fundamental 
Binary Tress 
Big O notation 
Problem Solving
Search for a billion users
OOPs 
SOLID patternrs
Singleton 
Factory 
Builder patters
Auto complete search box for a million users
Angular 
React
Time complexicity
Space complexicity
=================================================


Steps:

1. Run derby server:
cd C:\softwares\db-derby\bin
.\startNetworkServer.bat

2. Run code

ada
apex
ASG
GreenCity
jawahar nehr
sbi ks
silver nine
suditi
