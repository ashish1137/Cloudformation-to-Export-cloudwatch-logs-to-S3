# Cloudformation-to-Export-cloudwatch-logs-to-S3

An end to end cloudformation to export cloudwatch logs to S3. You will need to provide following details.    

 1. Region: Name of the region (Eg - ap-southeast-2).
 2. DestinationBucket: Name of the new bucket where cloudwatch logs are to be exported.
 3. LogGroupName: Name of the cloudWatch log group which has to be exported.
 4. NumberOfDays: If today is November 21st and NUMBEROFDAYS = 1, November 20th logs will be exported. (Default- 2)   
 5. ExpirationInDaysFromGlacier: Number of days after which items will be deleted from glacier. (Default- 365)
 6. TransitionInDaysFromS3ToGlacier: Number of days after which items will be moved from S3 to glacier. (Default- 1)
 7. SubscriberEmail: Email address who will receive the failure email.
