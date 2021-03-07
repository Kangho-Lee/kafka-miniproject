> # kafka-miniproject
# Udemy Kafka mini project

* 기본적인 Kafka의 Producer, Consumer 실습 프로젝트

(1) kafka-basics
* Producer
  - ProducerDemo.java : 기본적인 Kafka Producer 실습
  - ProducerDemoKeys.java : Key 값을 가지고 Kafka Producer 실습
  - ProducerDemoWithCallback.java : Callback 방식을 이용한 kafka Producer 실습
* Consumer
  - ConsumerDemo.java : 기본적인 Kafka Consumer 실습 
  - ConsumerDemoGroups.java : 기본적인 Kafka Consumer Groups 실습
  - ConsumerDemoWithThread.java : Thread 방식을 이용한 Kafka Consumer 실습
  - ConsumerDemoAssignSeek.java : Assign, Seek 방식을 이용하여 특정 Partition을 지정하여 Consume 실습
  
 
(2) kafka-producer-twitter
* Twitter Client API (Producer) - Kafka - Elasticsearch (Consumer) 프로젝트 실습 (a)
  - TwitterProducer.java : TwitterClient를 활용해 찾고자 하는 키워드에 해당하는 Twitter Data 값들을 Kafka에 넣는 실습
 
 
(3) kafka-consumer-elasticsearch
* Twitter Client API (Producer) - Kafka - Elasticsearch (Consumer) 프로젝트 실습 (b)
  - ElasticSearchConsumer.java : Kafka Twitter Topic 에 있는 값을 ElasticSearch(BonSai) 에 넣는 실습 
  
  
(4) kafka-connect
* kafka-connect-twitter 활용하여, target-sink 실습 (https://github.com/jcustenborder/kafka-connect-twitter)
  - connect-standalone.properties, twitter.properties, run.sh
   
   
(5) kafka-streams-filter-tweets
* Kafka Stream 활용하여 (요건에 따른) 특정 데이터 정제작업을 거쳐 데이터처리 실습
  - StreamsFilterTweets.java
