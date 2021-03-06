# Installing the AWS CLI<a name="cli-chap-install"></a>

The AWS Command Line Interface is available in two versions\.

## AWS CLI version 2<a name="cli-chap-install-v2"></a>

**Preview Evaluation Software**  
AWS CLI version 2 is provided as a preview for testing and evaluation\. At this time, we do not recommend using it in a production environment\. For production environments, we recommend that you use the generally available version 1\.  
We welcome feedback for this developer preview of AWS CLI version 2 in the [AWS CLI version 2 GitHub repo](https://github.com/aws/aws-cli/issues?q=is%3Aopen+is\%3Aissue+label%3Av2)\. Be sure to specify "\[V2\]" in the title of your issue\.

AWS CLI version 2 is the most recent major version of the AWS CLI and supports all of the latest features\. Some features introduced in version 2 are not backward compatible with version 1 and you must upgrade to access those features\.

AWS CLI version 2 is available to install only as a bundled installer\. Although you might find it in some package managers, these are not produced or managed by AWS and are therefore not official and not supported by AWS\. We recommend that you install the AWS CLI from only the official AWS distribution points, as documented in this guide\.

For information about how to install AWS CLI version 2, see [Installing the AWS CLI version 2](install-cliv2.md)\.

## AWS CLI version 1<a name="cli-chap-install-v1"></a>

AWS CLI version 1 is the original AWS CLI, and we continue to support it\. However, major new features that are introduced in AWS CLI version 2 might not be backported to AWS CLI version 1\. To use those features, you must install AWS CLI version 2\.

For information about how to install AWS CLI version 1, see [Installing the AWS CLI version 1](install-cliv1.md)\.

## Migrating from AWS CLI version 1 to version 2<a name="migrating"></a>

If you ran commands or scripts with AWS CLI version 1 and you are considering migrating to AWS CLI version 2, see [Breaking Changes – Migrating from AWS CLI version 1 to version 2](cliv2-migration.md) for a description of the changes that you should know about\.