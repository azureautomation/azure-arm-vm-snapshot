Azure ARM VM Snapshot
=====================

            

This CreateSnapshotAzureIaaSVM.ps1 script is for creating Blob Snapshots for all Azure IaaS VMs(includes root volume and Data volumes) for Azure Resource Manager VM(un-managed disk). This is intended to run only for Virtual Machines with TagName as 'Environment'
 and TagValue as 'Production'. You can also automate the process of Blob Snapshot by publishing the script in Azure Automation as well with few changes.


A snapshot is a read-only version of a blob that's taken at a point in time. Snapshots are useful for backing up blobs. After you create a snapshot, you can read, copy, or delete it, but you cannot modify it.


See the corresponding article for details and instructions:[https://docs.microsoft.com/en-us/azure/storage/storage-blob-snapshots](https://docs.microsoft.com/en-us/azure/storage/storage-blob-snapshots)


**NOTE: **It is suggested that you download the script file from this page instead of copying and pasting the script code below, in order to avoid any formatting issues that may affect script execution.


 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
