# i2icell    
Java, kafka, hazelcast, oracle database, voltdb, log4j, kryo serializer

(Part of i2i Systems internship project.)
(More info : https://github.com/oktayxpolat/i2i_Intern_2021_Project )



## ALERT SENDER
* Get msisdn and partition key info from Hazelcast
* Get subscriber info from Oracle database to get packet limit
* Generate random usage according to packet id and limit
* Produce subscriber and updated used amount info with Kryo serializer into Kafka


## OCS
* Get balance list of subscribers from Voltdb
* Get updated used amount info with Kryo deserializer from Kafka
* Update balance list of subscriber in Voltdb
