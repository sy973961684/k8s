FROM openjdk:8-jre-alpine3.9

COPY target/cronjob-demo-1.0-SNAPSHOT.jar /cronjob-demo.jar

ENTRYPOINT ["java", "-cp", "/cronjob-demo.jar","com.mooc.demo.cronjob.Main"]
