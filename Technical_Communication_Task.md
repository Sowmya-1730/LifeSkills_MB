# You joined a new project. The project is going through some performance and scaling issues. After some analysis, the team lead asks you to investigate possibly using a NoSQL database will improve performance. Investigate at least 5 NoSQL databases and why they are used

##### The top most NoSQL databases that we can use for real-time applications are MongoDB, Apache Cassandra, Redis, Amazon DynamoDB and Neo4j

### 1. MongoDB (Document-based Database)
MongoDB is a document-oriented  NoSQL database which stores data in JSON format.
**Key Features:**
- Schema-less data model
- Supports indexing and aggregation
- Horizontal scaling using sharding 

### 2. Apache Cassandra (Wide-column Database)
Apache Cassandra is a distribured NoSQL database designed to handle large-scale data across multiple servers.
**Key Features:**
- Peer-to-Peer
- High fault tolerance
- Optimized for write-heavy workloads

### 3. Redis (Key-Value Database)
Redis is a in-memory NoSQL database known for it's extreme fast performance. And it also supports multiple data structures.
**Key Features:**
- Very low latency
- Supports data persistence
- Rich data structures (lists, sets, hashes)

### 4. Amazon DynamoDB (Managed NoSQL Service)
Amazon DynamoDB service is fully provided by AWS. It was like combination of MongoDB and Redis by supporting both key-value and data models.
**Key Features:**
- Automatic scaling
- Fully managed
- Integration with AWS ecosystem

### 5. Neo4j (Graph Database)
Neo4j is a graph-based NoSQL database like RDBMS which is best for relationships.
**Key Features:**
- Efficient relationship queries
- ACID compliance
- Uses Cypher query language

In which cases, we need to use each type of NoSQL for best performance and along with their strength
- MongoDB: Its strength is flexible schema and it was best to use for web & content apps
- Apache Cassandra: Its strength is high availability and it was best to use at the time if we need to store big data and having distributed systems
- Redis: Its strength is having ultra-fast performance and it was best if we want to maintain caching and for real-time systems.
- Amazon DynamoDB: Managed & scalable are the strengths because of AWS. It can be used when we deal with cloud-based applicatoins
- Neo4j: Relationship handling is the strength of Neo4j and it can be used if we need to maintain data systems in connected.

### References
- [MongoDB NoSQL Explained](https://www.mongodb.com/nosql-explained)  
- [MongoDB Wikipedia](https://en.wikipedia.org/wiki/MongoDB)  
- [Apache Cassandra Wikipedia](https://en.wikipedia.org/wiki/Apache_Cassandra)  
- [Redis Wikipedia](https://en.wikipedia.org/wiki/Redis)  
- [Amazon DynamoDB Wikipedia](https://en.wikipedia.org/wiki/Amazon_DynamoDB)  
- [Neo4j Wikipedia](https://en.wikipedia.org/wiki/Neo4j)  
