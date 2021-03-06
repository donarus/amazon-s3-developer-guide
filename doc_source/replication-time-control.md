# Replicating Objects Using S3 Replication Time Control \(S3 RTC\)<a name="replication-time-control"></a>

S3 Replication Time Control \(S3 RTC\) helps you meet compliance or business requirements for data replication and provides visibility into Amazon S3 replication times\. S3 RTC replicates most objects that you upload to Amazon S3 in seconds, and 99\.99 percent of those objects within 15 minutes\. 

With replication metrics, you can monitor the total number of S3 API operations that are pending replication, the total size of objects pending replication, and the maximum replication time to the destination Region\. Replication metrics are available through the [Amazon S3 console](https://console.aws.amazon.com/s3/) and [Amazon CloudWatch](https://docs.aws.amazon.com/AmazonCloudWatch/latest/DeveloperGuide/)\. For more information, see [Amazon S3 CloudWatch replication metrics](cloudwatch-monitoring.md#s3-cloudwatch-replication-metrics)\.

With S3 RTC, Amazon S3 events notify you in the rare instance when objects do not replicate within 15 minutes and when those objects replicate successfully to their destination Region\. Amazon S3 events are available through Amazon SQS, Amazon SNS, or AWS Lambda\. For more information, see [ Configuring Amazon S3 event notifications](NotificationHowTo.md)\.

**Topics**
+ [Enabling S3 Replication Time Control](enabling-replication-time-control.md)
+ [Using Replication Metrics to Monitor Amazon S3 Replication Configurations](using-replication-metrics.md)
+ [Using Amazon S3 Events to Track S3 Replication Time Control Objects](using-s3-events-to-track-rtc.md)
+ [Best Practices and Guidelines for Using S3 Replication Time Control](rtc-best-practices.md)