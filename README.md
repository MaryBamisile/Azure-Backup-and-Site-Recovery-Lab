# Azure-Backup-and-Disaster-Recovery
<h2>OVERVIEW</h2>
<p>The Azure Backup service provides simple, secure, and cost-effective solutions to back up your data and recover it from the Microsoft Azure cloud. https://learn.microsoft.com/en-us/azure/backup/backup-overview</p>
<h2>Platform Used</h2>
<b>Azure Portal: https://portal.azure.com/</b>

 <b>Services required:</b>
  <li> Recovery service vault
 <li> Backup policy
 <h2>Project-lab walk-through:</h2>
<p align="center">
 
1. Go to Azure portal: https://portal.azure.com/ 
<br>  
Search for "Backup and site recovery" in Azure Marketplace and click on create

![image](https://github.com/user-attachments/assets/d4d1a67a-58c9-4db9-9686-a996ead435b9)

Go ahead and fill in the (Resource group, Name, region etc), you can leave other parameters on default values.

Goto your newly created recovery service vault and locate the 'Backup' blade to configure the backup.

![image](https://github.com/user-attachments/assets/8e9b4e88-ecb8-4940-b90f-a6c41d04eb9b)

Note: The policy definition depend on your organization's preference. Eg: How frequent you want backup to take place and how long to keep the backups etc. 
For this demo, I selected the default policy.

You can decide to exclude some VMs if they are not production environment. I added only one VM as seen in screenshot below:
![image](https://github.com/user-attachments/assets/26f1bf7f-355f-459f-9452-a80ae4105c95)
