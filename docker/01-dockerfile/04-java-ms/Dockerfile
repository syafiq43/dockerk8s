FROM openjdk:8-jre-alpine
MAINTAINER info@brainupgrade.in
#COPY --from=java-build /build/request-logger/target/app.jar app.jar
COPY app.jar app.jar
ENTRYPOINT ["/usr/bin/java"]
CMD ["-jar","app.jar"]
# docker build -t java-run .
# docker run -p 8080:8080 java-run