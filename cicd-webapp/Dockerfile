FROM tomcat:8.5.54-jdk8
ADD target/cicd-webapp.war /usr/local/tomcat/webapps/ROOT.war
EXPOSE 8080
CMD ["catalina.sh", "run"]
