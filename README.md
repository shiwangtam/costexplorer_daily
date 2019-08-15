# AWS Daily Cost Report Generator

Deployment steps

1. Go to Cloudformation, create stack, upload a template to Amazon S3 using deploy.yaml file

2. Go to SES and validate customer's email address as sender

3. Upload lambda code to existing lambda.py

4. Wait for email with attachment name "cost explorer report"
