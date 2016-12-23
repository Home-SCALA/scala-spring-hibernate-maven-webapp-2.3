Scala + Spring + Hibernate + Maven + Selenium WebDriver
=======================================================

This project contains source code for kickstarting a webapp project using the latest versions of
Scala, Spring, Hibernate and Maven, including Selenium WebDriver PageObject-based web tests.

Versions currently used in the project are:

* jdk-1.7.0
* mvn-3.2.5
* [Scala](http://www.scala-lang.org/): 2.11.2
* [Spring](http://www.springsource.org/about): 4.0.6.RELEASE
* [Hibernate](http://www.hibernate.org/): 4.3.6.Final
* HSQLDB
* Jetty-9.2.2 **(** http://localhost:9090/home.html **)**
* Selenium

The code also makes use of [HSQLDB](http://hsqldb.org/), but you'll probably want to replace that with the JDBC driver
for whatever database you're using.


Building and Running
--------------------

Assuming you already have Maven installed, the webapp can be built by running:

    mvn clean install

The webapp can be run inside Jetty using the Maven plugin:

    mvn jetty:run

An Eclipse project will be generated with all the correct natures in it by running:

	mvn eclipse:eclipse


Attribution
-----------
This source code was originally created by Graham Lea for the blog http://grahamhackingscala.blogspot.com/
(though Graham now blogs at http://www.grahamlea.com/)

The Eclipse plugin configuration was submitted by Trevor Lalish-Menagh (http://www.trevmex.com/)

