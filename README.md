eb_config_examples
==================

Collection of AWS Elastic Beanstalk configurations for .ebextensions  

Applications:  
  * [Loggly Gen 2 Server Config](https://github.com/lapygithub/eb_config_examples/blob/master/.ebextensions/loggly_gen2.config) - SaaS Log Management ([Loggly](www.loggly.com))  
  * [New Relic Server Config](https://github.com/lapygithub/eb_config_examples/blob/master/.ebextensions/newrelic.config) - SaaS Application and Server Monitoring ([New Relic](www.newrelic.com))  
  * [AWS Cloudwatch Metrics](https://github.com/lapygithub/eb_config_examples/blob/master/.ebextensions/cloudwatchmetrics.config) - ([Source](http://docs.aws.amazon.com/))  
  * AWS Cloudwatch Alarms:
  	> - [Elastic Beanstalk](https://github.com/lapygithub/eb_config_examples/blob/master/.ebextensions/ELB-Alarms.config) ([Source](https://s3.amazonaws.com/elasticbeanstalk/extensions/ELB-Alarms.config))  
  	> - [RDS](https://github.com/lapygithub/eb_config_examples/blob/master/.ebextensions/RDS-Alarms.config) ([Source](https://s3.amazonaws.com/elasticbeanstalk/extensions/RDS-Alarms.config))  
  	> - [SNS and SQS](https://github.com/lapygithub/eb_config_examples/blob/master/.ebextensions/SNS.config) ([Source](https://s3.amazonaws.com/elasticbeanstalk/extensions/SNS.config))  
  	> - [Dynamo DB](https://github.com/lapygithub/eb_config_examples/blob/master/.ebextensions/DynamoDB-with-CloudWatch-Alarms.config) ([Source](https://s3.amazonaws.com/elasticbeanstalk/extensions/DynamoDB-with-CloudWatch-Alarms.config))  
  	> - [ElasticCache](https://github.com/lapygithub/eb_config_examples/blob/master/.ebextensions/ElastiCache.config) ([Source](https://s3.amazonaws.com/elasticbeanstalk/extensions/ElastiCache.config))  

  * [AWS Environment Variables and Option Settings](https://github.com/lapygithub/eb_config_examples/blob/master/.ebextensions/environment.config)  
  * [Cloud Formation](https://github.com/lapygithub/eb_config_examples/blob/master/.ebextensions/02_load_balancer.config) [Source](http://www.delarre.net/posts/elasticbeanstalk-vpc-fun/)
  * [AWS Post Deployment Scripts](https://github.com/lapygithub/eb_config_examples/blob/master/.ebextensions/99delayed_job.config)  
  * [AWS Ruby "Internal Server Error" fix](https://github.com/lapygithub/eb_config_examples/blob/master/.ebextensions/tmpwatch_cron.config)  

Tips & Tricks:  
  + [Faster Deployment and Timing](http://horewi.cz/faster-rails-3-deployments-to-aws-elastic-beanstalk.html)  
  + [EB Deployment](http://www.hudku.com/blog/innocuous-looking-evil-devil/)  
  + [Libcouchbase Deployment](http://www.delarre.net/posts/deploying-libcouchbase-with-aws-elasticbeanstalk.html)  
  + [VPC Beanstalk Deployment](http://www.delarre.net/posts/elasticbeanstalk-vpc-fun.html)  
  + [Post Deployment Scripts](http://junkheap.net/blog/2013/05/20/elastic-beanstalk-post-deployment-scripts/)  
  + [CloudWatch Alarm Examples](http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/customize-environment-resources-examples.html)  
  + [CloudFormation Resource Types](http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-template-resource-type-ref.html)  
