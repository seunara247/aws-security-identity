# AWS Security Identity Project 

This project demonstrates the setup and configuraton of AWS IAM (Identity and Access Management) to manage secure access to AWS services.

## Project Overview

The goal of this project is to:

- create IAM users and roles

- Attach appropriate IAM policies

- Restrict or allow access to specific AWS services (e.g S3, EC2)

- Test access to ensure security best practices

## Creating IAM Users, IAM Roles and Attaching Policies

## IAM Users
- using AWS console search for IAM 

- then click on users

- then click on Create user. i named my user *my-iam-asignment*

- then click on your user so it would show more detailes about that user on that page you will see *security credentilals* click on it and look for *Multi-factor Authentication* click on it and it will lead you to where you can choose which way you would like to Authenticate.

- add the user to a group

## Attaching IAM Policies

- on the IAM Dashboard click on policies

- then click on Create policy

- click on the JSON tab (in my case i use JSON)

- Paste your custon policy (in my case i already had a JSON file)

- i named the policy *IAM-Policy*


## IAM Roles

- on the IAM Dashboard click Roles

- then Create roles

- for trusted entity i chose *AWS Service* and for use case i chose *EC2*

- for add permissions policies i chose the policy i previously created then you can create a role after reviewing 

## Conclusion

This IAM Security Identity project demonstrates a practical understanding of managing AWS Identity and Access Management. From creating users and roles to assigning precise permissions and testing access control, each step reflects core principles of cloud security. By implementing IAM best practices, we ensure secure, organized, and auditable access to AWS resources, laying a strong foundation for secure cloud infrastructure.
