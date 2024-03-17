# AWS - src

## LINKEDIN Prepare for the AWS Certified Solutions Architect - Associate (SAA-C03) Certification

### +AWS Certified Solutions Architect - Associate (SAA-C03) Cert Prep: 1 Cloud Services Overview

### +AWS Certified Solutions Architect - Associate (SAA-C03) Cert Prep: 2 Storage Design

<details>
<summary>1. Storage Services </summary>

# Storage Services

AWS offers a variety of storage services, requiring understanding to choose the right ones.

- Simple Storage Service (S3)
- Glacier
- CloudFront
- Elastic Block Store (EBS)
- The Storage Gateway 
- The Snow Family
- Databases

## Simple Storage Service (S3)

- Simple Storage Service (S3) is a primary service for general storage needs.
- It was one of the first storage services that Amazon ever offered with AWS.
- File storage, akin to S3 object storage, deals with objects or chunks of information.

## Glacier

- Glacier is suitable for archiving large amounts of data not frequently accessed.
- Glacier is for that archival data, someplace to put a large amount of data that you want to keep for a long time, but you're not necessarily worried about accessing it frequently or instantly.

## CloudFront

- CloudFront optimizes content delivery by caching data near users.
- CloudFront is about getting the stuff close to your users.
- It is simply making sure that web information, this kind of data that's accessed frequently by your website visitors, is cached at an Edge location that's near the customer.

## Elastic Block Store (EBS)

- Elastic Block Store (EBS) provides fast block-level access for instances.
- Block storage, used with EBS, offers data access similar to local hard drives.
- Elastic Block Store is the best storage solution to use for your instances when you want those instances to have very fast block-level access rather than object-level access. S3 is object level.
- It's used on local networks all the time. We use it with ISCSI; internet SCSI, or Fiber channel, et cetera. These are done to connect to storage area networks usually.
- Basically, what we're doing is, across the network, being able to get access to data in a similar way we do to local hard drives.
- AWS can use block storage with virtual machines within the AWS Cloud when you use Elastic Block Store, or EBS.

## The Storage Gateway 

- The Storage Gateway enables accessing cloud storage as if it's local.
- It is basically an appliance that you put on your local network, either a software appliance or a hardware appliance, that acts as a VPN connection into the Amazon Cloud so that you can access your storage as if it's local storage.

## The Snow Family

- The Snow Family assists in migrating massive data to the cloud.
- It is a collection of really three primary products that can be used in order to migrate data from your local data stores into the cloud when you have massive amounts of data that you need to move.

## Databases

- Databases also serve as storage solutions.

# Factors to consider when choosing a Storage Service:

- Consider factors like size, performance, and cost when selecting a storage service.
- Performance includes both access speed and the time it takes for data retrieval.
- Balance performance requirements with cost considerations; Glacier offers cost savings but delayed access.
- Choose storage services based on the urgency of data access and budget constraints.

# #END</details>

<details>
<summary>2. D </summary>

# D

```x

```

```x

```

```x

```

```x

```

```x

```

```x

```

```x

```

# #END</details>
