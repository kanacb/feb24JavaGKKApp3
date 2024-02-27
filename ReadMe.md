# Creating a WebSocket Application
Example of a WebSocket server implemented in Java using the javax.websocket API.

## Create a Java Project using VS Code
Steps
1. ctrl + shift + p
2. Spring Initializr - Create Maven Project
3. go thru the setup project
4. add the following dependencies
- spring-boot-starter-web
- lombok
- spring-boot-starter-websocket
- spring-boot-starter-tomcat
- javax.websocket-api
5. create these Java files in the main project folder
- WebSocketEndpointConfig.java
- WebSocketServer.java
6. create these html files in the resources/static folder
- index.html
- chat.html
- websocket.js
7. Copy the code that is shared in the github
- https://github.com/kanacb/feb24JavaGKKApp3.git

### Your taks
1. Find the correct host 
Replace `"ws://localhost:8080/your-war-file-name/echo"`

### To deploy you have to run this code