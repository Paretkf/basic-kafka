# Basic Kafka
- massage queue
- ทำ scaling ได้

Producer
- add message ลงใน queue


consumer
- retrieve

Broker
- server แต่ละตัว

Topic
- หัวข้อที่ Producer 

Partition
- แบ่ง topic ออกเป็นส่วนๆ
- เราสามารถมี consumer ได้มากที่สุดเท่ากับจำนวน partition
- อยากให้มีหลายๆ consumer ในการทำงาน pararial กัน

Zoo keeper
- kafka จะไปใช้งาน zookeeper

kafkacat
- terminal ที่ใช้ access kafka