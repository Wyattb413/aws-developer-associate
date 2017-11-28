# AWS Certified Developer Associate Notes

[**Udemy Course Link**](https://www.udemy.com/aws-certified-developer-associate/learn/v4/overview) - https://www.udemy.com/aws-certified-developer-associate/learn/v4/overview

[**AWS Console Link**](https://us-west-2.console.aws.amazon.com/console/home?region=us-west-2) - https://us-west-2.console.aws.amazon.com/console/home?region=us-west-2

## Table of Contents

Lecture Topic | Link
--- | ---
**SECTION 2** | [**Section 2**](#section-2)
10,000 Foot Overview | [Lecture 8](#section-2-lecture-8)

<!-- ################################################################################################################ -->
<!--                                                     SECTION 2                                                    -->
<!-- ################################################################################################################ -->

## SECTION 2

### Section 2 Lecture 8

- **Region** - A region is a geographical area consisting of 2 (or more) *Availability Zones*
- **Availability Zone (AZ)** - A data center (could comprise of multiple data centers)
- **Edge Locations** - CDN end points for CloudFront

#### Networking and Content Delivery

- **Virtual Private Cloud (VPC)** - Virtual data center, can have multiple VPCs per region, and can even connect one VPC to another
- **Route 53** - Amazon's DNS Service (***Amazon Fun Fact: Route 53 is named after the U.S. highway *Route 66*, with 53 pertaining to the port number opened when opening up DNS to the world)
- **Clound Front** - Consists of *Edge Locations** for CDNs
- **Direct Connect** - A way of connecting physical data centers to AWS through dedicated telephone line (does not transmit over internet)

#### Compute

- **Elastic Compute Cloud (EC2)** - Virtual machines in the cloud
- **Elastic Compute Cloud Container Service** - Highly scalable, high performing *mangement service* that supports *Docker* containers - allows you to run applications on a managed cluster of *EC2 instances*
- **Elastic Beanstalk** - upload your code and *Elastic Beanstalk* automatically handles the deployment, from capacity provisioning, load balancing, auto-scaling to application health monitoring
- **Lambda** - Like an *EC2 instance*, but is *server-less*, it lets you run code without provisioning or managing servers
- **Lightsail** - Out-of-the-box cloud project that bundles AWS services with little setup required