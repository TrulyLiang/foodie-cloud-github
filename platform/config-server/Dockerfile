FROM java:8
ADD target/config-server-1.0-SNAPSHOT.jar config-server-1.0-SNAPSHOT.jar
RUN bash -c 'touch /config-server-1.0-SNAPSHOT.jar'
ENTRYPOINT ["java","-jar","/config-server-1.0-SNAPSHOT.jar"]

