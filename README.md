Uputstvo:
https://spring.io/guides/gs/producing-web-service/

Da bih nasao wsdl treba nakon pokretanja aplikacije da odem na:
http://localhost:8080/ws/countries.wsdl
 - **/ws** potice od `"/ws/*"` u `return new ServletRegistrationBean(servlet, "/ws/*")` u `WebServiceConfig`
 - **/countries.wsdl** potice od `@Bean(name = "countries")` u `WebServiceConfig`

Ako bih zeleo da iz executable JAR predjem u WAR:
https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/#build-tool-plugins-maven-packaging
