---
title: "B"
subtitle: ""
date: 2022-04-11T13:47:25+08:00
draft: false
authors: [蒋硕]
tags: []
categories: []
series: []
---

import boto3


s3 = boto3.resource(
    's3',
    aws_access_key_id='430d1cf4bd5b4d0bb85ec3c479ed9669',
    aws_secret_access_key='fc7a7ae20e1445e78211e2dfd2706bb4eb20035170e34b40a12d4c3ce3c34bbf',
    region_name='us-west-2',
    endpoint_url='https://stdcdn.com'
)
its location is ~/.aws/credentials. At a minimum, the credentials file should specify the access key and secr