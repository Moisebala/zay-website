Adding 
RDS Multi-AZ  vs  RDS Read-replicas:
Amazon FSx for Lustre:'hot data' in a parallel and distributed fashion as well as easily store the 'cold data' on Amazon S3
Throughput Optimized HDD (st1) and Cold HDD (sc1) volume types CANNOT be used as a boot volume
Snowball Edge Storage Optimized :  80TB
AWS Lambda: currently supports 1000 concurrent executions per AWS account
AWS Inspector:
Instance Store: temporary storage of information that changes frequently such as buffers, caches, scratch data, and other temporary content.
AWS Shield: managed Distributed Denial of Service (DDoS) protection service that safeguards applications running on AWS.
Cost Storage: S3 < EFS < EBS
Kinesis Stream :  for producer 1MB(1000 messages)/ Shard and consumer read 2MB/Shard or 5 API call /SHARD—all per second 
Kinesis Data Firehose: is the easiest way to reliably load streaming data into data lakes, data stores, and analytics tools
AWS Managed Microsoft AD: configure a trust relationship between AWS Cloud and your existing on-premises Microsoft Active Directory
AD Connector: if you only need to allow your on-premises users to log in to AWS applications and services with their AD credentials
Simple AD: provides a subset of the features offered by AWS Managed Microsoft AD.does not support features such as trust relationships
AWS Cloud Directory: Amazon Cloud Directory is a cloud-native directory
AWS cross-zone LB: distributes traffic across equally to targets in all enabled AZ
AWS Storage Gateway: file , volume or tape
Cache volume vs Stored Volume: CV full volume Amazon S3 service bucket, and just the recently accessed data is retained in the gateway’s local , SV all volume in local
DynamoDB Streams: writes stream records in near-real time so that you can take action based on the contents
DynamoDB point in time:backs up your table data in the preceding 35 days.
Connection Draining: to complete in-flight requests made to instances that are de-registering or unhealthy.
AWS recognize:  image analyse 
AWS transcribe:  speech to text 
AWS translate: translate language any language 
AWS extract:  extract printed text or handwriting text from document
AWS sagemaker: training ML build 
AWS polly: text to speech
AWS lex: Conversational chatbot 
AWS comprehend: natural language processing service (sentiment)
AWS forecast: forecast service analyzing historical data





EC2AZ=$(curl -s http://169.254.169.254/latest/meta-data/placement/availability-zone)
