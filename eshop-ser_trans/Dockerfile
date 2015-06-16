# Start from Tomcat 8.0 and JDK 8
FROM tomcat:8.0-jre8

MAINTAINER Jebastin Prabaharan<jpharan@gmail.com> 

#ENV WAR_SOURCE war/eshop-widget.war
ENV WAR_SOURCE war/SpringMVC.war
ENV WAR_TARGET /usr/local/tomcat/webapps/ecom.war

EXPOSE 8080

COPY $WAR_SOURCE $WAR_TARGET

CMD ["catalina.sh", "run"]
