To use this RESTful application please follow the instructions as below.

Prerequisites - JAVA 1.7, Maven

1. Get the project source code on to your local machine.
2. Browse to the directory which has pom.xml
3. Run the following commands in sequence.
	a)mvn clean
	b)mvn package
4. In the directory of services you will see a new folder named target in which you will services-1.0.0.war. Rename this to services.war
5. Deploy the "services.war" onto a server like Apache Tomcat.
6. Access the application with the url : http://IP:PORT/services
