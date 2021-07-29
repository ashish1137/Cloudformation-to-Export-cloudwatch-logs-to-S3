# Cloudformation-to-Export-cloudwatch-logs-to-S3

An end to end cloudformation to export cloudwatch logs to S3. You need to provide following details.
    DESTINATIONBUCKET: Name of the new bucket where cloudwatch logs are to be exported
    GROUPNAME: Name of the cloudWatch log group which has to be exported
    NUMBEROFDAYS: If today is November 21st and NUMBEROFDAYS = 1, November 20th logs will be exported. (e.g. 2)
    SUBSCRIBEREMAIL: Email address who will receive the failure email
