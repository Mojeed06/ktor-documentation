FROM tomcat:10.1.36
EXPOSE 8080:8080
COPY ./build/libs/tomcat-war.war/ /usr/local/tomcat/webapps
WORKDIR /usr/local/tomcat
CMD ["catalina.sh", "run"]
