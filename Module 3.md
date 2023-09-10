# Cloud Infrastructure 
is the foundation of the cloud.
Multiple regions --> Availability Zones (AZ)

![image](https://github.com/syash7202/Introduction-to-Cloud-Computing/assets/66427456/3cd64e90-3921-4dc5-ba71-0466741527a0)

## Computing Resources 
- Virtual servers: software-based
- Bare-metal servers: physical servers
- Serverless: abstraction

## Virtual Machines (VM)
![image](https://github.com/syash7202/Introduction-to-Cloud-Computing/assets/66427456/87813a7c-6f23-4d4f-80dc-979802553d32)
![image](https://github.com/syash7202/Introduction-to-Cloud-Computing/assets/66427456/6aa24bec-8ef2-4223-8ce8-d27f26075d0f)
![image](https://github.com/syash7202/Introduction-to-Cloud-Computing/assets/66427456/3f118b9c-4411-466e-ba90-74c00e124968)
![image](https://github.com/syash7202/Introduction-to-Cloud-Computing/assets/66427456/5b9dec26-2e8c-4117-aa55-83692c5a954c)

## Bare-Metal Servers
is a single-tenant, dedicated physical server. In other words, it's dedicated to a single customer.

![image](https://github.com/syash7202/Introduction-to-Cloud-Computing/assets/66427456/324eed0c-4a99-449f-863b-5ed8eb4aeffa)

### Workloads (suitable for)
- Fully customizable/ demanding environments
- Dedicated or long-term usage
- High-performance computing 
- Highly secure/isolated environments.

![image](https://github.com/syash7202/Introduction-to-Cloud-Computing/assets/66427456/20dbd1b0-dbe3-469d-b500-86b36d2b9822)


## Bare-metal VS Virtual Machines
![image](https://github.com/syash7202/Introduction-to-Cloud-Computing/assets/66427456/3289b7c1-5fdf-412a-8d49-f1b0a224ea68)

# Secure Networking in the Cloud 
![image](https://github.com/syash7202/Introduction-to-Cloud-Computing/assets/66427456/0e9483f2-8af5-4786-b12d-703f1cfca133)

**Networking capabilities** in the cloud are delivered as a service rather than in the form of rack-mounted devices. Cloud resources such as VMs (or VSIs), storage, network connectivity, and load balancers are deployed into subnets within Virtual Private Clouds (VPCs). Using private and public subnets allows users to deploy multi-tier enterprise applications securely. Load balancers distribute the traffic and allow applications to be responsive.

# Containers
Containers are executable units of software in which application code is packaged, along with its libraries and dependencies, in common ways so that it can be run anywhere, whether it be on a desktop, traditional IT, or the cloud.
Containers are small, fast, and portable, and unlike virtual machines, they do not need to include a guest OS in every instance and can, instead, simply leverage the features and resources of the host OS.
Containers streamline the development and deployment of Cloud Native applications.

# Cloud Storage
Cloud storage is where you save data files in the cloud.
Certain storage must be attached to a compute node before the storage can be accessed, whereas other storage types can be directly accessed either through the public Internet or a dedicated private network connection.
Cloud providers host, secure, manage, and maintain the cloud storage and associated infrastructure to ensure you have access to your data when you need it.
Cloud storage services allow you to scale your capacity as you need so you only pay for what you provision, usually on a ‘per gigabyte’ basis.
The cost of storage will vary by type but in general,
The faster the read / write speed of the storage, the higher the per-gigabyte cost.

## Direct Attached Storage
sometimes referred to as "Local storage", is storage that is presented directly to a cloud-based server and is effectively either within the host server chassis or within the same rack.
This storage is fast and normally only used to store a server’s operating system, although it can have other use cases.
![image](https://github.com/syash7202/Introduction-to-Cloud-Computing/assets/66427456/aee8f942-0e5b-4192-a635-b384cea06adf)

## File Storage
attached to a computer node to store data via ethernet network (NFS), less expensive, and more resilient to failure. It has less disk management and 7 maintenance. Provision large amounts of file storage. It is managed by the service provider.
![image](https://github.com/syash7202/Introduction-to-Cloud-Computing/assets/66427456/4f685c82-e356-4d0e-8167-cd835da285b3)

## Block Storage
Block storage breaks files into chunks (or blocks) of data and Stores each block separately under a unique address. Like direct attached storage and file storage, block storage also must be attached to a compute
node before it can be utilized for your workloads.
Block storage, like file storage, can be mounted from remote storage appliances, making it extremely resilient to failure, and keeping data far more secure in them, on account of encryption in transit, and encryption at rest services, available on these appliances.
Block storage is mounted as a volume to compute nodes using a dedicated network of fibers,
through which signals move at the speed of light.

![image](https://github.com/syash7202/Introduction-to-Cloud-Computing/assets/66427456/eee59189-7245-4eb5-be61-1cef8bb3b43d)

## Object Storage
![image](https://github.com/syash7202/Introduction-to-Cloud-Computing/assets/66427456/d486e040-e4ee-4dfe-94a6-82f8666099b7)

# Object Tiers & APIs
Buckets > Tiers & classes
These tiers are based on how frequently the data is accessed.
- Standard tier: store objects that are frequently accessed, highest per GB cost.
- Vault / Archive tier: store objects that are accessed once or twice per month, low storage cost 
- Cold vault tier: store data that is accessed only once or twice a year, costing just a fraction of US cents per GB per month. 

 **One can set automatic archiving rules: if data is not accessed for a particular time it shifts to lower-costing storage facilities.** 

![image](https://github.com/syash7202/Introduction-to-Cloud-Computing/assets/66427456/ac8e5868-0f4e-4a94-ba5d-345eb0164cea)

# Content Delivery Networks (CDN)
A content delivery network, or CDN, is a distributed server network that delivers temporarily stored, or cached, copies of website content to users, based on the user's geographic location. 
A CDN stores this content in distributed locations and reduces the distance between your website visitors, and your website server.

