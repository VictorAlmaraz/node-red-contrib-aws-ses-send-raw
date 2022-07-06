# A simple node that sends raw e-mails with AWS Simple Email Service.

This node is based on [node-red-contrib-aws-ses-send](https://github.com/danielterra/node-red-contrib-aws-ses-send)

## Pre-requisites
1. You need to have a account on AWS and create a programatic access user on IAM with permission to send e-mail with AWS Simple Email Service.
2. You need to follow the steps to configure the SES with a verified domain to send emails.

## Configure the node
Double click the node and fill all fields

## Payload
It expects a payload with a RFC-2822 compliant MIME message

## Return
It returns an Object with the Id of the email sended

```
{
    "ResponseMetadata":{
        "RequestId":"d05b47cf-0ee2-413f-b06b-fe981fbfed1b"
    },
    "MessageId":"0101017599fe549f-64676c3d-8dda-478b-9765-228d49de341c-000000"
}
```
    