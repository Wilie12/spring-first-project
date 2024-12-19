# First Spring Project
First Spring Project is a simple Spring Boot Web application created in order to demonstrate Spring framework.
## Resources
This API handles only one endpoint with static content:

- https://localhost:8080/greeting

## How to use
Page can be accessed with name parameter, but also has default value.
### With parameter
```
[GET] https://localhost:8080/greeting?name=yourName
```
In response yourName will be displayed on the website.
### Without parameter
```
[GET] https://localhost:8080/greeting
```
In response there will be deafult name displayed: "Vistula".

## Technologies
- Spring Boot 3
- Java
- Spring Web
- Thymeleaf
