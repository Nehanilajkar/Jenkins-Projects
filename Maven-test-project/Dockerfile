FROM tomcat:9.0-jdk11

RUN rm -rf /usr/local/tomcat/webapps/ROOT

COPY target/my-webapp.war /usr/local/tomcat/webapps/

# Expose Tomcat port
EXPOSE 8080

# Start Tomcat
CMD ["catalina.sh", "run"]
