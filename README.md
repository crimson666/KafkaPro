to run local kafka -> .\bin\windows\kafka-server-start.bat .\config\server.properties
 
to run local zookeeper -> .\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties

see topic about -> .\kafka-topics.bat --bootstrap-server localhost:9092 --describe --topic cab-location

see list of topic -> .\kafka-topics.bat --bootstrap-server localhost:9092 --list

see the topic contents -> .\kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic cab-location --from-beginning
