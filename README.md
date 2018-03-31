# Wild Rydes Website Frontend
[![Serverless](http://public.serverless.com/badges/v3.svg)](http://www.serverless.com)
[![License](https://img.shields.io/badge/License-BSD%202--Clause-orange.svg)](https://opensource.org/licenses/BSD-2-Clause)
[![Build Status](https://travis-ci.org/ServerlessOpsIO/wild-rydes-website.svg?branch=master)](https://travis-ci.org/ServerlessOpsIO/wild-rydes-website)

Creates a static website on AWS S3.

## Resources

This will create:
* S3 Bucket
* S3 Bucket Policy
* Route53 Record

## Outputs

__StaticSiteS3BucketName:__ Name of S3 bucket.

__StaticSiteS3BucketDomainName:__ Domain under which website resides.

__StaticSiteS3BucketWebsiteURL:__ URL of the static website.
