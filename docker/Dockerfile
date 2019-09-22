FROM openjdk:11

RUN mkdir -p /tmp/finastra/src
RUN mkdir -p /tmp/finastra/dest

WORKDIR /tmp/finastra

COPY *.jar .

CMD ["java", "-jar", "mnemonic-0.0.1-SNAPSHOT.jar"]