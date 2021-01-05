--------

This content focuses on **\.NET Framework** and **ASP\.NET 4\.x**\. It covers Windows and Visual Studio\.

Looking for **\.NET Core** or **ASP\.NET Core**? Go to *[version 3\.5 or later](https://docs.aws.amazon.com/sdk-for-net/latest/developer-guide/welcome.html)*\. It covers cross\-platform development in addition to Windows and Visual Studio\.

--------

# Monitoring Your AWS Resources Using Amazon CloudWatch<a name="cloudwatch"></a>

Amazon CloudWatch is a web service that monitors your AWS resources and the applications you run on AWS in real time\. You can use CloudWatch to collect and track metrics, which are variables you can measure for your resources and applications\. CloudWatch alarms send notifications or automatically make changes to the resources you’re monitoring based on rules that you define\.

The code for these examples is written in C\#, but you can use the AWS SDK for \.NET with any compatible language\. When you install the AWS Toolkit for Visual Studio, a set of C\# project templates are installed\. The simplest way to start this project is to open Visual Studio, and then choose **File**, **New Project**, **AWS Sample Projects**, **Deployment and Management**, **AWS CloudWatch Example**\.

 **Prerequisite Tasks** 

Before you begin, be sure that you have created an AWS account and set up your AWS credentials\. For more information, see [Setting up the AWS SDK for \.NET](net-dg-setup.md)\.

**Topics**
+ [Describing, Creating, and Deleting Alarms in Amazon CloudWatch](cloudwatch-creating-alarms-examples.md)
+ [Using Alarms in Amazon CloudWatch](cloudwatch-using-alarms-examples.md)
+ [Getting Metrics from Amazon CloudWatch](cloudwatch-getting-metrics-examples.md)
+ [Sending Events to Amazon CloudWatch Events](cloudwatch-examples-sending-events.md)
+ [Using Subscription Filters in Amazon CloudWatch Logs](cloudwatch-using-subscriptions-examples.md)