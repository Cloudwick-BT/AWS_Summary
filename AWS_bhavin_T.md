## Amazon Web Services

### AWS products

####*  Compute and Networking Services
Many Computing and Networking Services are provided by AWS to meet the application's demand.

  1. Amazon EC2:
    * Elastic Compute Cloud provides resizeable computing capacity that will be used to support the application. An AMI (Amazon Machine Image) is the template that contains software configuration which can be launched known as _Instance_.

  2. VPC:
    * Virtual private cloud is virtual network dedicated to AWS account. It is same as server at our local loction which is not accessible by other traffic. 


####*  Storage and Content Delivery Services
AWS provides many storage options to meet business needs.

  1. Amazon S3:
    * Aazon Simple Storage Service can handles large amount of data which are stored in chunks called as _buckets_. We can assign access rights for each buckets which must be _unique_.

  2. CloudFront Distributions:
    * It makes content of your website available to the user from any location. After storing the content on origin location like S3 and associating the CloudFront distribution with the origin server, allows our website to be scaled world wide.


####* Security and Identity Services

  1. IAM:
    * Identity and Access Management lets you set permission for user to access resources.

  2. Directory Services:
    * Sets permission to access directory.


####* Database Services
It provides fully-managed relational and NoSQL database with in-memory caching and petabyte-scale data warehouse solution.

  1. Amazon RDS:
    * Provide Relational Database Service which can be used to query complex functions.

  2. Amazon RedShift:
    * Fully managed petabyte-scaled data warehouse.

  3. Amazon DynamoDB:
    * Provides schema flexibility with NoSQL database, which enables faster read and write.

  4. Amazon ElastiCache:
    * Helps improve performance by caching I/O itensive queries and managing web session data.



###What free tier has to offer ?

Amazon allows to use thier services for free for 1 year after subscribing which includes following resources:

  1. __Server__: 623 MB of RAM with 750 hr/month
  2. __Storage__: 30 GB on EBS, 5GB of S3, 2 millions of I/O, 1 GB of snapshots. Charges are 10 cents per 1 million I/O requests per month.
  3. __Database__: Relations DB have 20 GB of storage and NoSQL is 100MB storage.
  4. __Data Transfer__: 15GB outbound traffic.