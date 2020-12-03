# Greetings from Switzerland...

# Hello and welcome to DevOpsCon demo repository
## This repository contains basic Maven project with Hello-World war file 
In order to make it work, please do the following: 

<ul>
  <li>Make sure JAVA 8 is running on your laptop</li>
  <li>Get Tomcat 9 - prefer the Core > Zip from <a href=https://tomcat.apache.org/download-80.cgi target=new>here</a></li>
  <li>Configure under <TOMCAT DIR>/conf/tomcat-users.xml the code below</li>
  <li>[LINUX / MAC] Make sure you have running permissions <TOMCAT DIR>/bin/ and run chmod +x *.sh</li>
  <li>Restart tomcat <TOMCAT DIR>/bin/shutdown.sh & startup.sh</li>
  <li>Application URL is <a href=http://localhost:8080/helloworld/>http://localhost:8080/helloworld/</a></li>  
</ul>

 > ```xml
 > <tomcat-users>
 >   <role rolename="manager-gui" />
 >   <role rolename="admin-gui" />
 >   <role rolename="manager-script" />
 >   <user username="admin" password="admin" roles="manager-gui,admin-gui,manager-script" />
 > </tomcat-users>
 > ```
