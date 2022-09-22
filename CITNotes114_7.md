STORAGE TYPES 

 

-Volatile v Non-Volatile 

-Local Storage (RAM, HDD, Optical Drive, Flash Drives) 

*“MOORE’S LAW APPLIES HERE TOO” 

DISASTER RECOVERY 

-Disaster Recovery 

-Fault Tolerance 

-Replication 

-Redundancy 

STORAGE IN THE ENTERPRISE 

RAID (1, 5, 6, 1+0) 

-File servers 

-Network Attached Storage (NAS) 

-Storage Area Network 

STORAGE IN CLOUD 

*“ALLOWS, LIKE MENTIONED BEFORE, IS TO ‘PAY AS YOU GO’” 

-Pay as you go model 

-Benefits (total cost of ownership, Time to deployment, info management) 

-Cloud storage requirements (Durability, Security, Availability) 

TYPES OF CLOUD STORAGE 

-Object 

-File 

-Block 

WAYS TO USE CLOUD STORAGE 

-Backup and recovery 

-Software Tests/developments 

ENCRYPTING SOFTWARE 

-Plain Text vs Cipher Test 

-Data at Rest 

-Data in Transmit 

 

 

 

 

DATA BACKUPS 

-How much is needed to back up? 

-How often is a backup needed? 

-What software is needed to run backups? 

-How will they be implemented? 

-Where and for how long will the data be kept? 

-File Backups 

-Critical Data 

-Databases 

-OS Backups 

AMAZON S3 

S3 Storage Classes 

-Standard 

-Intelligent Tiering 

-Standard-Infrequent Access 

-One Zone-Infrequent Access 

-Glacier 

-Glacier Deep Archive 

-Accessing (through AWS management, Console Line Interface, SDK) 

-Pricing is usually structured around usage frequency and pricing 

-Use Cases (backup/restore, DR, Archiving, data lakes and big analytic data, hybrid cloud storage, cloud-native apps 

S3 GLACIER 

Features and Terms 

-Durability 11 9s of durability 

-Encryption 

-Enforcing compliance 

AMAZON EFS (Elastic File System) 

-File storage in cloud 

-Works well for big data and analytics, media processing workflows, content management, web serving and home directories 

-Petabyte-scale low-latency file system 

-Shared storage 

-Elastic capacity 

-Supports NFS versions 4-4.1 

-Compatible with all Linux-based AMIs for EC2 

 

 
(What I learned is that there are different priority levels for each form of data formatted in a glacier.) 

 

(The summary I could give for all key points in this lecture is that storage services, whether local physically
or throughout cloud services, are very effective for all forms of storage. More notably, S3 Glaciers make it easy
to manage different file relevancy.)