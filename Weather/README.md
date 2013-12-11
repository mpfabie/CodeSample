First, add an user with administrator access right for Tomcat. 

To add Tomcat user, edit this file – “%TOMCAT_PATH%/conf/tomcat-users.xml“.

<?xml version='1.0' encoding='utf-8'?>
<tomcat-users>
  <role rolename="manager"/>
  <role rolename="admin"/>
  <user username="admin" password="password" roles="admin,manager"/>
</tomcat-users>

