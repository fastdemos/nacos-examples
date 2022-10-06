FROM pi4k8s/openjdk8:centos7

WORKDIR /opt

ADD nacos-spring-cloud-provider-example.jar ./

ENV JAVA_OPTS "-Xms512m -Xmx512m"

ENTRYPOINT java ${JAVA_OPTS} -Djava.security.egd=file:/dev/./urandom -jar nacos-spring-cloud-provider-example.jar
