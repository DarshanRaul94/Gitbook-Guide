# AWS CDK - python

## Why AWS CDK:

 _AWS Cloud Development Kit \(AWS CDK\) :_

So Cloudformation does still have two disadvantages over terraform 

1. Closed Source
2. AWS provider native

> But the biggest disadvantaqe of not actually being  Infrastructure as CODE and state management. That's gone for good thanks to AWS CDK.

You can use the AWS CDK to define your cloud resources in a familiar programming language. The AWS CDK supports TypeScript, JavaScript, and Python.

#### Advantages of AWS CDK:

* AWS CDK is **open source**
* Use logic \(if statements, for-loops, etc\) **FINALLY!!**
* object-oriented techniques to create a model of your system
* Organize your project into logical modules
* Share and reuse your infrastructure as a library
* Use your existing **code review workflow**
* State management \( **diff** against a deployed stack to understand the impact of a code change\)

> There is no charge for using the AWS CDK, however you might incur AWS charges forcreating or using AWS [chargeable resources](http://docs.aws.amazon.com/general/latest/gr/glos-chap.html#chargeable-resources)

## Prerequisites:

> The AWS CDK is developed in TypeScript and transpiled to JavaScript. Bindings for the other supported languages make use of the AWS CDK back-end running on Node.js

* [Node.js \(&gt;= 8.11.x\)](https://nodejs.org/en/download)
* You must specify both your credentials and an AWS Region to use the AWS CDK CLI

## Installation and Configuration needed

### Installation

First install the aws-cdk package

`npm install -g aws-cdk`

Then check the cdk version with:

```text
cdk --version
```

### AWS Configuration:

The CDK looks for credentials and region in the following order:

* Using the **--profile** option to **cdk** commands.
* Using environment variables.
* Using the default profile as set by the AWS Command Line Interface \(AWS CLI\)

## concepts

## practical:

1. Initialize a python cdk app

```text
cdk init --language python
```

2. Create a virtual environment

```text
python3 -m venv .env
source .env/bin/activate
```

3. Install all the packages

```text
pip install -r requirements.txt
```

This would be the initial folder structure:

![](../../../.gitbook/assets/image%20%2867%29.png)


