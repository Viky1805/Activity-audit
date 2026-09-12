# Exp_No:4 Activity-Audit

## Name: Vignesh  S

## Reg No: 212224110061

ASSET-ORIENTED RISK ASSESSMENT OF STORAGE ASSETS IN AWS

**Aim**

To identify storage assets in AWS S3, identify possible vulnerabilities and threats, and assess their likelihood, impact, and risk level.

Software / Cloud Services Required
AWS Account
Microsoft Azure Account
Web Browser
Internet Connection
Cloud Services Used
Cloud Platform	Storage Service
AWS	Amazon S3

PART A — AWS S3 STORAGE ASSESSMENT

## Step 1:

Login to AWS
Open the AWS Management Console.
Sign in using your AWS account.
Search for S3.
Select Amazon S3.

## Step 2: 

Select the S3 Bucket
Click Buckets.
Select the S3 bucket created in the previous experiment.
Record:
Bucket name
AWS Region
Number/type of objects
Record
Parameter	Value
Bucket Name	<Enter bucket name>
AWS Region	<Enter region>
Number of Objects	<Enter number>
Object Type	<Enter type>

<img width="1917" height="1091" alt="image" src="https://github.com/user-attachments/assets/d95e7345-8c7b-44f2-8d4c-0c1c83ee6521" />




## Step 3:

Check Block Public Access
Open the S3 bucket.
Select Permissions.
Locate Block public access (bucket settings).
Check Block all public access.
Record
ON → Secure configuration
OFF → Potential public-access risk

<img width="1917" height="1077" alt="image" src="https://github.com/user-attachments/assets/5ef2c2f8-5368-496b-ab59-cf9203164c10" />



## Step 4:

Check Bucket Versioning
Select the Properties tab.
Locate Bucket Versioning.
Record whether it is:
Enabled
Disabled
Security Purpose
Versioning helps recover previous versions of objects after accidental deletion or modification

<img width="1917" height="1077" alt="image" src="https://github.com/user-attachments/assets/a65f5bb3-0243-44c4-8b89-2911aafd4bed" />


## Step 5: 

Check Default Encryption
Stay in the Properties tab.
Locate Default encryption.
Record the encryption type.
Possible Configurations
SSE-S3
SSE-KMS
DSSE-KMS
Security Purpose
Encryption protects stored data from unauthorized disclosure.

<img width="1917" height="1106" alt="image" src="https://github.com/user-attachments/assets/34e642d5-8c8a-4ced-8f34-13218afc6ec3" />



## Step 6: 

Check Bucket Policy
Select Permissions.
Locate Bucket policy.
Check whether a bucket policy exists.
Record
Policy exists
No policy
<img width="1917" height="1106" alt="image" src="https://github.com/user-attachments/assets/2dc960aa-6612-4a1f-a4db-c2097522605a" />


## Step 7: 

Check Object Ownership and ACL
In Permissions, locate Object Ownership.
Record the current configuration.
A common secure configuration is:

Bucket owner enforced
This means:

ACLs are disabled.
Objects are owned by the bucket owner.
Access is controlled using policies.
<img width="1917" height="1085" alt="image" src="https://github.com/user-attachments/assets/b59b1e14-e098-42a6-a825-1de0655c7a2a" />



## Step 8: 

Check Server Access Logging
Go to Properties.
Locate Server access logging.
Record whether it is:
Enabled
Disabled
Security Purpose
Logging helps investigate suspicious or unauthorized access to the bucket.

<img width="1917" height="1091" alt="image" src="https://github.com/user-attachments/assets/fd9e54d2-34d4-493a-a225-ce8968afd367" />


## Result:

All AWS user activities, including volume creation, deletion, and permission changes, were successfully audited using CloudTrail.


