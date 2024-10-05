# Robust Cloud Security with AWS IAM

## ⚡️This README offers a guide to implementing robust cloud security with **AWS Identity and Access Management (IAM)**, controlling access to AWS resources for authorized users and applications.

## Prerequisites

- **AWS Account**: A registered AWS account with necessary permissions to manage IAM resources.
- **Basic AWS Knowledge**: Familiarity with core AWS services and concepts.

## Steps to Enhance Cloud Security

### 1. Create an EC2 instances 💻 

- **Log in to AWS Management Console**: Access your account and navigate to the EC2 service.
- **Launch Instance**: Click on Launch Instance.
- **Select AMI**: Choose a unique instance name and select a desired AMI (e.g., Ubuntu, Amazon Linux) that is Free Tier eligible.
- **Choose Instance Type**: Select an instance type that qualifies for the Free Tier.
- **Configure Key Pair**: Select the Default key pair for login.
- **Finalize Launch**: Click Launch Instance to create your EC2 instance.

  
![Task3 0](https://github.com/user-attachments/assets/fddea2d9-835a-40e0-b030-903b5167a7d7)



### 2. Create IAM Policies 📏 and AWS Account Alias  🔖
- **Access IAM Policies**: Search for IAM, click on Policies, then select Create Policy and switch to the JSON tab.
- **Paste JSON Data**: Paste your policy JSON data into the editor and click Next.
- **Add Policy Details**: Enter a unique policy name and description.
- **Add Tags**: Scroll down to Additional Tags, add Production and Development tags, and click Save.
  
  ![Task3 1](https://github.com/user-attachments/assets/3e2bd9f3-0fe2-4870-ac1f-d7f553ccbd35)

  
- **Access AWS Account Alias**: In the IAM Dashboard, locate the AWS Account card on the right-hand side and select the Account Alias.
- **Set Account Alias**: Enter your project name or any preferred name, which will provide a URL for new users to access the site.

  ![Task3 2](https://github.com/user-attachments/assets/0f8b7de2-ce1c-4f12-a664-c0c3df6b6156)


### 3. Create IAM Users and User Groups 👩‍👩‍👧‍👧
- Search for IAM and click on User Groups, then select Create Group and enter a unique name without special characters.
- Go back to the IAM Dashboard and click on Users, then select Create User.
- Enter a unique username with the department identifier and check the box for AWS Management Console access.
- Choose Auto-generate password and uncheck User must create a new password, then click Next.
- Attach policies directly by searching for and selecting the newly created policy, then click Next.
- Click Create User, and securely save the username and password.

  ![Task3 3](https://github.com/user-attachments/assets/aceb0d8c-c14a-4fe1-abff-1f62fa6286a4)





### 7. Test your user's access
- **Copy Sign-in URL**: Copy the Console sign-in URL and open it in an incognito window.
- **Log In**: Use the username and console password from your IAM tab to log in. As a new user, you may see "Access Denied" on some dashboard panels.
- **Check Region and Stop Instance**: Ensure you are in the same region as your deployed production and development instances, then attempt to stop the production EC2 instance.

![Task3 4](https://github.com/user-attachments/assets/5e94d021-da27-4fdf-9d51-e2e1b4915b6a)



![task3 5](https://github.com/user-attachments/assets/eef7238a-b7f3-43f3-aae7-080f92ff3d94)

###  Successfully tested your IAM policy! 🎉



