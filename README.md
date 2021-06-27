# learning-kafka

#### Kafka basics and terminology 

* A single node/machine is called broker
* A cluster is a group of brokers
* Topic is interface to send messages
* A Topic can be divided into partitions. Partitions can be placed same on same broker or can be distributed among the cluster
* Each partition can replicated on multiple broker nodes

##### Kafka producer

* It builds a ProducerRecord for a message
* The ProducerRecord is seralized and sent to partitioner 
* Messages are usually bundled together and sent in a batch 
