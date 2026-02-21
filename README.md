# Simple AWS Elastic Beanstalk Project

This is a basic Flask application deployed on **AWS Elastic Beanstalk** for learning purposes.

## How to Deploy

1. Install AWS EB CLI:
   ```bash
   pip install awsebcli
Initialize Elastic Beanstalk environment:

eb init -p python-3.11 simple-ebs-project
eb create simple-ebs-env
Deploy the app:

eb deploy
Open the app in a browser:

eb open
Notes
This project is intentionally simple to understand Elastic Beanstalk workflows.

Next step: Scale to more complex projects with databases and APIs.
