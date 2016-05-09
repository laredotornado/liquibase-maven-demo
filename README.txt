In order to run this example, you will need to have the following installed

Maven 3.2 or greater
Java 1.7 or greater
MySQL 5.5 or greater 

Then you will want to run the following commands as the MySQL root user

	create database example;
	grant all privileges on example.* to 'example'@'localhost' identified by 'example';

To run everything, type the following command in the same directory in which this file lives.

	mvn clean install

	
