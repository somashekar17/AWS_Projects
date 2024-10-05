# IAM Policy Simulator

- **Return to AWS Account**: Switch back to your main AWS account (not the dev user) and go to the IAM dashboard.
 ![task3 6](https://github.com/user-attachments/assets/864c9d2e-b2f2-4579-9a6e-193ed5e1bcb9)

- **Access Policy Simulator**: Locate the Policy Simulator link under the Tools panel in the IAM dashboard.
 ![task3 7](https://github.com/user-attachments/assets/003a99db-84a0-4b49-a18e-ec90232c41c3)

- **Select User Group**: Choose your dev user group from the list.
 ![task3 8](https://github.com/user-attachments/assets/2f83106a-59e0-4a6c-8e9c-d217a02d105d)

- **Choose EC2 Actions**: Under Select service, select EC2, then choose DeleteTags and StopInstances from the Select actions drop-down. Click Run Simulation.
 ![task3 9](https://github.com/user-attachments/assets/f86d2f4e-49dc-4cd6-a2ac-9d00538a024b)
![task3 10](https://github.com/user-attachments/assets/2f1af27d-86bf-4e1b-ad66-7621c696334c)

- **Review Denied Actions**: Note that both actions are denied. Expand the toggle for DeleteTags and select Show statement to identify which statement in NextWorkDevEnvironmentPolicy is blocking access.
 ![task3 11](https://github.com/user-attachments/assets/96e9b654-9d71-4cf2-87b8-18c5b0853b73)

- **Simulate StopInstances**: For StopInstances, add the tag development in the Instance field, run the simulation again, and observe that access is granted. You’ve successfully tested your IAM policy! 🎉
 ![task3 12](https://github.com/user-attachments/assets/6100c6de-d07e-4f08-965b-7da83bae4116)
