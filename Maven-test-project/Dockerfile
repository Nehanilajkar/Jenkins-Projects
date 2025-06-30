FROM tomcat:9.0-jdk11

# Remove default ROOT webapp if you want (optional)
RUN rm -rf /usr/local/tomcat/webapps/ROOT

# Copy your WAR file into Tomcat's webapps folder
COPY my-webapp.war /usr/local/tomcat/webapps/

# Expose Tomcat port
EXPOSE 8080

# Start Tomcat
CMD ["catalina.sh", "run"]
