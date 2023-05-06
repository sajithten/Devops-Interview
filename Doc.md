# Devops-Interview
# Linux system administration

What are the first 3 steps you would take to debug a high memory utilization problem on a Linux server?

# Scripting

Write a bash script to calculate the frequency of each word in a text file input.txt.

For simplicity sake, you may assume:

input.txt contains only lowercase characters and space ' ' characters.

Each word must consist of lowercase characters only.

Words are separated by one or more whitespace characters.

Example:

Assume that input.txt has the following content:

the day is sunny the the the sunny is is
Your script should output the following, sorted by descending frequency:

the 4
is 3
sunny 2
day 1
Note:

Don't worry about handling ties, it is guaranteed that each word's frequency count is unique.

Could you write it in one-line using Unix pipes?

# Cloud operations

You’re working with a client that has users in Australia who upload large multimedia files (1-10GB) via their browser. The files are required to be stored in S3 US East-1 for regulatory purposes. These files are later processed by a job that runs on an EC2 instance. The EC2 instance pulls a local copy of the original file, performs various manipulations locally against the file, and then transfers the resulting file back to S3 on US East-1.

The problem is that users are finding their files take too long to be uploaded and complete the processing step. The backend team has investigated the issue, and diagnosed that the file transfer steps (browser to S3, S3 to EC2, and EC2 to S3) are taking the most time.

The backend team has asked you for recommendations on how to improve this network communication to maximize transfer speed, transfer cost, and keep the network traffic private between EC2 and S3.

# Architecture

You're working on a system that consists of two VPCs within 2 different AWS accounts, where each VPC has multiple services running inside it. You have one EC2 instance in the first VPC that needs access to an RDS instance in the second VPC while keeping the communication private.


When you tried turning on VPC peering, you were able to establish the connection, but this resulted in exposing all the services in both VPCs to each other, which is not desirable.

What alternative method would you use to only allow the EC2 and RDS instance to communicate with one another, without exposing all the other services within these two VPCs to each other?

# CI/CD

You’re working on a squad that practices strict Test-Driven Development (TDD). All the GitHub repos are set up to require a passing test suite as a CI step before the developer is allowed to merge their code.

Due to growth in the size of the test suite (~ 2000 test cases), some of the developers have started complaining that the CI step to run the tests is taking too long (~ 30 minutes per run) and is slowing down their development process.

You considered vertically scaling the instances that run the CI pipeline, but due to budget constraints the company did not approve the additional spend for more powerful runners.

What other options would you consider to optimize the run time of the test suite in the CI step?

# Security

You are managing an application running on EC2 that requires access to some other AWS services. Accessing these services typically requires the EC2 instance to have access keys and secrets, however the security team does not permit hard coding or storing any security credentials on the EC2 instance.

Based on the above, how would you permission the EC2 instance to access these other AWS services?
