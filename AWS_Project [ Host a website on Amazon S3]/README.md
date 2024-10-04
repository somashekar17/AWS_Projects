# This README provides essential information for setting up and managing your Hosta website on Amazon S3.

## Prerequisites

Before you begin, ensure you have the following:
- AWS account: A registered AWS account with necessary permissions to create S3 buckets and configure website hosting.
- Website files: Your website's HTML, CSS, JavaScript, and image files.

## Steps

## Create an S3 Bucket:

- Log in to your AWS Management Console. 
- Navigate to the S3 service.  
- Click "Create bucket." 
- Choose a unique bucket name and select the desired region.
- Configure properties as needed (e.g., versioning, encryption).
- Click "Create bucket."

![Task2 -1](https://github.com/user-attachments/assets/101ee633-d92c-4db8-bccd-4ecfdbebf055)


## Upload Website Files:

- Navigate to your newly created bucket.
- Click "Upload" and select your website files.
- Ensure the files are uploaded to the root directory of the bucket.
![2](https://github.com/user-attachments/assets/95cf8aef-a9ba-4046-8277-ae647b86c850)



## Configure Static Website Hosting:

- Click on your bucket name.
- Go to the "Properties" tab.
- Under "Static website hosting," enable it.
- Set the "Index Document" to index.html (or your preferred index file).
- Set the "Error Document" to error.html (or your preferred error page).
![3](https://github.com/user-attachments/assets/2c01f37b-d9bb-4262-b75c-7cb135dd19d6)


- Click "Save changes."



## Access Your Website:

- Copy the bucket URL provided by AWS.
- Paste it into your web browser to access your website.
 ![4](https://github.com/user-attachments/assets/58106bac-9b00-4571-b083-fc1d2afc7664)



- If you encounter an error, navigate to the "Object" section, select the index.html file, and click "Actions." Choose "Make public ACL" to grant public access to the file. This should resolve the issue.




![5](https://github.com/user-attachments/assets/980870bb-5b66-4c0c-9e68-30f2c5edc2bf)
