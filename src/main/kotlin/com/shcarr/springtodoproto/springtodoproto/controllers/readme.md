 to launch
 
 gradle build and run
 gradlew.bat build && java -jar build\libs\springtodoproto-0.0.1-SNAPSHOT.jar
 
 
 Basic: i can also add this to gradle or maven and have it done automatically.
 
 docker build 
 docker build -t spring_test . --build-arg JAR_FILE=build/libs/springtodoproto-0.0.1-SNAPSHOT.jar
 
 docker run
  docker run -it -p 8080:8080 spring_test
 
 
 