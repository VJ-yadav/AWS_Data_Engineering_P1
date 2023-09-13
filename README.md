# AWS_Data_Engineering_P1

## This is a project for replicating the real world problem I have implemented for Big TEch clients in the past.

### Goal: To predict the performance of the Marketing Video advertisement on the platform like Youtube, Instagram reels for the upcoming Marketing Campaign.


Cloud providers for the project.
    Create AWS account.
    Created the IAM user with Admin access and Enabled MFA for the new user.
    Assigned tags to the User - Tracks for the project resources, billing , or cost analysis and estimation.
    MFA device assigned
    <i>You can register up to 8 MFA devices of any combination of the currently supported MFA types with your AWS account root and IAM user. With multiple MFA devices, you only need one MFA device to sign in to the AWS console or create a session through the AWS CLI with that user.</i>

    LEarn about IAM Identity Center (successor to AWS Single Sign-On)
    
Accessing the AWS console
1. Via Console
AWS CLI -- Install this

AWS Region.
AWS Availability Zone - AZ
AWS S3 bucket Naming convention
Learn about the AWS S3 Bucket Owner Ship
Bucket Versions, Encryption


 aws configure
 Put all the Key_ID values

 Lake House Architecture

 AWS Glue Catalog -- Crawl DAta -- Information, Metadata about the data. 


All the tasks of the Glue

AWS AThena - Adhoc Query Service

Preprocessing required, ETL , data cleaning before crawling the data as it did not work that great with JSON data;
SerDe Libraries , Jason should be in one line, no spaces, no pre formatting.

After cleaning the data , again run the crawler, 

FOr cleaning we will write  a AWS Lambda.


 AWS Wrangler, OR Library
LEarn about the AWS LAmbda, limitations, 


Server LEss architecture
STep functions, LAmbda

Route 53
Cloudfront



underscore prefferred for spark jobs

AWS Glue Triggers, Initiates the ETL Jobs,
The Trigger job, in detail, 

  
Cost Optimization, Refere the Notes from Ipad

AWS Glue Dev Endpoints --- VERY EXPENSIVE.