# What is Hadoop?

- Apache Hadoop is an open source framework that is used to efficiently store and process large datasets ranging in size from gigabytes to petabytes of data.

- Instead of using one large computer to store and process the data, Hadoop allows clustering multiple computers to analyze massive datasets in parallel more quickly.

## Four main modules

- **Hadoop Distributed File System(HDFS)**: a distributed file system that runs on standard or low-ebd hardware. HDFS provides betteer data throughput than traditional file systems, in addition to high fault tolerance and native support of large datasets.
- **Yet Another Resource Negotiator(YARN)**: manages and monitors cluster nodes and resource usage.
- **MapReduce**: A framework that helps programs do the parallel computation on data. The map task takes input data and converts it into a dataset that can be computed in key value pairs. The output of map task is consumed by reduce task to aggregate output and provide the desired result.
- **Hadoop Common**: provides common Java libraries that can be used across all modules
