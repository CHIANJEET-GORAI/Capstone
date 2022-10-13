# DriveYourWay

This project is a web application which manages the cars sold at three different car dealerships. It performs CRUD (Create, read, update and delete), search and purchase 
functions/operations on any car from any dealerships.

Programming language: Java

Java Framework: Spring Boot

Type: Maven

Dependencies used: Spring Web, Thymeleaf, Lombok, Spring data JDBC and H2 database





## Run:
### Prerequisites (Requirements):

For building and running the application you need:

- [JDK 1.8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
- [Maven 3](https://maven.apache.org)

### Running the application with IDE

There are several ways to run a Spring Boot application on your local machine. One way is to execute the `main` method in the `com.devdaljeet.cardealershipsystem.CarDealershipSystemApplication` class from your IDE (Eclipse).

* 	Download the zip or clone the Git repository.
* 	Unzip the zip file (if you downloaded one)
* 	Open Command Prompt and Change directory (cd) to folder containing pom.xml
* 	Open Eclipse
	* File -> Import -> Existing Maven Project -> Navigate to the folder where you unzipped the zip
	* Select the project
* 	Choose the Spring Boot Application file (search for @SpringBootApplication)
* 	Right Click on the file and Run as Java Application

### Running the application with Maven

Alternatively you can use the [Spring Boot Maven plugin](https://docs.spring.io/spring-boot/docs/current/reference/html/build-tool-plugins-maven-plugin.html) like so:

```shell
$ git clone https://github.com/CHIANJEET-GORAI/Capstone/DriveYourWay.git
$ cd DriveYourWay
$ mvn spring-boot:run
```

# License
MIT License
Copyright (c) 2020 Dev-Daljeet

Refer to **LICENSE** file for full information.
