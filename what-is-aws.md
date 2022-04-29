# What is Amazon Web Services ?

Amazon Web Services S3 is a service from Amazon that provides efficient storage facilities to the user’s resources.

## Introduction

The amount of data generated on a daily basis is increasing exponentially. A major part of this data (if not the entire data set) is essential for analysis, understanding users, making important decisions, observing the trends, making predictions, extracting useful insights, designing further applications based on the requirement, and much more. This means most of the data needs to be stored efficiently, in addition to making it easy to retrieve the data, provide relevant security to sensitive/private data, and making sure no other process slows down due to this storage.

This is when Amazon came up with the very idea of **S3** that not just stores data efficiently, but helps in scaling up or down the data, providing high levels of security, and the ability to retrieve any amount of information at any point in time, anywhere from the Internet (data that is publicly available). It can also be used as a backup and data recovery service since data storage is highly durable on AWS S3.

This service, in addition to being compatible with other AWS services, supports third-party solutions too.

### Pre-requisites

It is essential to understand how the AWS S3 service stores data, which makes it so efficient to retrieve and use.

Amazon S3 stores data in the form of **‘objects’**, and these objects are housed inside an entity known as a  **‘bucket’**. 
  - An object refers to the file (that contains data) and some metadata with respect to data inside the file (example- type of data, characters, and bytes). 
  - If a user wishes to store their data in the Amazon S3 bucket, they will first need to upload their data file to a bucket. 
  - After this, the permissions on the file (inside the bucket) can be set, which will decide whether this data can be changed by others or not.

### Steps to use Amazon S3

Following are the steps to use Amazon S3:

  1. If you don’t have an account with AWS, sign up for one.

![image](https://user-images.githubusercontent.com/65863183/165973086-0710273f-5634-400c-90d6-e96274084dba.png)

  2. Follow the steps and create an AWS account.
  3. If you already have an account with AWS, sign in and click on the **‘Get Started with Amazon S3’**.

![image](https://user-images.githubusercontent.com/65863183/165973365-dd7c98a4-f5f4-4640-a441-215aea37ca1f.png)

  4. Create a bucket to store the user’s uploaded file. Once the file is uploaded to the bucket, the charging starts.

![image](https://user-images.githubusercontent.com/65863183/165973574-d9cd7465-fbe9-400b-82f8-2c5d4c68ebec.png)

  5. After creating a bucket and giving a name to it (make sure the name is unique and the region is ‘US West (Oregon), click on the **‘Create’** button and then **‘Create bucket’**.

![image](https://user-images.githubusercontent.com/65863183/165973646-b7c8f56a-8bf3-4ce6-95be-4b0b7de8bced.png)

  6 The **‘configure options’** and **‘set permissions’** have been shown below. In the end, the S3 is reviewed and can be put to use.

![image](https://user-images.githubusercontent.com/65863183/165973807-d5b57113-6d09-4304-9004-755768786711.png)
Amazon Web Services S3

Permissions are shown below:

![image](https://user-images.githubusercontent.com/65863183/165973855-a24c554e-48a4-4e5e-ac74-eaf036ef9d88.png)

  7. The next step is to upload a data file into the created bucket. This data file can be anything ranging from a text file to a video file. The bucket which you would have previously created can be seen on the console. Click on it and then click on the **‘upload’** button.

![image](https://user-images.githubusercontent.com/65863183/165973970-8d4d6969-4e87-43f6-8e18-7de918515d73.png)

  8. Add files to your bucket from your local machine or any other resource and click on **‘Upload’** as in the below screenshot:

![image](https://user-images.githubusercontent.com/65863183/165974082-2f6ef28b-d537-4551-b391-39ff2760bf9b.png)

  9. This uploaded object’s file information can be seen on the console. This can be done by clicking on the bucket you created and checking the **‘Name’** list. It can be downloaded onto your local machine as well. A sample looks like this:

![image](https://user-images.githubusercontent.com/65863183/165974183-4beb8f11-aa51-4f72-bc53-678274cd421b.png)

Now we have seen how to create a bucket, and upload a data file into the bucket, we will understand how an object can be moved from one place to another.

  1. Click on the bucket you created previously.
  2. Click on **‘Create folder’**, give a name to your folder, choose encryption as **‘None’** and click on **‘Save’**.

![image](https://user-images.githubusercontent.com/65863183/165974442-fab37aa7-4bdd-435f-a726-f8ebd5228984.png)

  3. The objects list will now have the folder you created and the file which was uploaded to the S3 bucket. Click on the object which needs to be copied to the newly created folder, click on **‘More’** and click on **‘Copy’**.

![image](https://user-images.githubusercontent.com/65863183/165974587-656b954c-f223-4f9a-8901-114b4621d3ab.png)

  4. Now click on the new folder which was created (it is the destination where the uploaded file needs to be copied to), click on **‘More’->’Paste’**. A **’Copy and paste’** dialog box appears.
  5. Click on **‘Paste’** after the file is uploaded to the folder.

![image](https://user-images.githubusercontent.com/65863183/165974788-5e4c3082-3bf0-42f7-b9e7-64c5086f8c44.png)

After looking at transfer of data file from one bucket to another folder, we will look at how an object can be deleted from a bucket.  

  1. Click on the bucket name which contains the file you wish to delete.
  2. Under the **‘Name’**, click on the check-box of the file you wish to delete.
  3. Click on **‘More’->’Delete’**.

![image](https://user-images.githubusercontent.com/65863183/165974990-9ddf05e2-4c42-42ad-9fff-4eb188b1a6ee.png)

  4. Similar to **‘Paste’** option in the Paste operation, a **‘Delete objects’** dialog box appears. Click on the **‘Delete’** button to delete one of the objects from the S3 bucket:

![image](https://user-images.githubusercontent.com/65863183/165975140-90bc29c1-2d99-4d09-8a91-fa98389fff9b.png)

### Emptying the bucket

If you wish to retain the name of the bucket, but wish to change the contents/objects present in the bucket, the bucket can be emptied.

  1. Click on the bucket icon next to the bucket name you wish to delete.
  2. Now click on the **‘Empty bucket’** option. The **‘Empty bucket’** dialog box will appear.
 
![image](https://user-images.githubusercontent.com/65863183/165975646-d741de04-5ce8-4afd-88e6-eb365968d886.png)

  3. Enter the name of the bucket and click on **‘Confirm’**. This will empty the contents of the bucket, but will retain the bucket (which would be empty).

![image](https://user-images.githubusercontent.com/65863183/165975770-be3ca0a6-4508-49dd-b3c6-6edb9b29085c.png)

### Deleting the entire bucket

If you wish to delete the entire bucket, instead of just emptying the bucket, the below steps could be followed:

  1. Click on the bucket icon next to the bucket name you wish to delete.
  2. Now click on the **‘Delete Bucket’** option. The **‘Delete bucket’** dialog box will appear.

![image](https://user-images.githubusercontent.com/65863183/165976001-be78543f-222c-4753-ac0d-2c9692f80578.png)

  3. Enter the name of the bucket and click on **‘Confirm’**.

![image](https://user-images.githubusercontent.com/65863183/165976091-2f952ccd-c335-4269-b788-b0b5d9f977f4.png)

Some of the salient features of Amazon S3:

  - For the purpose of security, AWS supports 3 encryption forms. AWS has a machine learning service which automatically discovers, arranges and secures data which is present in AWS.
  - AWS helps monitor costs and reduce them.
  - Storage administrators which are present in AWS help provide analysis of the data usage visually.
  - Uploading data to S3 is an easy process. They have multiple ways of transferring required data over the internet. They have direct connections, APIs, AWS Snowball service, and an AWS Storage Gateway.
  - Analysis on large amounts of data can be done without the need of moving it to a different system.
  - AWS works on a global cloud infrastructure, which means it is extremely durable.

The flowchart for the Amazon S3 looks like this:

![image](https://user-images.githubusercontent.com/65863183/165976279-aaedb6aa-35de-4b52-b454-5d6d765cd95c.png)

### Conclusion
In this chapter, we reviewed the importance of AWS S3, and how it has changed the face of storage in the world of computing.
