# Concepts to know

* Vertical vs horizontal scaling
https://github.com/vaquarkhan/vaquarkhan/wiki/Difference-between-scaling-horizontally-and-vertically
Horizontal Scaling - 
Staying below the ceiling using cheaper hardware.
Rather than getting few good machines get large number of mediocre machines.
  Load Balancing - The traffic from user is distributed/balanced accross variuos servers. Return public IP addresses of the load balancer and the servers can trasfer data to load balancer. So the balancer will have a public IP address and servers will have private IP addresses.
  Decides to whome this request is sent to (depending on factors). In this case all servers are identical and it does not matter whome you send the request.
  But the downside is the disk space.
  Alternatives to Load Balancing - Have dedicated severs.
                                   Distribute servers using Round Robin. (kind of what google does)
                                   But it may happen some server might get a very heavy task. (caching)
                                   
                                   
* CAP theorem
* ACID vs BASE
Partitioning/Sharding 
Consistent Hashing
Optimistic vs pessimistic locking
Strong vs eventual consistency
RelationalDB vs NoSQL
Types of NoSQL
     Key value
     Wide column
     Document-based
     Graph-based
Caching
Data center/racks/hosts
CPU/memory/Hard drives/Network bandwidth
Random vs sequential read/writes to disk
HTTP vs http2 vs WebSocket
TCP/IP model
ipv4 vs ipv6
TCP vs UDP
DNS lookup
Http & TLS
Public key infrastructure and certificate authority(CA)
Symmetric vs asymmetric encryption
Load Balancer
CDNs & Edges
Bloom filters and Count-Min sketch
Paxos 
Leader election
Design patterns and Object-oriented design
Virtual machines and containers
Pub-sub architecture 
MapReduce
Multithreading, locks, synchronization, CAS(compare and set)

Tools
Cassandra
MongoDB/Couchbase
Mysql
Memcached
Redis
Zookeeper
Kafka
NGINX
HAProxy
Solr, Elastic search
Amazon S3
Docker, Kubernetes, Mesos
Hadoop/Spark and HDFS
