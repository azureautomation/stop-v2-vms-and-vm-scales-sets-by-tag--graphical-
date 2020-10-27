Stop V2 VMs and VM Scales Sets by Tag (Graphical)
=================================================

            

DESCRIPTION


This Graphical PowerShell runbook connects to Azure and stops all V2 VMs in an Azure subscription and resource group where a VM or VM Scale Set contains a User Defined Tag Name and Value. You can attach a recurring schedule to this runbook to run it at a
 specific time. 


REQUIRED


1. An Automation connection asset called AzureRunAsConnection that contains the information for connecting with Azure using a service principal.  This Service Principal will need to have been assigned a Role with access to Compute resources


2. An Automation variable asset called 'AzureSubscriptionId' that will contain your Subscription ID where the VMs are currently located.


3. An Automation variable asset called 'Resource-Group' that will contain the Resource Group name where the VMs are currently located.


NOTES

- Both the Tag Name and Tag Value will be asked for as Runbook Input parameters when the runbook is run manually or when the schedule is created.


AUTHOR


Brian C Harrison


LAST EDIT


2017-06-12** *** *


 

 

![Image](https://github.com/azureautomation/stop-v2-vms-and-vm-scales-sets-by-tag-(graphical)/raw/master/StopRMVMsbyTag.png)


        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
