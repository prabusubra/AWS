
Amazon Resources(EC2, RDS...) --> subnet --> VPC --> Internet Gateway --> Internet

Virtual Private Gateway(VPG) --> Protects the Internet to enter VPC. it enables virtual Private Network(VPN).

AWS Direct --> Reduce network cost and increase bandwidth.

Network ACL:- stateless and works at Subnet level, By Default allows all the inboud/outbound network traffics.

Security Group:- statefull and works at EC2 instance level, By default denies all the inbound/outbound network traffics.

Storage:-

Instance Store:- ideal for short time and temporary data. on stop or terminate of EC2, data will be lost.

Amazon Elastic Block Storage(EBS):-  On stop or terminate of EC2 data will be available.
                                     EBS Snapshot for creating incremental backups.

Amazon Simple Storage Service(S3):- max size is 5TB

Amazon Elastic File System(EFS):- grows and shrinks automatically.

Amazon RDS:- 
    Amazon Aurora - for high availability, 6 copy of your data accross 3 AZs and continously backup the data to Amazon S3.

    Amazon DynamoDB - NoSQL, Key-value database

Amazon Redshift:- it is a data warehouse service and used for big data analytics.

Amazon Database Migration Service(DMS):- 

Security:-
    Root User -> Root user creates the first IAM user and grants the permission to create users, then IAM user creates the new users.
    AWS Policy
    AWS Audit:- access to AWS security and compliance reports.
                    1. Aggrements
                    2. reports
    Denial of Service -> block listing
    AWS Shield:-
        1. Standard
        2. Advanced
    Amazon Key Management Service(KMS):- 
    Amazon WAF - monitor network request comming to web application
    AWS Inspector - performs automated security assements.
    Amazon GaurdDuty - intelligent threat detection.

Monitoring:-
    Amazon Cloud Watch:- AWS Services sends the metrics to Cloud Watch, then it generate the graph.
    Amazon Cloud Watch Alarm:- automatically stopt if metric reachs certain value.

    Amazon Cloud Trails:-  Records the API calls.

    Trusted Advicers:- 
        inspects AWS Environment and provide recommendations.

Migration:-
    AWS Cloud Adoption Framework(CAF)
    Migration
    AWS Snow
        


