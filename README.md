# lambda-hugo

lambda-hugo is a simple AWS Lambda Layer to add Hugo support to a Lambda function. It should work in any runtime.

## Usage
1. Add the Hugo layer to your function. Refer to the [AWS Layer Documentation](https://docs.aws.amazon.com/lambda/latest/dg/configuration-layers.html) for more details. Use the ARN from the table at the bottom of this README for ARNs.
2. Execute the Hugo binary from `/opt/bin/hugo`.


| Hugo version |  ARN |
| --- | --- |
| 0.53 |  `arn:aws:lambda:us-east-2:804798220069:layer:hugoLayer:1` |
