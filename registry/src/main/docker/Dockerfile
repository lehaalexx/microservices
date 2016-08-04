FROM frolvlad/alpine-oraclejdk8:slim
VOLUME /tmp
ADD registry.jar registry.jar
RUN sh -c 'touch /registry.jar'
ENTRYPOINT ["java", "-Xmx200m","-jar","/registry.jar"]
EXPOSE 8761