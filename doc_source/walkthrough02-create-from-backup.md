# Walkthrough 2: Create a File System from a Backup<a name="walkthrough02-create-from-backup"></a>

With Amazon FSx, you can create a file system from a backup\. When you do so, you can change any of the following elements to better suit the use case you have for your newly created file system:
+ Throughput capacity
+ VPC
+ Availability Zone
+ Subnet
+ VPC security groups
+ Active Directory Configuration
+ AWS KMS encryption key
+ Daily automatic backup start time
+ Weekly maintenance window

The following procedure guides you through the process of creating a new file system from a backup\. Before you can create this file system, you must have an existing backup\. For more information, see [Working with Backups](using-backups.md)

**To create a file system from an existing backup**

1. Open the Amazon FSx console at [https://console\.aws\.amazon\.com/fsx/](https://console.aws.amazon.com/fsx/)\.

1. From the navigation list at right, choose **Backups**\.

1. From the table on the dashboard, choose the backup that you want to use for creating a new file system\.

1. Choose **Restore backup**\. This will begin the create file system wizard\.

1. Choose the settings that you'd like to change for this new file system\.

1. Choose **Review summary** to review your settings before creating the file system\.

1. Choose **Create file system**\.

You've now successfully created your new file system from an existing backup\.