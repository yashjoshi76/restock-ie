# restock-ie
Python script to automate daily check up for a specific item on a local electronic store website

Technologies:
Python 3.9
BeautifulSoup 4.10
Twilio 7.4
AWS Lambda
AWS EventBridge

Steps to run the program:

Get a Twilio account and an AWS account
Get your Twilio Account SID and Auth Token
Modify the starter code in Python:
Include your Account SID and Auth Token
Replace from_ and to variables with your Twilio number and recipient number
Create a new function in AWS Lambda with a runtime of Python 3.9
Create a deployment package:
Put your script and all dependencies in a folder
Zip the folder into a .zip file
Upload the deployment package to an S3 bucket
Connect the Lambda function to the S3 bucket
Set up an EventBridge rule to trigger the function on a schedule using a Cron expression
Check that the rule is enabled and running successfully.
