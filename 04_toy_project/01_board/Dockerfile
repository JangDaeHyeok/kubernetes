FROM sktellecom/centos7:jdk-11
VOLUME /tmp
CMD ["mkdir", "/board", "&", "chown", "-R", "1000:1000", "/board"]
EXPOSE 8090
ADD ./build/libs/webflux-0.0.1-SNAPSHOT.jar app.jar
ENV JAVA_OPTS=""
ENTRYPOINT ["java","-jar","/app.jar"]