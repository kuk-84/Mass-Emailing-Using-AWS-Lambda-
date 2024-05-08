AWS,S3,Lambda,IAM,CloudWatch,SES
Gmail has a limit of 2000 mails and 1500 for multi send. 
AWS SES provides us the flexibility to change that limit as per the pay as you go model. Users have complete control over the cost, sending limit. 
SES is a server-less, easy to set up, cost-effective solution to send and receive high-volume emails. 
It eliminates the overhead of building and managing an SMTP server and email infrastructure. SES oversees the complexity of email infrastructure, deliverability, monitoring etc.
It allows sending emails asynchronously, from outside the application within seconds. 
This project aims to send mass emails to business firm’s existing potential customers.
We can verify and add email addresses to the list to which we want to send the email. 
As soon as the file is uploaded on the AWS S3 storage, 
an event of AWS Lambda will be triggered which will send the mails using AWS SES service. 
We will use Python to write the AWS Lambda function.
