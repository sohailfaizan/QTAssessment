FROM tomcat:8.5.15-jre8
MAINTAINER sohail

VOLUME /tmp

# Delete existing ROOT folder
RUN rm -rf /usr/local/tomcat/webapps/ROOT
ADD ROOT.war /usr/local/tomcat/webapps/
CMD ["catalina.sh", "run"]
EXPOSE 8080
