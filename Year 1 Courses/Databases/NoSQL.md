# NoSQL
was originally defeind to be literally "No SQL", but now often refers to "Not Only SQL". They often aim to be non-relational, distributed, open-source and horizontally scalable. These properties are particularly useful in the internet-age.

## Why distribute data?
**Scalability**. The data set can be too large for a single machine. Data often resides in RAM rather than secondary storage.
**Fault tolerance**. The service can survive failure of some machines.
**Lower latency**: Data can be stored closer to where it is used.

## How do we distribute the data?
Using replication, where each machine has an exact copy of the data, or partitioning it where each machine holds a portion of the data. 

## Distributed databases cause issues for CAP concepts

### Consistency
All reads return data that is up-to-date.

### Availability
All clients can find some replica of the data.

### Partition tolerance
The system continues to operate despite arbitrary message loss or failure of part of the system.