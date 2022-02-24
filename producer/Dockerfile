FROM openjdk:8-jre-slim

WORKDIR /kafka-server

ADD kafka/ /kafka-server/

CMD ./bin/kafka-console-producer.sh --topic test --bootstrap-server server:9092 

