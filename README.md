# Cloudformation-to-Export-cloudwatch-logs-to-S3

An end to end cloudformation to export cloudwatch logs to S3. You will need to provide following details.    

 1. DESTINATIONBUCKET: Name of the new bucket where cloudwatch logs are to be exported.
 2. GROUPNAME: Name of the cloudWatch log group which has to be exported.
 3. NUMBEROFDAYS: If today is November 21st and NUMBEROFDAYS = 1, November 20th logs will be exported. (e.g. 2)    
 4. SUBSCRIBEREMAIL: Email address who will receive the failure email.
