# AWSCertificationGuide


Current Date of closure: 20 June 2020

Cert:: AWS Solution arcitect. 			
version (SAA-C02)					https://d1.awsstatic.com/training-and-certification/docs-sa-assoc/AWS-Certified-Solutions-Architect-Associate_Exam-Guide.pdf 

Good Documentation for assistance
https://github.com/SkullTech/aws-solutions-architect-associate-notes

The exam includes 65 questions and has a time limit of 130 minutes. You need to score a minimum of 720 out of 1000 points to pass the exam

The question format of the exam is one of the following:
	Multiple-choice (one correct response from four options).
	Multiple-response (two or more correct responses from five or more options).


Things to DO: 
	Define Sylabus								-> Find on udemy. 
	Day wise Topic to cover. 					
	Number of mock tests need to be completed	-> 2 Available on Udemy
	Where to buy mock tests from. 				
	Where to get certification dumps. 			
	Close 10 Dumps. 	



Acceptance Criteria 
	Minimum 75% in last 4 mock tests. 


FAQ: 
	Passing percentagee:    			72
	Where to give certification tests 	
	Price Required for test 			150 USD		177-USD		Rs: 14500

MockTest Site:
	https://www.knowledgehut.com/practice-tests/aws-solutions-architect-associate
	https://javarevisited.blogspot.com/2019/08/top-5-free-aws-solution-architect-Associate-certification-dumps-practice-questions.html
	https://www.whizlabs.com/aws-solutions-architect-associate/
	https://pdf.testsdumps.com/SAA-C02.pdf
	file:///Users/bpuneet/Downloads/amazonwebservices.braindump2go.saa-c02.vce.2020-jun-13.by.robin.64q.vce.pdf
	file:///Users/bpuneet/Downloads/saa-c02.pdf
	https://digitalcloud.training/aws-certified-solutions-architect-associate-practice-tests-saa-c02/
	https://www.examtopics.com/exams/amazon/aws-certified-solutions-architect-associate/view/1/
	
Paid tests Available over:
	https://digitalcloud.training/aws-certified-solutions-architect-associate-practice-tests-saa-c02/

Study Material 
	Udemy: 			
	PluralSight: 	Chandni-saxena  		
==============================================
Sylabus
	1) S3
	2) EC2
	3) Load Balancer
	4) Database RDS
	5) Cloudformation
	6) ECS
	7) Lambda
	8) Security
	9) Dynamo DB
=============
Topics Covered: 
	1) VPC/NAT/DirectConnect
	2) SnowBall
	3) EC2	/ Security Groups / Placement Groups
	4) IAM
	5) EBS/EFS/InstanceStore/Raid
	6) RDS	/ Aurora/ ElasticCache/  
	7) CLB/ ELB/ NLB --> Load Balancer
	8) ASG --> Auto Scalling Group. /Launch Configuration
	9) Security
	10) S3:	--> LifeCycle Rules 	--> Transfer Aceleration
			general Purpose			11-9 Availablity
			S3 IA - Infrequent Access
			One Zone Infrequent Acccess
			S3 Intelligent Tiering 
			Glacier
			Glacier Deep Acrhive

			MFA delete for s3 bucket
			S3 Logging
			S3 replication ( Same region/Cross Region)
			S3 Select and Glacier Select

			S3 Locking: Worm Lock ( Write once read many)
	11) Route53 

	12) CLI & SDK\
	13) AdvancedFeatures: 
			CloudFront CDN for better performance--> Edge Location	Caching static Data
			Athena
			Global Accelerator And CloudFront
			AWS database migration Service --> Used to migrate database to aws quickly and securely
			AWS data sync
			AWS SWF 		--> Simple Workflow 
			AWS Step Functions	--> Serverless workflows. 
			AWS EMR --> It is a managed Service to RUN BigData,Hadoop, Spark, Apache Hive on AWS.  --> Elastic Map Reduce
			AWS ElasticTranscoder --> Video on different Platforms. Managed Video service 
			AWS OPS Work --> Its a manged Chef/puppet service. 
			AWS Workspaces --> managed Secure Desktop-as-a-service for VDI, Cloud desktop accessible anywhere.  
			AWS Glue --> It is ETL Service for AWS
			AWS AppSync --> Its a managed GraphQL service by AWS. Can Sync post system comes online after offline actions. like whatsapp. 
			Storage Gateway --> On Prem -> Storage Gateway
								File Access/NFS --> File gateway
								Volumes/Block	--> Volume Gateway
								VTL Tapes/iSCI 	--> Tape Gateway
			AWS ElasticTranscoder --> Convert Media files(Video+Music). Fully managed pay per use
	14) SQS(Queue) And SNS(Topic) 
			SQS types--> 	Standard 
							Dead Letter Queue

===============================================
3 June 2020
Day1: 
	1) Youtube Video 	https://www.youtube.com/watch?v=Ia-UEYYR44s&list=WL&index=28&t=3730s 
			watch first 3 Hours video. And cover all topics. Raise question to each other.  total 10 Questions. 
	2) Topics Coverd: 
		S3
		SnowBall
		VPC						https://sites.google.com/site/awsarticles/home/aws-architect-notes/vpc-overview-components/vpc-exam-questions
								https://sites.google.com/site/awsarticles/home/aws-architect-notes/vpc-overview-components/vpc-exam-questions
		NACL
		Security Groups
		NAT
		VPC 
		IAM 
		Cognito
	3) Questions related to these topics

===============================================
Test1 13 June 2020: 
	https://www.knowledgehut.com/practice-tests/aws-solutions-architect-associate
	Scored: 55% 
	Topics Failed: VPC, Route53, EC2, RDS, 
Test2 24 June 2020: 
	https://www.knowledgehut.com/practice-tests/aws-solutions-architect-associate
	Scored: 66% 
Test3 26 June 2020 
	https://github.com/PrashantWalunj999/AWS-Certified-Solutions-Architect-Certification--SAA-C02--Exam/blob/master/AWS-Certified-Solutions-Architect-Associate_Sample-Questions.pdf
	Scored: 50% 
Test4 27 June 2020
	https://www.whizlabs.com/aws-solutions-architect-associate/
	Scored: 75%
Test5 29June 2020
	UdemyTest1 
	Score: 66%
Test6 29 June 2020: 
	https://www.knowledgehut.com/practice-tests/aws-solutions-architect-associate
	Scored: 82% 
Test6 29 June 2020: 
	https://www.knowledgehut.com/practice-tests/aws-solutions-architect-associate Test3
	Scored: 31%
Test7 30 June 2020: 
	UDEMY test: test2
	Scored: 56%
===============================================

VPC: 
	1) Insance with Access to public subnet will be able to access internet only if they have public IP/ Elastic IP. 
	2) NAT Gateway can give access to EC2 from private IP.  Internet gateway IG is for public subnets. 
	3) NACL are security groups which doesnt even allow traffic to reach inside VPC. Explicity Deny rules.
		NACL have stateless rules, ie you have to define inbound and outbound both for connection.  
	4) NAT instances should have Source/Destination check disabled. 
	5) Egress-Only Internet Gateway is only outbound connection in instances to internet. 
	6) VPC Endpoint: Private url to access the AWS Services.  
		1) Interface Endpoint: All other servies apart from this. 
		2) Gateway Endpoint: S3 and Dynamo DB. 
		3) To use Private DNS, make sure attribute "Enable DNS Hostname" and "Enable DNS Support" are set to true for your VPC.  
	7) 2 VPC will talk to each other via VPC Peering. 
	8) VPNCloudHub: Multiple Sites, should connect with security. 
Route53:
	1) Alias records are free for : S3, ELB, Cloudfront, cloudwatch. 

EC2 : 
	* Placement Groups are 3 types: Cluster, Spread(Max 7 in 1 spread) , Partion 
	* Already created instance CAN'T be moved to placement groups by changing the parameter placement group. 
	* EC2 instance with same security Group can talk to each other in default security group only. 
	* application load Balancer doesnt handle TCP connection. Only NLB handes TCP
	* Classic Load balancers doesnt allow SNI based multiple certificates. only ALB/NLB or Cloudfront can use this feature. 
	* NLB provides, Static IP, whearas ALB provides DNS URLs. 
	* SNI is a way to add multiple Certificcates to a Load Balancer. this is available with ALB/NLB/Cloudfront. 
	* EC2 instance Types: 
		A/T Series 	--> General And Burstable 
		M Series 	--> General Purpose
		R Series 	--> Ram/Memory Obptimized. 
		C Serues 	--> Compute Optimized
		I Series 	--> High on IO. good for Storage optiomized
		P/G/F Series	--> Series with Graphics card. High on performing stuff. 
	* Enhanced networking Has 2 mechanism: ena-support and Intel 82599VF
	* Different instances running on the same physical machine are isolated from each other via the Xen hypervisor.
	* Application Load Balancer and Classic Load Balancer exposes DNS, wherease Network Load Balancer Exposes IP. 
	* EC2 Spot fleet: Fleet can have multiple family of instance and Can be the larger instance as well. at times m4Large > m4.2Xlarge price. In this scenario we can get M4.2Xlarge
	* Scalling policiies: 
		i) 	Step Scalling policy
		ii) Target Tracking
		iii)Simple Scallinng	: Scalling on 
		iv) Scheduled scalling 	:   
EBS: 
	1) Instance Store data is in memory data. It cant be stored in Snapshot. Only can be hibernated. 
	2) For propritery File system. USE EBS. 
	2) Types of EBS volume: 
		IOPS SSD(io1)--> I/O intestive workloads. Used for critical database, because of large IOPS 
		General SSD(gp2) --> Cost effective, general purpose. 3IOPS per GB(Max iops is 16000).
		ThroughPut Optimized HDD(st1) --> low cost HDD designed for higher throughput. BigData, DatawareHoouse, LogProcessing, Kafka, Max Throughput of 500MB/s
		Cold HDD(sc1) -- > Even LOW COST HDD, less frequently accessed data workload. Max throughput 250MB/s, Max iops 500

		There are 2 types of hardDisk.. read https://udemy-images.s3.amazonaws.com/redactor/raw/2018-12-17_12-12-20-ce9961d8c4466dd46d97bc76a7004fb6.png
			SDD --> new Technology, They are expensvice, used for RANDOM, small tasks.
				1) General Ssd 
				2) IOPS ssd

			HDD --> OLD technology, thus cheaper
				1) Throughput optimized 
				2) cold --> less frequently accessed data. 
	3) Type of Raid
		RAID 0 --> Increase Performance. 2 EBS volume, write on either of them. 
		RAID 1 --> Increase Fail Tolerant. 2 EBS Volume, write to both the volumes. 
	4) Attaching EBS volumes: 
		Hot Attach : When system is up n running. 
		Warm Attach: When system is in stop state.
		Cold Attach: when system is starting up. 
RDS: 
	1) Standby RDS instance should never be in same AZ as primary
	2) You can have Encrypted Read repica, only if you have master db as encrypted. 
	3) MasterDB cant be encrypted on fly, you have to create a snapshot and then re-create the db with encryption enabled. 
	4) Read Replica can be in different region or Same region or Same AZ. 
	5) In case of FailOver, the CNAME is automatically changed to BAckup for DR in multiAZ. 
	6) Redshift if you want to rebuild in another region. Modify Redshift cluster and configure cross-region snapshots to other region. 

S3: 
	1) Min size of S3 object is 0Byte and Max is 5TB
	2) You can transition Object to stanrad IA or One Zone IA after atleast 30 days.

CLoudwatch: 
	1) it doesnt provide memory by default. But can be used, via instally agent and having custom metrics
	2) Cloudwatch Dashboard are global and include graphs from different region.
	3) Cloudwatch alarm High Resolution metrics
	4) Monitoring Schemes: 
		Basic: 5 Minutes
		Detailed : 1 Minute
		Custom: 	can be 1 second. 

SQS And SNS: 
	1) Types: Standard, Dead Letter queue
	2) There is an option of long polling, wait till message arrives, max is 20 sec 
	3) Kinesis:  Only used for RealTime and large Streams. 
		Kinesis Stream: Low Latency stream ingest at scale  --> Input
		Kinesis Analytics: Computation done at spark or any other. --> Processing
		Kinesis Firehose --> Load in AWS S3, Elastic Search, Redshift, Splunk --> Storing

	4) Kinesis stream is partition with shards, retention on shard can be 1-7 days max. Data cant be deleted. 
	5) Amazon MQ --> Used for migration of legacy application. It is Active MQ on EC2 instances. 
		Protocol it supports: openWire, AMQP, STOMP, MQTT, WSS
	6) SNS by default have facility to send notifications. 
	7) SQS Visibility Timeout: It is the time period when SQS prevents other from receiving and processing the message

Encryption: 
	1) Type of Encryption: 
		* SSE-C : Default Encryption provided by AWS, BEST for AES-256 cases. 
		* SSE-KMS: Customer Managed Keys, Keys created by customer. 
		* Client Side Encryption : Objects are encrypted at client side and then uploaded. 
		* SSE-S3: Each object is encrypted using a unique Key. 

DataBase: 
	1) RDBMS (RDS ) --> MYSQL, oralce types. 
	2) NoSQL -> Dynamo DB, elastic Cache, Neptune(Graph)
	3) Aurora --> Managed by AWS. Size-> 10GB to 64TB.--> 6replica across 3 AZ--> OLTP completely managed and highly available.  
	4) ElasticCache--> Managed Cache by AWS like redis/memcached. RedisAuth for authentification
	5) Dynamo DB --> AWS prorprietary nosql. Serverless, 
		Dynamo DB Accelerator(DAX) it is in memory cache of dynamo db used to get 10X performance 
	6) REdShiift is used for OLAP_ Online Analytic Processing 
	7) Neptune --> Graph database managed by AWS. 
	8) ElasticSeacrh --> Search engine managed by AWS. very least asked 
	9) DynamoDB --> NoSQL based DB, similar to cassandra, table based. Completely SERVERLESS 


Lambda: 
	1) Max timeout for lambda is 15 Minutes. 
	2) Max memory it can allocate is 3GB. 


AWS Storage Gateway: 
	1) Cached Volumes: Very low latency, Only cached data is stored locally, no need to scale the local on site data. Most data goes in S3. 
	2) Stored Volumes: Store all data locally, and sync point in time. 

AWS DataSync: 
	1) Disable verification during intial file transfer and enable it post transfer for fast transfer and then you can do integreity check. 

CloudFront: 
	1) Signed URL should be used in case of RTMP Distribution, Custom HTTP Client who doesnt support cookies, Single url for single file. 
	2) Signed Cookies should be used, if you dont want to change the URL. Multiple files in HLS format
	3) CloudFront OAI(Origin Access Identity), Used to Give access for S3 bucket only to cloudfront. 
DR: 
	1) Types: 
		Backup and Restore	--> Backup From on Prem to Cloud is sent and stored in AWS but no system is running. 
		Pilot Light			--> Minimal replical is running on AWS, and it can scale quickly. 
		Warm Standby 	--> Active/Passive. Scalled down version is always running. 
		Hot Site/Multi site approach --> Active/Active
	2) DMS and SCT --> Database migration system and Schema converstion tool(Used for different source and target)
	3) AWS DataSync: Used to sync large file from on-prem to AWS. Mostly files to S3, EFS, FSx, 
		Its a schedule based service, runs with cron. Not realtime data. 

Amazon New Services
	1) Amazon Rekognition: To monitor and recognize Pattern on Image and Videos.
	2) Amazon GuardDuty : detect malicioous activity and unauthorized behavior on AWS account. 
	3) Amazon Inspector: Increase security compliance of applications deployed on AWS. 
	4) Amazon Macie: Used to detect usage pattern on S3 data. 

ScaleIN ==> ScaleDown
ScaleOut == Scale up
Well Architected Framework: 
	1) Pillars: 
		* Operational Excellence: 
			Prepare: Runbook, Cloudformation, Config, Anticipate 
			Operate: Automate(Cloudformation), Cloudtrail (Track), Cloudwatch(Track Logs)
			Evolve: Cloudformation(Upgrade), CI-CD tools. 
		* Security: 
			Identity: IAM, STS, MFA,
			Detection: Cloudwatch, Config, Cloudtrail
			Protection: Shield, Cloudfront, WAF
			DataProtection: KMS, S3, 
		* Reliability: 
			Change ManageMent: ASG, CloudWatch, CloudTrail
			FailureManagement: DR, Backups, 
		* Performance Efficiency: 
			Selectoin: ASG, Lambda, Ec2, RDS
			Review: CloudWatch, Cloudformation,
		* Cost Optimization: 
			Expense Awareness: AWSBudget, AWS cost and Usage report, Cost Explorer,
			Cost Effective: Lambda, Spot instance, Reserved Instance, Glacior 
			Matching Suppy&Demand: ASG, Lambda, 
			Optimizing Overtime: Trusted Advisor. 
Cognito: 
	1) Cognitor provides Cognito ID post authentification. 
MISC: 
	1) VPC Transit Gateway is a Star topology. 
	2) AWS RAM --> Resource Access Manager it is used to share AWS resources. can share, It Can Share: TransitGateway, Subnets(VPC), AWS licence Manger and R53. 
	3) ASG have Launch Configuration(Old Method, used in Athena)/Launch Templates(New Method, allowing versioning). Via versioning we have mix of Ec2 instances. 
	4) Sheild is used for prevention against DDOS. Shield Advanced is like paid assistnace service.  
	5) WAF is Web application Firewall, protects at Level7, It only protects against ALB, APIGW, Cloudfront. 
	6) AWS SSM have versioning enabled for auit purpose. 
	7) AWS Trusted Advisor Analyze AWS account for . It Can also send emails on weekly basis on your report. 
		* Cost Optimization
		* Performance
		* Security
		* Fault Tolerance
		* Service Limit
	8) IAM permission boundries are applied to users and roles. CAN NOT BE APPLIED TO GROUPS. 
	9) Secret Manager is Similar to SSM Parameter Store, but Have apility to rotate the passwords.
	SECRET MANAGER is a NEW SERVICE. SSM PARAMETER STORE is old service.  
	10) Bastion Hosts are using the SSH protocol, which is a TCP based protocol on port 22. Only NLB have TCP and UDP enabled. ALB supports HTTP, HTTPS.
	11) ASG auto scalling is never enabled by default. 
	12) APIGW always support https traffic. never support HTTP 

questions: 
	CloudFront CDN for better performance--> Edge Location	Caching static Data
	Athena
	Global Accelerator And CloudFront
	AWS database migration Service --> Used to migrate database to aws quickly and securely
	AWS data sync
	AWS SWF 		--> Simple Workflow 
	AWS Step Functions	--> Serverless workflows. 
	AWS EMR --> It is a managed Service to RUN BigData,Hadoop, Spark, Apache Hive on AWS.  --> Elastic Map Reduce
	AWS ElasticTranscoder --> Video on different Platforms. Managed Video service 
	AWS OPS Work --> Its a manged Chef/puppet service. 
	AWS Workspaces --> managed Secure Desktop-as-a-service for VDI, Cloud desktop accessible anywhere.  
	AWS Glue --> It is ETL Service for AWS
	AWS AppSync --> Its a managed GraphQL service by AWS. Can Sync post system comes online after offline actions. like whatsapp. 
	Storage Gateway --> On Prem -> Storage Gateway
						File Access/NFS --> File gateway
						Volumes/Block	--> Volume Gateway
						VTL Tapes/iSCI 	--> Tape Gateway
	AWS ElasticTranscoder --> Convert Media files(Video +Music). Fully managed pay per use
