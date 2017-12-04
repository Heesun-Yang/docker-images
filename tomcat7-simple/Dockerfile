FROM tomcat:7

COPY simple.war /usr/local/tomcat/webapps/
COPY conf/server.xml /usr/local/tomcat/conf/

RUN chmod -R 775 /usr/local/tomcat/

EXPOSE 8080
