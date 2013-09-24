Todo app
==========
<div class="row-fluid">
  <div class="span8">
	<p>
	   This is an todo app developed by using spring rest.
	</p>
	<p>
	   Angular js is used as client side framework
	</p>
       <p>
           <b>Live Demo hosted at cloud foundry </b> http://todoapp.cfapps.io/ 
       </p>    
  </div>
</div>


Tools used :
* [Spring roo](https://github.com/spring-projects/spring-roo#readme)
* [Maven](http://maven.apache.org/)  
* [Angularjs](http://angularjs.org/)
* [MySql](http://www.mysql.com/)
* [SendGrid](http://sendgrid.com/)



Prerequisites :

Mysql database
   Modify database.properties accordingly.
   Modify hibernate.hbm2ddl.auto field in persistence.xml accordingly.

Sendgrid
   Modify sendgrid.properties for sending emails.

Steps to run :

	git clone https://github.com/kiranreddykasa/springrest-angularjs.git
	mvn clean package tomcat:run
	http://localhost:8080/todoapp/todoes
