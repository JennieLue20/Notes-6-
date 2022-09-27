# Notes-6-
Compute 
//overview
You can launch as many or as few virtual servers as you need, set security and networking, and manage storage using Amazon EC2. 
Amazon EC2 allows you to scale up or down in response to variations in demand or surges in popularity, minimizing the need to forecast traffic.
Many services are offered like: 
Amazon EC2 Auto Scaling supports application availability ( automatic launch or terminate EC2 instances )
Amazon Elastic, Amazon ECR store is to retrive docker documents ( docker support ) 
AWS Beanstalk provides a way to run and manage applications
AWS Lamba is a pay as you go ( compute time use ) 
//Reminder ; when selecting a service ;
1. What is your application design? 
2. What are your usage patterns? 
3. Which configuration setting will you want to manage? 
Always start with EC2 instance wizard to help. 
//quote
"Elastic netowrk adapter reaches speed up to 100gb"
The presence of numerous queues simplifies and speeds up the mapping of incoming and outgoing packets
//quote
"Never store AWS credentials on a EC2 instance"
First of all its not secured instead attach to IAM role to the EC2 instance. 

