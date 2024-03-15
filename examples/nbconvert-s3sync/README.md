# Cast to S3 bucket

This is one of the simplest options to automatically bring your notebooks online.  All you need is an S3 bucket.

An S3 bucket configured for hosting static websites is a "serveless webserver" that can work as your website.  S3 is mostly commonly presumed to mean "Amazon Web Services" because AWS pioneered the cloud storage concept, but it doesn't have to be AWS.  Today, many other providers offer S3-compatible storage, and are usually cheaper than AWS.  "S3-compatible" means that most of your `awscli` and `boto3` commands can be expected to work the same.
