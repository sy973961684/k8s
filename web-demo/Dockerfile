FROM hub.mooc.com/kubernetes/tomcat:8.0.51-alpine

COPY target/ROOT /usr/local/tomcat/webapps/ROOT

ENTRYPOINT ["/usr/local/tomcat/bin/catalina.sh","run"]
