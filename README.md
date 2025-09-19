# Learn Jenkins App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### Jenkins Config
- Install plugin :  stage view , docker pipeline, html publisher

### AWS Config
- Add bucket into AWS
- Disable static block access
- Add policy S3

{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Sid": "Statement2",
            "Effect": "Allow",
            "Principal": "*",
            "Action": "s3:GetObject",
            "Resource": "arn:aws:s3:::koman-jenkins/*"
        }
    ]
}

### NETLIFY Config

