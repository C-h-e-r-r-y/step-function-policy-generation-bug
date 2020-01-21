# How reproduce
1. Run `npm install` from `/serverless` fodler
1. setup aws credentials
1. execute `serverless deploy`

You will got:

```

cmd.exe /c "serverless deploy"
 
 Serverless Warning --------------------------------------
 
  A valid option to satisfy the declaration 'opt:stage' could not be found.
 
Serverless: Added parameters to template
Serverless: Packaging service...
Serverless: Added parameters to template
Serverless: Uploading CloudFormation file to S3...
Serverless: Uploading artifacts...
Serverless: Validating template...
Serverless: Updating Stack...
Serverless: Checking Stack update progress...
....
Serverless: Operation failed!
Serverless: View the full error output: https://us-east-2.console.aws.amazon.com/cloudformation/...
 
  Serverless Error ---------------------------------------
 
  An error occurred: MyUnderscorestateUnderscoremachineRole - The policy failed legacy parsing (Service: AmazonIdentityManagement; Status Code: 400; Error Code: MalformedPolicyDocument; Request ID: ).
 
  Get Support --------------------------------------------
     Docs:          docs.serverless.com
     Bugs:          github.com/serverless/serverless/issues
     Issues:        forum.serverless.com
 
  Your Environment Information ---------------------------
     Operating System:          win32
     Node Version:              10.15.0
     Framework Version:         1.53.0
     Plugin Version:            3.1.1
     SDK Version:               2.1.1
     Components Core Version:   1.1.1
     Components CLI Version:    1.2.3
 

Process finished with exit code 1
 


```  