# Steps to create an AWS S3 bucket

This guide provides you a step-by-step guide to create an AWS S3 bucket in AWS 

---

## Objective

This guide aims to provide a comprehensive, step-by-step methodology on how to create an S3 bucket in AWS. Amazon S3 (Simple Storage Service) is a scalable object storage service offered by AWS. It allows you to store and retrieve any amount of data, such as documents, images, videos, and backups. S3 is commonly used for static website hosting, data archiving, and secure file storage in the cloud.In this guide you will learn how to create a bucket and upload files into it.

---

## Prerequisites

- AWS account
- IAM user with permissions to access S3

---

## Task : Create a S3 bucket

### 1. Log in to AWS Console

- Visit [https://console.aws.amazon.com/](https://console.aws.amazon.com/)
- Sign in with your credentials

<img src="https://github.com/lalith2306/AWS-S3/blob/lalith2306-b1/Images/1.Console-home%20page.png?raw=true" width="950" alt="Log in to AWS console with credentials"/>


### 2. Search and select S3

 - Navigate to the search pane and search for **S3**   
 - Select **Buckets** 

<img src="https://github.com/lalith2306/AWS-S3/blob/lalith2306-b1/Images/2.Search%20s3%20bucket-p.png?raw=true" width="950" alt="Search for buckets"/>


### 3. Create Bucket  
- Click on the **Create bucket** button to create a new empty bucket

<img src="https://github.com/lalith2306/AWS-S3/blob/lalith2306-b1/Images/3.create%20bucket-p.png?raw=true" width="950" alt="Create a new bucket"/>

### 4. Enter Bucket Name  
- Choose **General Purpose Buckets** 
- Provide a **unique bucket name**
- Ensure that the bucket name must be globally **unique** in AWS.


<img src="https://github.com/lalith2306/AWS-S3/blob/lalith2306-b1/Images/4.%20Bucket-name-p.png?raw=true" width="950" alt="Give a name to the bucket"/>


### 5. Block Public Access  
- Choose **ACLs disabled** as enabling this option will not allow other AWS accounts to access our bucket.
- Ensure **Block all public access** is checked for security purposes.
- This option enabling allows us to keep the bucket private and can't be accessed from anyone else.

<img src="https://github.com/lalith2306/AWS-S3/blob/lalith2306-b1/Images/5.block%20pub%20access-p.png?raw=true" width="950" alt="Block public access"/>


### 6. Enable Bucket Versioning (Optional)  
- You can choose to enable **versioning** to keep multiple versions of files.
- Add **Tags** with key value pair to identify the resource and manage effectively.
- Once all settings are done, scroll down and click **Create bucket**. 

<img src="https://github.com/lalith2306/AWS-S3/blob/lalith2306-b1/Images/6.Tag-p.png?raw=true" width="950" alt="Enable bucket versioning"/>


### 7. Bucket Successfully Created  
- You’ll see a success message on top.

<img src="https://github.com/lalith2306/AWS-S3/blob/lalith2306-b1/Images/7.successfully%20created-p.png?raw=true" width="950" alt="Bucket creation successful"/>


### 8. Upload File  
- Open your newly created bucket and click **Upload**.

<img src="https://github.com/lalith2306/AWS-S3/blob/lalith2306-b1/Images/8.upload_file-p.png?raw=true" width="950" alt="Upload a file"/>


### 9. Add File  
- Click **Add files**, then select the file from your local machine that you want to upload.

<img src="https://github.com/lalith2306/AWS-S3/blob/lalith2306-b1/Images/9.add%20file-p.png?raw=true" width="950" alt="Choose the file to be uploaded"/>


### 10. Confirm Upload  
- Click **Upload** after adding your file.

<img src="https://github.com/lalith2306/AWS-S3/blob/lalith2306-b1/Images/10.upload%20file-p.png?raw=true" width="950" alt="Upload the chosen file to the S3 bucket"/>


### 11. Upload Successful  
- Your file will be uploaded and listed in the bucket contents.
- You’ll see a success message on top

<img src="https://github.com/lalith2306/AWS-S3/blob/lalith2306-b1/Images/11.Successfully%20upload-p.png?raw=true" width="950" alt="File upload successful"/>

---

## AWS S3 Documentation

You can read the official documentation here:  
[Amazon S3 User Guide](https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html)

---

## Video Tutorial

[![Watch the video](https://img.youtube.com/vi/tfU0JEZjcsg/0.jpg)](https://www.youtube.com/watch?v=tfU0JEZjcsg)

---

## Conclusion

You’ve now successfully created an S3 bucket and uploaded a file to it using the AWS Console. You can repeat the process to manage more files or enable advanced settings like permissions and lifecycle rules.
