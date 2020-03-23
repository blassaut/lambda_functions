# lambda_functions

In order to cut the AWS costs, we can use a lambda function to start and stop our instances.

To trigger those functions, a CloudWatch rule in AWS (CRON) can be used : 
* startEC2instance : 0 4 ? * MON-FRI *
* stopEC2instance : 30 17 ? * MON-FRI *
