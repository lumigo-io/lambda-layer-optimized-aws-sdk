# lambda-layer-optimized-aws-sdk

[![Greenkeeper badge](https://badges.greenkeeper.io/lumigo/lambda-layer-optimized-aws-sdk.svg)](https://greenkeeper.io/)

A Lambda layer that gives you an AWS SDK with HTTP keep-alive enabled already.

You can add this layer to your function using one of the following ARNs (pick the one from the region you need):

* **arn:aws:lambda:us-east-1:374852340823:layer:optimized-aws-sdk:[insert version here]**
* **arn:aws:lambda:us-west-2:374852340823:layer:optimized-aws-sdk:[insert version here]**
* **arn:aws:lambda:eu-central-1:374852340823:layer:optimized-aws-sdk:[insert version here]**
* **arn:aws:lambda:eu-west-1:374852340823:layer:optimized-aws-sdk:[insert version here]**

The latest version of this layer is **10**.

## Getting started

You can add this layer to your project using the Serverless framework:
![](/docs/images/sls-example.png)

Or with SAM:
![](/docs/images/sam-example.png)

Or add it via the console manually:
![](/docs/images/console-example.png)

## Version mapping

| layer version | AWS SDK version |
|---|---|
| 9 | 2.458.0 |
| 10 | 2.471.0 |
