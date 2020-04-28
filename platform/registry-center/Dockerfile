FROM java:8
ADD target/registry-center-1.0-SNAPSHOT.jar registry-center-1.0-SNAPSHOT.jar
RUN bash -c 'touch /registry-center-1.0-SNAPSHOT.jar'
ENTRYPOINT ["java","-jar","/registry-center-1.0-SNAPSHOT.jar"]

