ssm\_agent cookbook
===================

Description
-----------

A simple cookbook to download and install the [Amazon EC2 Systems Manager](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/systems-manager.html) agent.

About Systems Manager
---------------------

Amazon EC2 Systems Manager is a collection of capabilities that helps you automate management tasks such as collecting system inventory, applying operating system (OS) patches, automating the creation of Amazon Machine Images (AMIs), and configuring operating systems (OSs) and applications at scale. Systems Manager works with managed instances: Amazon EC2 instances, or servers and virtual machines (VMs) in your on-premises environment that are configured for Systems Manager.

Usage
-----

Include the default recipe.

```
include_recipe 'ssm_agent::default'
```
