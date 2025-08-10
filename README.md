# 🖥 AWS EC2 Windows Server – System Info Assignment

This repository contains my GUVI AWS task, where I created a Windows Server EC2 instance, connected via RDP, retrieved system information, and saved it for submission.

---

## 🛠 Tasks Performed

1. *Launched an AWS EC2 Instance*
   - Selected *Windows Server 2025 Base* AMI
   - Chose instance type t3.micro (Free Tier eligible)
   - Configured Security Group to allow *RDP (TCP port 3389)*
   - Downloaded the .pem key file

2. *Retrieved Administrator Password*
   - Used AWS console’s “Get Windows Password” option
   - Decrypted it using the .pem key

3. *Connected via RDP*
   - Opened *Remote Desktop Connection* on my local machine
   - Entered the public IP of the EC2 instance
   - Logged in with Administrator credentials

4. *Retrieved System Information*
   - Opened *Command Prompt* inside the VM
   - Ran:
     cmd
     systeminfo
     
   - Displayed OS version, architecture, hardware details, and network info

5. *Captured Screenshot*
   - Enabled *drive sharing* in RDP settings
   - Saved the screenshot to a shared local drive for transfer

---

## 💻 Tech Stack

- *AWS EC2* (Windows Server 2019 Base)
- *RDP Client* (Windows built-in mstsc)
- *Command Prompt* for system info retrieval

----
