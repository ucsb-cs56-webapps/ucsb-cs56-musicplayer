# View the live webapp!

[https://ucsb-cs56-musicplayer.herokuapp.com/](https://ucsb-cs56-musicplayer.herokuapp.com/)

# sparkjava-01

The simplest possible SparkJava web app (Hello World)

* [javadocs](https://ucsb-cs56-pconrad.github.io/sparkjava-01/apidocs/index.html)
* [web page generated by Maven (NOT THE WEB APP)](https://ucsb-cs56-pconrad.github.io/sparkjava-01/index.html).  This is simply documentation automatically generated by Maven, not the actual running web app.


# To use

| To do this | Do this |
| -----------|-----------|
| run the program | Type `mvn exec:java`.  Visit the web page it indicates in the message |
| check that edits to the pom.xml file are valid | Type `mvn validate` |
| clean up so you can recompile everything  | Type `mvn clean` |
| edit the source code for the app | edit files in `src/main/java`.<br>Under that the directories for the package are `edu/ucsb/cs56/pconrad`  |
| edit the source code for the app | edit files in `src/test/java`.<br>Under that the directories for the package are `edu/ucsb/cs56/pconrad`  |
| compile    | Type `mvn compile` |
| run junit tests | Type `mvn test` |
| build the website, including javadoc | Type `mvn site-deploy` then look in either `target/site/apidocs/index.html`  |
| copy the website to `/docs` for publishing via github-pages | Type `mvn site-deploy` then look for javadoc in `docs/apidocs/index.html` |	
| make a jar file | Type `mvn package` and look in `target/*.jar` |

| run the main in the jar file | Type `java -jar target/sparkjava-demo-01-1.0-jar-with-dependencies.jar ` |
| change which main gets run by the jar | Edit the `<mainClass>` element in `pom.xml` |
