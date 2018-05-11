# spring-boot-jpa-security" 


# Spring DataSource

spring.datasource.url = jdbc:mysql://localhost:3306/studentdb
spring.datasource.username = root
spring.datasource.password = root
spring.datasource.testWhileIdle = true
spring.datasource.validationQuery = SELECT 1
# JPA-Hibernate

spring.jpa.show-sql = true
spring.jpa.hibernate.ddl-auto = create-drop
spring.jpa.hibernate.naming-strategy = org.hibernate.cfg.ImprovedNamingStrategy
spring.jpa.properties.hibernate.dialect = org.hibernate.dialect.MySQL5Dialect 

spring.data.rest.basePath=/api 

# Security
spring.security.user.name = admin
spring.security.user.password = isawesome
