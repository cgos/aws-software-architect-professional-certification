# sa-pro-cert
Random files in relation to the work done on my software architect professional certification


* AWS Organizations dominated the question pool [Billing alarms, at least 4 questions on tagging, Cost Explorer, SCP, Service Catalogs]
* DevOps[Elastic Beanstalk, BG Deployments, Chef, Puppet]
* NetOps [ CIDR overlap on peering, CIDR arithmetic against instance count, VPC , Peering v/s regions], HA | DR | FT with R53 , SSL offloading, R53 routing policies
* Analytics [ ES and Kibana, Kinesis Stream, firehose and Log Aggregation],
* Migrations [ADS Agent, Collectors, Multiple Snowball, Leverage DX with dedicated connection to AWS]
* CloudFront, Lambda@Edge, Cache hits v/s Query Parameter upper/lower casing,
* Deploying reproducible infrastructure across regions
* EFS Serving NAS and EC2
* Choosing between Lambda+SQS v/s Kinesis
* Securing S3 Buckets via access, end-points and policies
* RTO/RPO + pilot | warm | hot | active-active
* Deciphering policy JSON
* At least 2 questions on X-Ray
* DX, Transit gtwy, Pub/Priv VIFs
* CloudFront, OAI, S3 backed and Website backed and underlying behaviors
* Leveraging global database capabilities [ Aurora, DynamoDB, DAX]
* Everything under Systems Manager, secret management, patch mgmt, param store
* File Systems: EFS, FSx
* IAM, SAML, OpenID, STS, JSON policy docs
* ECS, calibrating task def against environment


1. *Topics*: Some topics I remember from the exam:

* Reserved instances vs spot and where to use what
* S3 transfer acceleration vs multi part
* Transit VPC vs Direct Connect gateway
* Using cloud formation vs SCP to control permissions to AWS services across different teams
* EBS cold starts
* SQS vs SNS for application decoupling
* Direct connect Vs Site-to-site VPN ( in terms of speed & cost)
* CloudHSM vs Customer owned HSM
* Elastic Beanstalk B/G deployments and how it works
* Route 53 fail over across regions
* Multi AZ & Multi region failover scenarios with RDS
* Dynamo global tables


Other notes:
* Service catalog
* Cloud HSM
* AppSync

From what I remember in the exam:
* first question was about sageMaker (my reaction was to standup and leave, but I stayed :stuck_out_tongue: )
* I had a question about service catalog
* couple of questions about multi regional databases
* a lot of questions regarding the migration of servers & databases (know when to use sms, dms, app service discovery with agent and connector)
* Some questions about S3 (encryption, presigned urls ...)
* some questions about Cloudfron + in combination with S3
* scalability and availability with. ASG, ALB, Databases
* Redshift came up couple of times with Kinesis firehose & Kinesis data streams
* Know Batch & EMR
* Quicksight also came up 2 times
* AWS Glue came up 1
* AWS Storage gateway File mode came up once
* Cloudfront HTTP/HTTPS
* ACM with CloudFront, ELB & EC2
* VPN, Transit GW, DX, DXGW
* Transit VPC
* AWS Config came up once
* AWS Secret manager came up a couple of times
* AWS System Manager Parameter store came up once
* ALB + static Ip address
* Couple of questions regarding Global accelerator
* Know when to use Snowball and when to use S3 transfer acceleration vs s3 over DX (question scenario : company has  a 500gbps speed over DX, and 1GBps internet connection, choose how to migrate 20TB of data)
* CodeCommit, CodeBuild & CodePipeline came up oncee
* OpsWorks came up twice, one talking about updating stack (blue/green deployment)
* Know when to use Reserved instances vs on-demand vs spot (2-3 questions, and really tricky)
* Some vpc questions, one I remember about subnetting a CIDR block
* SQS came up a couple of times with standard and FIFO and DLQ


Exam Prep:
* Simulation from AWS
* adrian questions

Exam questions:

IAM:
* are custom groups in IAM available in multiple accounts?
* https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles_terms-and-concepts.html


Links:
https://github.com/alozano-77/AWS-SAA-C02-Course
https://d1.awsstatic.com/whitepapers/building-a-scalable-and-secure-multi-vpc-aws-network-infrastructure.pdf
https://aws.amazon.com/solutions/implementations/aws-landing-zone/


