#Spring 4 Full Java Config Maven Archetype


##Summary
This is Spring 4 MVC Java Configuration. Everything is XML-free.

##What does it include?
* Java Configurations for **Spring MVC**, **Spring Security** & **Hibernate**
* Sample authentication application using **Thymeleaf** and **Bootstrap**

##How to install?
* Download the archetype
* Browse to the archetype directory and run `mvn install` to install to the local repository
 
###From console
* Create a new project directory
* Run `mvn archetype:generate -DarchetypeCatalog=local`
* Modify `settings.properties` under `src/main/resources` to your preference
* Run `mvn clean tomcat7:run`
* Pray it works ;)

###New Eclipse project
* Go `New > Maven Project` 
* Choose catalog as `Default Local`
* Select the proper archetype
* Click next and specify groupId, artifactId, version and package
* Wait for the workspace to finish updating
* Modify `settings.properties` under `src/main/resources` to your preference
* Run the project on your Tomcat7 or as Maven build with goals `clean tomcat7:run`

NB! Hibernate/PostgreSQL are not used in the example code, but you need proper settings in order to run the full configuration. 

Good luck!
