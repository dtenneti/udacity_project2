# udacity_project2

Uploaded all the files for Project 2, Excercise_1 & Excercise_2 zip files contains the terraform code.
The cloudwatch logs, does not show any entries, I get an error that I am missing a group, so I uploaded "lambda_function_execution" screenshot.

**********************************************************************************************************************************************************
1. Good try though..
Kindly add the following to your architecture diagram,

Location of your master and replica databases and the private and public subnets
Name of the Availability Zones you're using. ( include it as a text note within the AZ. eg: us-east-1a).
IP of your subnets
Please check out the below pages for more information,

DT Response: I have marked the architecture diagram with the specific AZ's
The databases and subnets are all located with in the AZ, I am not quite sure what else to specify in the diagram regarding their location besides the AZ info.
Usually we do not specify subnets IP in diagrams in-order not to expose the IP CIDR blocks for the excerise sake, below is the info

for VPC: 172.16.0.0/16
for Public Subnets: 172.16.1.0/24
for Private Subnets: 172.16.2.0/24

2. Great effort. You have included all the services in the architecture. however, you have to include the size of the Dynamo DB and S3 bucket and the region (e.g N.Virginia and Oregon) of your AWS services.

DT Response:The size for Dynamo DB is ~4TB,  S3 bucket size is limitless, not quite sure if we can specify the size, but my estimate is about 12TB

3. added estimates for items below
VPN connection
S3 standard
Data transfer

4. Kindly name your instances in order to meet the rubric requirement.
DT Response: The instruction in the videos doesnt show how to name the instances using Terraform, I did my some reasarch myself and didnt find a way to name the instances, the instances are tagged with the name though, I attached the screenshot "Instance_Name_Tags"  showing that.





