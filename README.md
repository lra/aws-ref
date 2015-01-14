# aws-ref

A simple AWS reference of stuff to be used in IAM.

## S3

### S3 Object Operations

- `s3:AbortMultipartUpload`
- `s3:DeleteObject`
- `s3:DeleteObjectVersion`
- `s3:GetObject`
- `s3:GetObjectAcl`
- `s3:GetObjectTorrent`
- `s3:GetObjectVersion`
- `s3:GetObjectVersionAcl`
- `s3:GetObjectVersionTorrent`
- `s3:ListMultipartUploadParts`
- `s3:PutObject`
- `s3:PutObjectAcl`
- `s3:PutObjectVersionAcl`
- `s3:RestoreObject`

### S3 Bucket Operations

- `s3:CreateBucket`
- `s3:DeleteBucket`
- `s3:ListAllMyBuckets`
- `s3:ListBucket`
- `s3:ListBucketMultipartUploads`
- `s3:ListBucketVersions`

### S3 Bucket Subresource Operations

- `s3:DeleteBucketPolicy`
- `s3:DeleteBucketWebsite`
- `s3:GetBucketAcl`
- `s3:GetBucketCORS`
- `s3:GetBucketLocation`
- `s3:GetBucketLogging`
- `s3:GetBucketNotification`
- `s3:GetBucketPolicy`
- `s3:GetBucketRequestPayment`
- `s3:GetBucketVersioning`
- `s3:GetBucketWebsite`
- `s3:GetLifecycleConfiguration`
- `s3:PutBucketAcl`
- `s3:PutBucketCORS`
- `s3:PutBucketLogging`
- `s3:PutBucketNotification`
- `s3:PutBucketPolicy`
- `s3:PutBucketRequestPayment`
- `s3:PutBucketVersioning`
- `s3:PutBucketWebsite`
- `s3:PutLifecycleConfiguration`

## RDS

### RDS Operations

- `rds:AddSourceIdentifierToSubscription`ß
- `rds:AddTagsToResource`
- `rds:ApplyPendingMaintenanceAction`
- `rds:AuthorizeDBSecurityGroupIngress`
- `rds:CopyDBParameterGroup`
- `rds:CopyDBSnapshot`
- `rds:CopyOptionGroup`
- `rds:CreateDBInstance`
- `rds:CreateDBInstanceReadReplica`
- `rds:CreateDBParameterGroup`
- `rds:CreateDBSecurityGroup`
- `rds:CreateDBSnapshot`
- `rds:CreateDBSubnetGroup`
- `rds:CreateEventSubscription`
- `rds:CreateOptionGroup`
- `rds:DeleteDBInstance`
- `rds:DeleteDBParameterGroup`
- `rds:DeleteDBSecurityGroup`
- `rds:DeleteDBSnapshot`
- `rds:DeleteDBSubnetGroup`
- `rds:DeleteEventSubscription`
- `rds:DeleteOptionGroup`
- `rds:DescribeAccountAttributes`
- `rds:DescribeDBEngineVersions`
- `rds:DescribeDBInstances`
- `rds:DescribeDBLogFiles`
- `rds:DescribeDBParameterGroups`
- `rds:DescribeDBParameters`
- `rds:DescribeDBSecurityGroups`
- `rds:DescribeDBSnapshots`
- `rds:DescribeDBSubnetGroups`
- `rds:DescribeEngineDefaultParameters`
- `rds:DescribeEventCategories`
- `rds:DescribeEvents`
- `rds:DescribeEventSubscriptions`
- `rds:DescribeOptionGroupOptions`
- `rds:DescribeOptionGroups`
- `rds:DescribeOrderableDBInstanceOptions`
- `rds:DescribePendingMaintenanceActions`
- `rds:DescribeReservedDBInstances`
- `rds:DescribeReservedDBInstancesOfferings`
- `rds:DownloadDBLogFilePortion`
- `rds:ListTagsForResource`
- `rds:ModifyDBInstance`
- `rds:ModifyDBParameterGroup`
- `rds:ModifyDBSubnetGroup`
- `rds:ModifyEventSubscription`
- `rds:ModifyOptionGroup`
- `rds:PromoteReadReplica`
- `rds:PurchaseReservedDBInstancesOffering`
- `rds:RebootDBInstance`
- `rds:RemoveSourceIdentifierFromSubscription`
- `rds:RemoveTagsFromResource`
- `rds:ResetDBParameterGroup`
- `rds:RestoreDBInstanceFromDBSnapshot`
- `rds:RestoreDBInstanceToPointInTime`
- `rds:RevokeDBSecurityGroupIngress`

### RDS Resources

- `rds:DatabaseClass` (String) The DB instance class of a DB instance
- `rds:DatabaseEngine` (String) The DB engine of the DB instance
- `rds:DatabaseName` (String) The name of the database on the DB instance
- `rds:MultiAz` (Integer) Indicates if the DB instance is running in multiple availability zones. 1 indicates that the DB instance is using multi-AZ.
- `rds:Piops` (Integer) This key will be present when a request is made for a DB instance with PIOPs enabled. The value will contain the number of provisioned IOs that an instance supports. 0 indicates does not have PIOPs enabled.
- `rds:StorageSize` (Integer) The storage volume size (in GB)
- `rds:Vpc` (Integer) Indicates if the database instance is running in a virtual private cloud

## CloudSearch

### ClourSearch Operations

- `cloudsearch:BuildSuggesters`
- `cloudsearch:CreateDomain`
- `cloudsearch:DefineAnalysisScheme`
- `cloudsearch:DefineExpression`
- `cloudsearch:DefineIndexField`
- `cloudsearch:DefineSuggester`
- `cloudsearch:DeleteAnalysisScheme`
- `cloudsearch:DeleteDomain`
- `cloudsearch:DeleteExpression`
- `cloudsearch:DeleteIndexField`
- `cloudsearch:DeleteSuggester`
- `cloudsearch:DescribeAnalysisSchemes`
- `cloudsearch:DescribeAvailabilityOptions`
- `cloudsearch:DescribeDomains`
- `cloudsearch:DescribeExpressions`
- `cloudsearch:DescribeIndexFields`
- `cloudsearch:DescribeScalingParameters`
- `cloudsearch:DescribeServiceAccessPolicies`
- `cloudsearch:DescribeSuggesters`
- `cloudsearch:document`
- `cloudsearch:IndexDocuments`
- `cloudsearch:ListDomainNames`
- `cloudsearch:search`
- `cloudsearch:suggest`
- `cloudsearch:UpdateAvailabilityOptions`
- `cloudsearch:UpdateScalingParameters`
- `cloudsearch:UpdateServiceAccessPolicies`

## DynamoDB

### DynamoDB Operations

- `dynamodb:BatchGetItem`
- `dynamodb:BatchWriteItem`
- `dynamodb:CreateTable`
- `dynamodb:DeleteItem`
- `dynamodb:DeleteTable`
- `dynamodb:DescribeTable`
- `dynamodb:GetItem`
- `dynamodb:ListTables`
- `dynamodb:PutItem`
- `dynamodb:Query`
- `dynamodb:Scan`
- `dynamodb:UpdateItem`
- `dynamodb:UpdateTable`

## IAM ARNs

| Service                            | Namespace                    |
| ---------------------------------- | ---------------------------- |
| Amazon CloudFront                  | `cloudfront`                 |
| Amazon EC2                         | `ec2`                        |
| Amazon Elastic MapReduce           | `elasticmapreduce`           |
| Amazon ElastiCache                 | `elasticache`                |
| Amazon Glacier                     | `glacier`                    |
| Amazon Kinesis                     | `kinesis`                    |
| Amazon RDS                         | `rds`                        |
| Amazon Redshift                    | `redshift`                   |
| Amazon Route 53                    | `route53`                    |
| Amazon S3                          | `s3`                         |
| Amazon SES                         | `ses`                        |
| Amazon SimpleDB                    | `sdb`                        |
| Amazon SNS                         | `sns`                        |
| Amazon SQS                         | `sqs`                        |
| Amazon SWF                         | `swf`                        |
| Amazon VPC                         | `ec2`                        |
| Auto Scaling                       | `autoscaling`                |
| AWS Billing and Cost Management    | `aws-portal`                 |
| AWS CloudFormation                 | `cloudformation`             |
| AWS Elastic Beanstalk              | `elasticbeanstalk`           |
| AWS Identity and Access Management | `iam`                        |
| AWS Marketplace                    | `aws-marketplace`            |
| AWS Marketplace Management Portal  | `aws-marketplace-management` |
| AWS OpsWorks                       | `opsworks`                   |
| AWS Storage Gateway                | `storagegateway`             |
| AWS STS                            | `sts`                        |
| AWS Support                        | `support`                    |
| CloudWatch                         | `cloudwatch`                 |
| DynamoDB                           | `dynamodb`                   |
| Elastic Load Balancing             | `elasticloadbalancing`       |
