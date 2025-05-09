# Steps to create an AWS S3 bucket

This guide give you a step-by-step guide to create an AWS S3 bucket in AWS 

## Objective

This guide aims to provide a comprehensive, step-by-step methodology on how to create an S3 bucket in AWS. Amazon S3 (Simple Storage Service) is a scalable object storage service offered by AWS. It allows you to store and retrieve any amount of data, such as documents, images, videos, and backups. S3 is commonly used for static website hosting, data archiving, and secure file storage in the cloud.In this guide you will learn how to create a bucket and upload files into it 

## Prerequisites

- AWS account
- IAM user with permissions to access S3

## Task : Create a S3 bucket

### 1. Log in to AWS Console

- Visit [https://console.aws.amazon.com/](https://console.aws.amazon.com/)
- Sign in with your credentials

<img src="https://github.com/lalith2306/AWS-S3/blob/lalith2306-b1/Images/1.Console-home%20page.png?raw=true" width="950" alt="Log in to AWS console with credentials"/>

### 2. Search and select S3

 - Navigate to the search pane and search for **S3**   
 - Select **Buckets** 
 - Click on **Create bucket** 
### 3. Create Bucket  
Click on the **Create bucket** button.

![Step 3 - Create Bucket](images/3.create-bucket.png)

### 4. Enter Bucket Name  
Provide a **unique bucket name**. The name must be globally unique across all of AWS.

![Step 4 - Bucket Name](images/4.bucket-name.png)

### 5. Block Public Access  
Ensure **Block all public access** is checked for security purposes.

![Step 5 - Block Public Access](images/5.block-public-access.png)

### 6. Enable Bucket Versioning (Optional)  
You can choose to enable **versioning** to keep multiple versions of files.

![Step 6 - Bucket Versioning](images/6.bucket-versioning.png)

### 7. Bucket Successfully Created  
Once all settings are done, scroll down and click **Create bucket**. You’ll see a success message.

![Step 7 - Bucket Created](images/7.successfully-created.png)

### 8. Upload File  
Open your newly created bucket and click **Upload**.

![Step 8 - Upload File](images/8.upload-file.png)

### 9. Add File  
Click **Add files**, then select the file from your local machine.

![Step 9 - Add File](images/9.add-file.png)

### 10. Confirm Upload  
Click **Upload** after adding your file.

![Step 10 - Upload File](images/10.upload-file.png)

### 11. Upload Successful  
Your file will be uploaded and listed in the bucket contents.

![Step 11 - Upload Successful](images/11.upload-successful.png)

## Conclusion

You’ve now successfully created an S3 bucket and uploaded a file to it using the AWS Console. You can repeat the process to manage more files or enable advanced settings like permissions and lifecycle rules.
