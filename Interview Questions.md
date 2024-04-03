# AWS 
```
Storage Classes in S3?
Volume types in EBS?
Instance Type in EC2?
What is Auto Scaling and how do you enable it?
Difference in AMI vs Snapshot?
What is inside AMI?
What is lifecycle policy in S3?
What is S3? Why is a bucket Global?
What is ARN?
Automate Backup?
Unable to connect to EC2 instance, how do you fix it?
Status health checks in EC2?
Share volume with EC2?(Talk about EFS here)
What is EFS? And how to enable EFS with all the steps (Also post number of EFS which is 2049)
NACL vs Security Group?
Load balancers Type?
NLB vs ALB?
Routing in ALB?
Can i attach multiple Target Group to ELB? If yes what is the advantage?
Automated backup?(Talk about automated Snapshot and AMI)
What is a SPOT Request? Any way to persist the data for SPOT Request.
How to save the Public IP? (Talk about Elastic IP)
What is Serverless computing(Talk about Lambda and Fargate)
What is max execution time in Lambda(15 Mins). Can it be increased(No)
Can lambda work inside the network(Talk about VPC and Endpoint)
What languages/Layers are in Lambda?
What is Subnet Group/Parameter Group in RDS? And what is the advantage?
How to connect EC2 with RDS?
How to make RDS for multiple regions?(Cross Region Disaster Recovery)
Port numbers for RDS(All 6 Databases)
What DB you worked on(Say PostgreSQL/Maria/MySQL) And remember the version numbers?
What issues you faced in RDS(Pick up from the github page for any database)
How to ensure 0 Downtime for RDS? (Talk about Read Replica)
What Monitoring did you use?(Say Cloudwatch and Datadog)
What event management you used(Say Eventbridge)
What is VPC/Subnet? How to you give CIDR. They might ask 10.0.0.0/24 has how many addresses? Remember 5 are reserved by AWS
How do you connect to Customer data centre(Say VPN pr Outpost(with Direct Connect) or Transit Gateway with (DC/VPN) as Endpoint)
What is Route 53 and what does it do?
What are Routing policies(Differences are important to remember)
What are the DNS Records(Remember A vs AAAA and NS/SOA/MX/TXT/SRV)
How do you encrypt Data(KMS)
How do you encrypt data in ELB(Talk about ACM Encryption)
What are security mechanism in AWS(Talk about Macie/Inspector/GuardDuty/Security Manager/Firewall/IAM) in that order
How to take action on Security findings(talk about Events and tell your team takes action based on the findings manually)
How to Write policy(They will ask you to share screen so prepared to write a sample policy)
I am unable to access the resource, What can be the reason(Say Policy/Role/Deny Condition/Boundary Condition) in that order
List Some issues in Outpost?
I am unable to connect to EC2 Instance. How do i debug it?
Load Balancer not responding, How to debug it?
Boot Process in Linux?
Adding Machines to Auto Scaling Group?
Cross account Network(Talk about Transit Gateway for Multi Account and tell about Role in IAM)
```
# DevOps
```
Print fizz-buzz in python in range 1-100
Print odd numbers in range 1-100 in python
Print all numbers in range 1-100 in python
Stateful set in k8s?
Advantage of stateful set?
Stateful set vs deployment?
Create a jenkins job to create a file in EC2 and create a file inside the instance
```

```
1. how to know user is root user or sudo user
2. how to create users in linux and how to give sudo permissions to user
3. how to display last 10 commands which we have used in linux
4. difference b/w docker file and docker compose
5. explain about dcoker file
6. explain about docker volumes
7. how to restart stopped container
8. difference b/w VM and docker 
9. why we use ansible and explain about any ansible playbook
10. what is jenkins profiles and how to create
11. how much you know about maven and about maven profiles
12. what is the pipeline stages and explain about build stage
13. one user wants to process only build step how do you give permissions to user to do only build step for particular job
14. explain about IAM and some databases in AWS
15. explain about kubernetes and what is the use and all
16. name space in docker
17. 3 containers are running, one container is consuming all the cpu memory (99%) will it be caused any issue to remaining containers? If yes what is the solution?
18. We are running on one container and that got failed. What is the possible ways to rectify that and what are the steps to take further 
19. How to check whether the particular process is running properly or not? in linux
20. I want to stop particular process using linus commands
21. What are all branches u have used in Jenkins
22. If build fails what are all the steps we should take
23. SED command completely
24. Can we delete content in a file by using SED command
25. How the automatic tests happens in Jenkins
26. Docker build option description
27. We have file called abc.txt in our system, how to check, in which location that file exists using linux command
28. Tell the branch names you have worked in GIT
29. Suppose we have a java.exe file and we have to run as a container, write a docker file and mention all the variables which we need to execute java.exe
30. Day to day activities other than CI/CD
31. Why we use docker containerization


Interview questions..
1. What is docker why we are using docker  difference between vm?
2. What is docker cloud & how it is different from docker hub what is the features over docker hub ?
3. What is docker compose ?
4.How you will link when the docker containers is in different virtual machine is there any configuration in docker compose file are any command or any variable?
5.What you will do if one master got corrupted, can we create multiple masters?
6. What you will do in case any pod deleted?
7.What is namespaces in kubernetes can you tell me some?
8.Can you tell me some commands using in kubernetes ?
9.Tell me the command to create cluster?
10.Difference between rc and rs?
11.What is kubernetes?
12 What is the difference between kubctl & kops?
13 Why you are using kubectl can you explin why we are using ?
14 Why we using kops?
15 What is the difference between docker cloud and docker swarm?
16 How to attach a volume in cluster at some time the container will be deleted then rs will re-create new container then how to attach that container automatically and how to restore the volume automatically to re-created container?
17 How many projects you used  kubernetes?
18 N number of docker containers deployed to different vms how will you manage there is no kubernetes installed?
19  If installed kubernetes how you will deploy this containers into kubernetes cluster?
20 Can you tell me the command for creating kubernetes cluster in vm?
21 How many nodes we required to create kubernetes cluster?
22  We have nearly 15 nodes in my organization all are decentralized so which node I need to create as a master? Is their any possibility to make all the machines as masters?
23 Our applications are decentralized I don’t want distributed environment if any thing happens to the master all will collapse , can we create multiple masters?
24 What is the difference between kubectl and minikube?
25 If any container down in my cluster how you will rectify?
27 How to write a script when the first command is executed then execute the below script?
A)     Java   --version
If [ $? –eq  0 ]
 Then
Echo “print the variable ”
Else
Echo “prin the variable”
fi
28 How to print the exact file name by using command ?
A)  First assign path as a variable 
awk -F '/' '{print $(NF-1)}' <<< "$a"
29 Can you tell me the sintax for forloop and while loop?
30 How to dictionary in python?
A)     Dict={a:10,b:10}
31 How to add another variable c, with key 10 to the above dictionary ?
32 How to replace exesting dictionary?
A)     Dict=[c:10]
33 How to print shell name?
34 How to assign a all the arguments to a single variable?
35 How to print the current processid of current shell?
36 How to know the file that is entering randomly to my script?
37How to divide two variables in shell script?
38 What is trap?
39 What is  shift in shell script?
40 How to run our script in background?
41 How to know the running back ground process id ?
42 What is $*, $$ and $@?
43 How to print only directories?
44 How to print the directory only started with number?
45 How to grep two strings at a time?
46 How to grep a string that is started with some string and ends with some string like a…..b ?
47 How to print string that starts with a?
48 Did you worked on arrays?
49 How will you give access of your script to a particular user?
50 How to access background running scripts and their pid?
51 How to run our script in foreground?
```
