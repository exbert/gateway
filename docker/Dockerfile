FROM openjdk

VOLUME /tmp

ADD maven/api-gateway-0.0.1-SNAPSHOT.jar api-gateway.jar

ENTRYPOINT ["java","-jar","api-gateway.jar"]