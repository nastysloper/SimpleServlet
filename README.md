# SimpleServlet
Old School Servlet example that responds to doGet

Prerequisites: Java, Maven and Tomcat

In the project directory with the POM, run the following command:
mvn clean install

This builds the project. Copy the war file into the Tomcat directory, e.g.,
cp target/*.war /usr/local/Tomcat8/webapps/ROOT.war

Start Catalina while in the Tomcat directory:
bin/startup.sh

Point your browser at localhost:8080/allforone and bask in the glory!
