FROM frolvlad/alpine-oraclejdk8:slim
VOLUME /tmp
ADD config.jar config.jar
RUN sh -c 'touch /config.jar'
ENTRYPOINT ["java", "-Xmx200m","-jar","/config.jar"]
EXPOSE 8888