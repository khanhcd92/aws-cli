# aws-cli

#### 1. Install AWS CLI
pip install awscli

#### 2. Config Named Profiles
Refer: https://docs.aws.amazon.com/cli/latest/userguide/cli-multiple-profiles.html

#### 3. Sending Personalized Email Using the Amazon SES API

aws ses create-template --cli-input-json file://<template_email>.json --profile <profile_name> --region <region_ses>

aws ses update-template --cli-input-json file://<template_email>.json --profile <profile_name> --region <region_ses>

Refer:
https://docs.aws.amazon.com/ses/latest/DeveloperGuide/send-personalized-email-api.html#send-personalized-email-create-template
