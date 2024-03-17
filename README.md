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
- With file storage, we're dealing with objects, or chunks of information.
- AWS uses something similar to file storage with S3 called object storage, so they treat a file like an object.
- File storage is used all the time on our local networks with NAS devices. So, if you've ever connected a network-attached-storage device to your network, even at home, and you put files on there, you are using file-based storage.
- Now, within that NAS device, you don't actually access it at the allocation vector level, or the block or sector level. Instead, you're dealing with it as a file, or in S3 terminology, as an object.

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
<summary>2. S3 Storage Class Overview </summary>

# S3 Storage Class Overview

- S3 is an AWS storage service focused on object storage.
- Objects are stored within buckets, which can hold files or any data chunks.
- Objects are automatically distributed across at least three Availability Zones for redundancy, except for the 1A class which uses only one zone for lower cost but reduced availability.
- S3 supports encryption and automatic data classification.
- Data classification aids in security and management tasks such as moving data to Glacier based on usage patterns.
- AWS enables direct big data analytics against data stored in S3 buckets without the need for database migration.
- S3 primarily offers object storage, not file storage.
- Different classes of S3 storage provide varying levels of availability and cost.
- Choose the appropriate method for data ingestion based on requirements and constraints.

# Getting Data into S3

## AWS APIs

- AWS APIs allow direct integration into applications for uploading data.

## Amazon Direct Connect

- Amazon Direct Connect establishes VPN connections for data transfer.

## Storage Gateway

- Storage Gateway synchronizes or replicates local data with S3.

## Kinesis Firehose

- Kinesis Firehose facilitates analytical data transfer to S3.

## Transfer Acceleration

- Transfer Acceleration speeds up data uploads globally but at increased cost.

## The Snow Family

- Snowball, Snowball Edge, and Snowmobile offer scalable solutions for data migration.
- Snowmobile is a large trailer capable of storing exabytes of data.
- Snowball Edge can run instances for analytics on-premises before transferring data to AWS.

![image](https://github.com/omeatai/src-aws/assets/32337103/74d73bd8-81bc-4d21-a445-4d92d99aac10)

# #END</details>

<details>
<summary>3. S3 Terminology </summary>

# S3 Terminology

- Buckets: Containers for storing objects in S3, with a default limit per AWS account.
- Regions: Geographic locations where buckets are created, affecting data accessibility and latency.
- Objects: Data stored within buckets, similar to files, but can also include structured data.
- Keys: Logical names of objects within buckets, analogous to file names.
- Object URLs: Unique URLs assigned to each object for internet access.
- Eventual Consistency: Objects may take some time to replicate across availability zones, leading to eventual consistency.
- Static Website Hosting: S3 is suitable for hosting static websites due to quick access and URL accessibility.

# S3 Operations:
- Creating and deleting buckets.
- Writing, reading, and deleting objects.
- Managing object properties.
- Listing keys in buckets.
 
# REST Interface (API):
- Represents S3's API for programming access.
- Utilizes CRUD operations (Create, Read, Update, Delete) mapped to HTTP methods (PUT, POST, GET, DELETE).
- Important for developers but less emphasized in architect or designer certifications.

# #END</details>

<details>
<summary>4. S3 Advanced Features </summary>

# S3 Advanced Features

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
