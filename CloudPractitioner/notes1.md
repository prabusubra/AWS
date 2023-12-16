1. Elastic Load Balancer(ELB)
       - Application Load Balancer (Layer 7) at http/https/gRPC
       - Network Load Balancer (Layer 4) high performace
       - Gateway Load Balancer (Layer 3)
   
2. Scalability
    - Vertical -- Increase the size of the instance.
    - Horizontal -- Increase number of instances
3. High Availability -- Running your application atleast at two Availability Zones(AZ).
4. Elasticity -- dynamic scaling
5. AutoScalingGroup(ASG):-
       - Launch Template
       - Types
           - Manually
           - Dynamic
           - Scheduled
           - Predictive
           - Target Tracking

S3:-
       Simple Storage System(S3)
       Infinitely Scaling
       Backup and Storage
       Disaster Recovery
       Archive

Policy:-
       User-Based
       Resource-Based
       ACL

Relication:- it is a async operation.
       Cross-Region Replication
       Same-Region Replication
       Different AWS account Replication

Classes:-
       Standard (99.99 % available)
       Standard Infrequent Access(IA)
              - 99.9 % available
              - suitable for Disaster recovery and backup
       One Zone Infrequent Access
              - Data will be lost if one AZ destroyed.
              - 99.5 % available
              - suitable for secondary copy of backups.
       Glacier Instant Retrival
              - Glacier is for archiving/backups
              - milli second retrieval
              - minimum storage duration is 90 days.
       Glacier Frequent Retrival
              - Expedited -- 1 to 5 min
              - standard -- 3 to 4 hours
              - bulk -- 5 to 12 hours
              - minimum storage duration is 90 days.
       Glacier Deep Archive
              - Standard -- 12 hours
              - Bulk -- 48 hours
              - minimum storage duration is 180 days.
       Instand Tiering
              - monthly monitoring and auto-tiering fee.
                     1. Frequent Access Tier - default
                     2. Infrequent Access Tier - object not accessed by 30 days.
                     3. Archive Instant Access Tier - object not accessed by 90 days.
                     4. Archive Access Tier - 90 - 700 days.
                     5. Deep Archive Access Tier - 180 - 700 days

AWS Snow Family:-
       - data migration with snow family
       - offline device to perform data migration.
       - if it takes more than a week to transfer a data, then use snowball device.
       - AWS will send physical device by post office. then u load the data in to it and send back.
       -  Snowball edge
              - Snowball Edge Storage optimized - 80TB
              - Snowball Edge Compute Optimized - 42TB of HDD or 28TB NVMe capacity.
              - Snowcone - small, rugged - 8TB of HDD
              - Snowcone SSD - 14TB
              - Snow Mobile - 10,00,000 TB
       
       
       
           
