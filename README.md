# Active Directory Help Desk Project

This project demonstrates my hands-on experience managing users, groups, and security policies in **Active Directory**.  
It simulates real Help Desk operations such as user account management, permissions, and Group Policy configuration, essential tasks in enterprise IT support environments.

## Tools Used

- **Windows Server 2022**
- **Active Directory Users and Computers (ADUC)**
- **Group Policy Management Console (GPMC)**
- **Event Viewer**
- **VirtualBox / VMware Workstation**


## Skills Demonstrated

- User account lifecycle management  
- Organizational Unit (OU) structuring  
- Group and permission administration  
- Security and password policy enforcement  
- Auditing and troubleshooting using Event Viewer  
- GPO creation and configuration  


## Tasks for this project

### 1️. Create a New User Account
Created a new user in **Active Directory Users and Computers (ADUC)** and assigned it to the correct Organizational Unit (OU).  
![Screenshot](https://github.com/Binali2142/Active-Directory-Help-Desk-Project/blob/main/Screenshots/01_create_user.png)



### 2️. Reset User Password
Simulated a common Help Desk scenario where a user forgot their password and reset it securely via ADUC.  
![Screenshot](https://github.com/Binali2142/Active-Directory-Help-Desk-Project/blob/main/Screenshots/02_reset_password.png)



### 3️. Unlock Locked Account
Demonstrated how to unlock a locked-out user after multiple failed login attempts.  
![Screenshot](https://github.com/Binali2142/Active-Directory-Help-Desk-Project/blob/main/Screenshots/03_unlock_account.png)


### 4️. Disable and Enable User Account
Temporarily disabled a user account to restrict access and later re-enabled it.  
![Screenshot](https://github.com/Binali2142/Active-Directory-Help-Desk-Project/blob/main/Screenshots/04_disable_enable_account.png)


### 5️. Add User to Security Group
Added a user to a security group to assign access permissions to shared folders and resources.  
![Screenshot](https://github.com/Binali2142/Active-Directory-Help-Desk-Project/blob/main/Screenshots/05_add_to_group.png)


### 6️. Move User Between OUs
Organized the directory structure by moving a user from one Organizational Unit to another.  
![Screenshot](https://github.com/Binali2142/Active-Directory-Help-Desk-Project/blob/main/Screenshots/06_move_user_ou.png)


### 7️. Audit Login Attempts (Event Viewer)
Used **Event Viewer** to view and filter login attempts (Event IDs 4624 for success and 4625 for failure).  
![Screenshot](https://github.com/Binali2142/Active-Directory-Help-Desk-Project/blob/main/Screenshots/07_event_viewer_audit.png)


### 8️. Create and Link Group Policy Object (GPO)
Created a custom Group Policy Object and linked it to a specific OU to enforce administrative settings.  
![Screenshot](https://github.com/Binali2142/Active-Directory-Help-Desk-Project/blob/main/Screenshots/08_create_gpo.png)
![Screenshot](https://github.com/Binali2142/Active-Directory-Help-Desk-Project/blob/main/Screenshots/08_Gpo_configuration.png)
![Screenshot](https://github.com/Binali2142/Active-Directory-Help-Desk-Project/blob/main/Screenshots/08_linked_gpo.png)


### 9️. Set Password Policy via GPO
Configured organization-wide password complexity, length, and expiration rules through Group Policy.  
![Screenshot](https://github.com/Binali2142/Active-Directory-Help-Desk-Project/blob/main/Screenshots/09_password_policy.png)


### 10. Apply Logon Banner Using GPO
Configured an interactive logon message to display company policy before login.  
![Screenshot](https://github.com/Binali2142/Active-Directory-Help-Desk-Project/blob/main/Screenshots/10_GPO_setting_%20window.png)
![Screenshot](https://github.com/Binali2142/Active-Directory-Help-Desk-Project/blob/main/Screenshots/10_logon_banner.png)



### **Author:** Qasim Ali Mahamed
**GitHub:** [https://github.com/Binali2142]  
**LinkedIn:** [www.linkedin.com/in/qasim-ali-mahamed-107069217]  


