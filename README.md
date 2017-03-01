# employee-service
employee-service for osi-tech portal

Steps:

1) Check-out the project on your local 
2) Download the dependencies using the command 

- gradlew eclipse dependencies - for windows
- ./gradlew eclipse dependencies - for mac

3) Run the application as springboot application using below commands

  - gradle bootRun - from cmd for windows
  - run as > java application or spring boot App (from eclipse or any other ide)

4) Once you run the service, it will be discoverable using eureka (can be accessed using the url: localhost:8761/eureka/)
5) Service is secured by providing basic authentication, please use the user id and passwords to hit the endpoints
6) Service will read the properties from config server using the config server's service id instead of mapping any hard-coded port.
