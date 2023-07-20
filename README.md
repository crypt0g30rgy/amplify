# Amplify BugBounty React Test App

## Installation

> clone this repo locally

> install dependencies via `npm install`

## Prerequisites

> you need a file called `aws-exports.js`

> should be in the format like in below example;

```javascript
/* eslint-disable */
// WARNING: DO NOT EDIT. This file is automatically generated by AWS Amplify. It will be overwritten.

const awsmobile = {
    "aws_project_region": "eu-west-1",
    "aws_appsync_graphqlEndpoint": "https://12g21gasjt7iat823gki.appsync-api.eu-west-1.amazonaws.com/graphql",
    "aws_appsync_region": "eu-west-1",
    "aws_appsync_authenticationType": "AWS_LAMBDA",
    "aws_cognito_identity_pool_id": "eu-west-1:c62badbsg-15lo-8596-78fa-88f347921251",
    "aws_cognito_region": "eu-west-1",
    "aws_user_pools_id": "eu-west-1_AHGjgjy6ay8",
    "aws_user_pools_web_client_id": "827186182Akjhskasgkhgjksdagl",
    "oauth": {},
    "aws_cognito_username_attributes": [],
    "aws_cognito_social_providers": [],
    "aws_cognito_signup_attributes": [
        "EMAIL"
    ],
    "aws_cognito_mfa_configuration": "OFF",
    "aws_cognito_mfa_types": [
        "SMS"
    ],
    "aws_cognito_password_protection_settings": {
        "passwordPolicyMinLength": 8,
        "passwordPolicyCharacters": []
    },
    "aws_cognito_verification_mechanisms": [
        "EMAIL"
    ],
    "aws_user_files_s3_bucket": "user-files-prod",
    "aws_user_files_s3_bucket_region": "eu-west-1"
};


export default awsmobile;

```

## Run

> do `npm start`