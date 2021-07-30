FROM tomcat:8.0
ARG war_FILE=/var/lib/jenkins/workspace/Docker_Sample_job/java-tomcat-sample/target/java-tomcat-maven-example.war
COPY ${war_FILE} /usr/local/tomcat/webapps
ADD **/*.war /usr/local/tomcat/webapps
EXPOSE 8080
CMD ["catalina.sh", "run"]
