# Jenkins Remoting Using AWS EC2

## Objective

Set up Jenkins Remoting to connect remote Jenkins nodes, distribute build workloads securely, and execute jobs on a remote AWS EC2 agent.

## Tools Used

* Jenkins
* AWS EC2
* Ubuntu Linux
* SSH

## Architecture

* Jenkins Controller (Master) on EC2
* Jenkins Agent on EC2
* SSH-based communication between Controller and Agent

## Steps Performed

1. Created two EC2 instances (Master and Agent).
2. Installed Java and Jenkins on the Master.
3. Generated SSH keys on the Master.
4. Configured SSH access to the Agent.
5. Added the Agent node in Jenkins using SSH credentials.
6. Connected the Agent and verified it was online.
7. Created a test job and executed it remotely.

## Result

Successfully configured Jenkins Remoting on AWS EC2 and
