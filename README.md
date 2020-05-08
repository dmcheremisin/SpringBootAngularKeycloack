## Spring Security OAuth - New Stack

### Relevant information:

1. `oauth-authorization-server` is a Keycloak Authorization Server wrapped as a Spring Boot application
2. There is one OAuth Client registered in the Authorization Server:
   1. Client Id: newClient
   2. Client secret: newClientSecret
   3. Redirect Uri: http://localhost:8089/
2. There is OAuth Angular Front-end App:  
   `oauth-ui-authorization-code-angular` - A simple Angular App
3. `oauth-resource-server` is a Spring Boot based RESTFul API, acting as a backend Application
4. There are two users registered in the Authorization Server:
   1. john@test.com / 123
   2. mike@other.com / pass

## Relevant Articles: 

- [Spring REST API + OAuth2 + Angular](https://www.baeldung.com/rest-api-spring-oauth2-angular)
- [OAuth2 for a Spring REST API – Handle the Refresh Token in Angular](https://www.baeldung.com/spring-security-oauth2-refresh-token-angular)