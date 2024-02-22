# Undestand AWS and some basic concepts.
Here are some of the concepts that I didn't understand about AWS. If you are finding yourself not being able to understand, here are a few things to keep in mind. 

## 1. Creating AWS Instances:

Creating an AWS instance is remarkably straightforward. You simply sign in to your AWS account, navigate to the EC2 dashboard, and proceed to create a new instance. During the creation process, you'll have the opportunity to configure your instance according to your specific requirements. This includes selecting the operating system, specifying the amount of RAM and storage capacity, and defining access points such as SSH or HTTPS.

The intuitive user interface of AWS makes it easy for users of all levels of expertise to spin up new instances with ease. Whether you're a seasoned IT professional or a novice, creating an AWS instance is a hassle-free process that can be completed in just a few clicks.

## 2. Understanding AWS Database Services:

It's essential to recognize that AWS databases are a distinct service within the AWS ecosystem. Rather than installing and managing database software directly on an EC2 instance, AWS provides a dedicated service known as Amazon RDS (Relational Database Service) for database management.

When setting up a database on AWS, users create an RDS instance tailored to their requirements. For example, if you prefer to use MySQL as your database management system, you can create a MySQL RDS instance. Once the instance is created, you'll receive login credentials that allow you to connect to the database from your local machine.

My misconception was that the database resides within the EC2 instance. However, it's important to clarify that the database instance created through RDS operates independently and is not tied to any specific EC2 instance. This distinction is crucial for understanding the architecture of your AWS environment and can save you valuable time and effort in troubleshooting and management.



### Note: I will have my understanding of how to access the EC2 instance from your local machine written here shortly. 
