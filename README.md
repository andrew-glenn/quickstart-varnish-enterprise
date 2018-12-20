# quickstart-varnish-enterprise
## Varnish on the AWS Cloud


This Quick Start deploys Varnish Cache Plus (VCP) on the AWS Cloud in about 30 minutes.

VCP is the commercial enterprise version of the open-source HTTP engine and reverse HTTP proxy, Varnish Cache (VC). Both versions of Varnish speed up a website by caching (storing) a copy of a page served by your web server the first time a user visits your page. The next time the user requests the same page, the cache will serve the copy quickly, instead of requesting the page from the web server again. VCP provides usability improvements and performance enhancements over VC.

This Quick Start deploys VCP into a Multi-AZ configuration on AWS with asynchronous caching data replication between Availability Zones. The Quick Start uses Ubuntu Linux as the operating system for the VCP instances.

The Quick Start offers two deployment options:

- Deploying VCP into a new virtual private cloud (VPC) on AWS
- Deploying VCP into an existing VPC on AWS

You can also use the AWS CloudFormation templates as a starting point for your own implementation.

![Quick Start architecture for VCP on AWS](https://d0.awsstatic.com/partner-network/QuickStart/datasheets/varnish-architecture-diagram.png)

For architectural details, best practices, step-by-step instructions, and customization options, see the 
[deployment guide](https://fwd.aws/av3ER).

To post feedback, submit feature ideas, or report bugs, use the **Issues** section of this GitHub repo.
If you'd like to submit code for this Quick Start, please review the [AWS Quick Start Contributor's Kit](https://aws-quickstart.github.io/). 

