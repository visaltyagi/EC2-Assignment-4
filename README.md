# EC2-Assignment-4
How to Create a FSx File System for Windows &amp; Linux Operating Systems - EC2 Assignment 4

**Problem Statement:**

You work for XYZ Corporation and the current requirement in the organization is for faster file sharing, which can also help in data replication from On-Premises infrastructure.

**You have been asked to:**

**1.** Create an FSx file system for a windows file server

**a.** Make sure you have AWS Managed Active Directory with a valid domain name.

**b.** Connect it to your Windows EC2 server.

**2.** Create an FSx file system for Lustre and attach it to an Amazon Linux 2 instance.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Problem Solution:**

**Step 1:** Create a Microsoft Active Managed directory with the valid domain name

**Step 2:** Create an EC2 Instance

**Step 3:** Open the RDP Client & create a (R:) mount on the Windows Virtual Server.

**Step 4:** If the (R:) mount successfully created, it means you have created a valid domain name on the EC2 Instance.

**Step 5:** Create a FSx file for Lustre.

**Step 6:** Create an EC2 Instance

**Step 7:** Add the Lustre Port in the EC2 Instance Security group.

**Step 8:** Create a /fsx directory on the Amazon EC2 Instance.

**Step 9:** If the fsx directory will be successfully mounted. It means you FSx for Lustre is successfully connected to the EC2 Instance.


**For More Information, check the detailed guide over here:**: **https://medium.com/devops-guides/how-to-create-a-fsx-file-system-for-windows-linux-operating-systems-ec2-7034dd8d12b3**

