# Microservice

Client side application properties

spring.application.name=Microservice

spring.mvc.view.prefix=/WEB-INF/
spring.mvc.view.suffix=.jsp

spring.jpa.hibernate.ddl-auto=update
spring.datasource.url=jdbc:mysql://localhost:3306/microservice
spring.datasource.username=root
spring.datasource.password=Pavan@1328
spring.jpa.show-sql=true
spring.jpa.generate-ddl=true
spring.jpa.open-in-view=true

server.port=8080

eureka.client.service-url.defaultZone=http://localhost:1000/eureka/

DiscoveryService application properties

server.port=1000

eureka.client.service-url.defaultZone=http://localhost:1000/eureka/
eureka.client.fetch-registry=false
eureka.client.register-with-eureka=false
