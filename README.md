Generate report for unattached Azure disks (managed and un-managed)
===================================================================

            

PowerShell script to generate a report of unattached VHD disks. This script will create two files - unattached_managed_disks.csv,


 unattached_un_managed_disks.csvThese two files will contain details about VHD files that are not attached to an Azure virtual machine.


NOTE: You have to login into your account before running the script. 'login-azurermaccount' to log in to your account.


You can use the generated CSV to better manage your Azure infrastructure. Understand why the disks are not in use and take an informed decision on whether you want to delete or re-use them. Thus helping you to identify resources that are not being utilized
 and to reduce cost.


 


Powershell Code:


-------------------


 


 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
