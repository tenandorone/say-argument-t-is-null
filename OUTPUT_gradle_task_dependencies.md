# Task :dependencies

```console
------------------------------------------------------------
Root project 'say-argument-t-is-null'
------------------------------------------------------------

annotationProcessor - Annotation processors and their dependencies for source set 'main'.
No dependencies

bootArchives - Configuration for Spring Boot archive artifacts. (n)
No dependencies

compileClasspath - Compile classpath for source set 'main'.
+--- org.springframework.boot:spring-boot-starter-data-jpa -> 3.4.1
|    +--- org.springframework.boot:spring-boot-starter:3.4.1
|    |    +--- org.springframework.boot:spring-boot:3.4.1
|    |    |    +--- org.springframework:spring-core:6.2.1
|    |    |    |    \--- org.springframework:spring-jcl:6.2.1
|    |    |    \--- org.springframework:spring-context:6.2.1
|    |    |         +--- org.springframework:spring-aop:6.2.1
|    |    |         |    +--- org.springframework:spring-beans:6.2.1
|    |    |         |    |    \--- org.springframework:spring-core:6.2.1 (*)
|    |    |         |    \--- org.springframework:spring-core:6.2.1 (*)
|    |    |         +--- org.springframework:spring-beans:6.2.1 (*)
|    |    |         +--- org.springframework:spring-core:6.2.1 (*)
|    |    |         +--- org.springframework:spring-expression:6.2.1
|    |    |         |    \--- org.springframework:spring-core:6.2.1 (*)
|    |    |         \--- io.micrometer:micrometer-observation:1.14.2
|    |    |              \--- io.micrometer:micrometer-commons:1.14.2
|    |    +--- org.springframework.boot:spring-boot-autoconfigure:3.4.1
|    |    |    \--- org.springframework.boot:spring-boot:3.4.1 (*)
|    |    +--- org.springframework.boot:spring-boot-starter-logging:3.4.1
|    |    |    +--- ch.qos.logback:logback-classic:1.5.12
|    |    |    |    +--- ch.qos.logback:logback-core:1.5.12
|    |    |    |    \--- org.slf4j:slf4j-api:2.0.15 -> 2.0.16
|    |    |    +--- org.apache.logging.log4j:log4j-to-slf4j:2.24.3
|    |    |    |    +--- org.apache.logging.log4j:log4j-api:2.24.3
|    |    |    |    \--- org.slf4j:slf4j-api:2.0.16
|    |    |    \--- org.slf4j:jul-to-slf4j:2.0.16
|    |    |         \--- org.slf4j:slf4j-api:2.0.16
|    |    +--- jakarta.annotation:jakarta.annotation-api:2.1.1
|    |    +--- org.springframework:spring-core:6.2.1 (*)
|    |    \--- org.yaml:snakeyaml:2.3
|    +--- org.springframework.boot:spring-boot-starter-jdbc:3.4.1
|    |    +--- org.springframework.boot:spring-boot-starter:3.4.1 (*)
|    |    +--- com.zaxxer:HikariCP:5.1.0
|    |    |    \--- org.slf4j:slf4j-api:1.7.36 -> 2.0.16
|    |    \--- org.springframework:spring-jdbc:6.2.1
|    |         +--- org.springframework:spring-beans:6.2.1 (*)
|    |         +--- org.springframework:spring-core:6.2.1 (*)
|    |         \--- org.springframework:spring-tx:6.2.1
|    |              +--- org.springframework:spring-beans:6.2.1 (*)
|    |              \--- org.springframework:spring-core:6.2.1 (*)
|    +--- org.hibernate.orm:hibernate-core:6.6.4.Final
|    |    +--- jakarta.persistence:jakarta.persistence-api:3.1.0
|    |    \--- jakarta.transaction:jakarta.transaction-api:2.0.1
|    +--- org.springframework.data:spring-data-jpa:3.4.1
|    |    +--- org.springframework.data:spring-data-commons:3.4.1
|    |    |    +--- org.springframework:spring-core:6.2.1 (*)
|    |    |    +--- org.springframework:spring-beans:6.2.1 (*)
|    |    |    \--- org.slf4j:slf4j-api:2.0.2 -> 2.0.16
|    |    +--- org.springframework:spring-orm:6.2.1
|    |    |    +--- org.springframework:spring-beans:6.2.1 (*)
|    |    |    +--- org.springframework:spring-core:6.2.1 (*)
|    |    |    +--- org.springframework:spring-jdbc:6.2.1 (*)
|    |    |    \--- org.springframework:spring-tx:6.2.1 (*)
|    |    +--- org.springframework:spring-context:6.2.1 (*)
|    |    +--- org.springframework:spring-aop:6.2.1 (*)
|    |    +--- org.springframework:spring-tx:6.2.1 (*)
|    |    +--- org.springframework:spring-beans:6.2.1 (*)
|    |    +--- org.springframework:spring-core:6.2.1 (*)
|    |    +--- org.antlr:antlr4-runtime:4.13.0
|    |    +--- jakarta.annotation:jakarta.annotation-api:2.0.0 -> 2.1.1
|    |    \--- org.slf4j:slf4j-api:2.0.2 -> 2.0.16
|    \--- org.springframework:spring-aspects:6.2.1
|         \--- org.aspectj:aspectjweaver:1.9.22.1
+--- org.springframework.boot:spring-boot-starter-data-rest -> 3.4.1
|    +--- org.springframework.boot:spring-boot-starter-web:3.4.1
|    |    +--- org.springframework.boot:spring-boot-starter:3.4.1 (*)
|    |    +--- org.springframework.boot:spring-boot-starter-json:3.4.1
|    |    |    +--- org.springframework.boot:spring-boot-starter:3.4.1 (*)
|    |    |    +--- org.springframework:spring-web:6.2.1
|    |    |    |    +--- org.springframework:spring-beans:6.2.1 (*)
|    |    |    |    +--- org.springframework:spring-core:6.2.1 (*)
|    |    |    |    \--- io.micrometer:micrometer-observation:1.14.2 (*)
|    |    |    +--- com.fasterxml.jackson.core:jackson-databind:2.18.2
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-annotations:2.18.2
|    |    |    |    |    \--- com.fasterxml.jackson:jackson-bom:2.18.2
|    |    |    |    |         +--- com.fasterxml.jackson.core:jackson-annotations:2.18.2 (c)
|    |    |    |    |         +--- com.fasterxml.jackson.core:jackson-core:2.18.2 (c)
|    |    |    |    |         +--- com.fasterxml.jackson.core:jackson-databind:2.18.2 (c)
|    |    |    |    |         +--- com.fasterxml.jackson.datatype:jackson-datatype-jdk8:2.18.2 (c)
|    |    |    |    |         +--- com.fasterxml.jackson.datatype:jackson-datatype-jsr310:2.18.2 (c)
|    |    |    |    |         +--- com.fasterxml.jackson.module:jackson-module-parameter-names:2.18.2 (c)
|    |    |    |    |         \--- com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:2.18.2 (c)
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-core:2.18.2
|    |    |    |    |    \--- com.fasterxml.jackson:jackson-bom:2.18.2 (*)
|    |    |    |    \--- com.fasterxml.jackson:jackson-bom:2.18.2 (*)
|    |    |    +--- com.fasterxml.jackson.datatype:jackson-datatype-jdk8:2.18.2
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-core:2.18.2 (*)
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-databind:2.18.2 (*)
|    |    |    |    \--- com.fasterxml.jackson:jackson-bom:2.18.2 (*)
|    |    |    +--- com.fasterxml.jackson.datatype:jackson-datatype-jsr310:2.18.2
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-annotations:2.18.2 (*)
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-core:2.18.2 (*)
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-databind:2.18.2 (*)
|    |    |    |    \--- com.fasterxml.jackson:jackson-bom:2.18.2 (*)
|    |    |    \--- com.fasterxml.jackson.module:jackson-module-parameter-names:2.18.2
|    |    |         +--- com.fasterxml.jackson.core:jackson-core:2.18.2 (*)
|    |    |         +--- com.fasterxml.jackson.core:jackson-databind:2.18.2 (*)
|    |    |         \--- com.fasterxml.jackson:jackson-bom:2.18.2 (*)
|    |    +--- org.springframework.boot:spring-boot-starter-tomcat:3.4.1
|    |    |    +--- jakarta.annotation:jakarta.annotation-api:2.1.1
|    |    |    +--- org.apache.tomcat.embed:tomcat-embed-core:10.1.34
|    |    |    +--- org.apache.tomcat.embed:tomcat-embed-el:10.1.34
|    |    |    \--- org.apache.tomcat.embed:tomcat-embed-websocket:10.1.34
|    |    |         \--- org.apache.tomcat.embed:tomcat-embed-core:10.1.34
|    |    +--- org.springframework:spring-web:6.2.1 (*)
|    |    \--- org.springframework:spring-webmvc:6.2.1
|    |         +--- org.springframework:spring-aop:6.2.1 (*)
|    |         +--- org.springframework:spring-beans:6.2.1 (*)
|    |         +--- org.springframework:spring-context:6.2.1 (*)
|    |         +--- org.springframework:spring-core:6.2.1 (*)
|    |         +--- org.springframework:spring-expression:6.2.1 (*)
|    |         \--- org.springframework:spring-web:6.2.1 (*)
|    \--- org.springframework.data:spring-data-rest-webmvc:4.4.1
|         +--- org.springframework.data:spring-data-rest-core:4.4.1
|         |    +--- org.springframework:spring-tx:6.2.1 (*)
|         |    +--- org.springframework.hateoas:spring-hateoas:2.4.1
|         |    |    +--- org.springframework:spring-aop:6.2.1 (*)
|         |    |    +--- org.springframework:spring-beans:6.2.1 (*)
|         |    |    +--- org.springframework:spring-context:6.2.1 (*)
|         |    |    +--- org.springframework:spring-core:6.2.1 (*)
|         |    |    +--- org.springframework:spring-web:6.2.1 (*)
|         |    |    +--- org.springframework.plugin:spring-plugin-core:3.0.0
|         |    |    |    +--- org.springframework:spring-beans:6.0.0 -> 6.2.1 (*)
|         |    |    |    +--- org.springframework:spring-context:6.0.0 -> 6.2.1 (*)
|         |    |    |    +--- org.springframework:spring-aop:6.0.0 -> 6.2.1 (*)
|         |    |    |    \--- org.slf4j:slf4j-api:2.0.3 -> 2.0.16
|         |    |    +--- com.jayway.jsonpath:json-path:2.9.0
|         |    |    \--- org.slf4j:slf4j-api:2.0.16
|         |    +--- org.springframework.data:spring-data-commons:3.4.1 (*)
|         |    +--- org.springframework.plugin:spring-plugin-core:3.0.0 (*)
|         |    +--- org.atteo:evo-inflector:1.3
|         |    +--- com.fasterxml.jackson.core:jackson-annotations:2.18.2 (*)
|         |    +--- com.fasterxml.jackson.datatype:jackson-datatype-jdk8:2.18.2 (*)
|         |    \--- org.slf4j:slf4j-api:2.0.2 -> 2.0.16
|         +--- org.springframework:spring-webmvc:6.2.1 (*)
|         +--- com.fasterxml.jackson.core:jackson-databind:2.18.2 (*)
|         +--- com.fasterxml.jackson.core:jackson-annotations:2.18.2 (*)
|         \--- org.slf4j:slf4j-api:2.0.2 -> 2.0.16
+--- org.springframework.boot:spring-boot-starter-web -> 3.4.1 (*)
\--- org.springdoc:springdoc-openapi-starter-webmvc-ui:2.8.3
     +--- org.springdoc:springdoc-openapi-starter-webmvc-api:2.8.3
     |    +--- org.springdoc:springdoc-openapi-starter-common:2.8.3
     |    |    +--- org.springframework.boot:spring-boot-autoconfigure:3.4.1 (*)
     |    |    \--- io.swagger.core.v3:swagger-core-jakarta:2.2.27
     |    |         +--- org.apache.commons:commons-lang3:3.17.0
     |    |         +--- org.slf4j:slf4j-api:2.0.9 -> 2.0.16
     |    |         +--- io.swagger.core.v3:swagger-annotations-jakarta:2.2.27
     |    |         +--- io.swagger.core.v3:swagger-models-jakarta:2.2.27
     |    |         |    \--- com.fasterxml.jackson.core:jackson-annotations:2.16.2 -> 2.18.2 (*)
     |    |         +--- org.yaml:snakeyaml:2.3
     |    |         +--- jakarta.xml.bind:jakarta.xml.bind-api:3.0.1 -> 4.0.2
     |    |         |    \--- jakarta.activation:jakarta.activation-api:2.1.3
     |    |         +--- jakarta.validation:jakarta.validation-api:3.1.0 -> 3.0.2
     |    |         +--- com.fasterxml.jackson.core:jackson-annotations:2.16.2 -> 2.18.2 (*)
     |    |         +--- com.fasterxml.jackson.core:jackson-databind:2.16.2 -> 2.18.2 (*)
     |    |         +--- com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:2.16.2 -> 2.18.2
     |    |         |    +--- com.fasterxml.jackson.core:jackson-databind:2.18.2 (*)
     |    |         |    +--- org.yaml:snakeyaml:2.3
     |    |         |    +--- com.fasterxml.jackson.core:jackson-core:2.18.2 (*)
     |    |         |    \--- com.fasterxml.jackson:jackson-bom:2.18.2 (*)
     |    |         \--- com.fasterxml.jackson.datatype:jackson-datatype-jsr310:2.16.2 -> 2.18.2 (*)
     |    \--- org.springframework:spring-webmvc:6.2.1 (*)
     +--- org.webjars:swagger-ui:5.18.2
     \--- org.webjars:webjars-locator-lite:1.0.1
          \--- org.jspecify:jspecify:1.0.0

compileOnly - Compile-only dependencies for the 'main' feature. (n)
No dependencies

default - Configuration for default artifacts. (n)
No dependencies

developmentOnly - Configuration for development-only dependencies such as Spring Boot's DevTools.
No dependencies

implementation - Implementation dependencies for the 'main' feature. (n)
+--- org.springframework.boot:spring-boot-starter-data-jpa (n)
+--- org.springframework.boot:spring-boot-starter-data-rest (n)
+--- org.springframework.boot:spring-boot-starter-web (n)
\--- org.springdoc:springdoc-openapi-starter-webmvc-ui:2.8.3 (n)

mainSourceElements - List of source directories contained in the Main SourceSet. (n)
No dependencies

productionRuntimeClasspath
+--- org.springframework.boot:spring-boot-starter-data-jpa -> 3.4.1
|    +--- org.springframework.boot:spring-boot-starter:3.4.1
|    |    +--- org.springframework.boot:spring-boot:3.4.1
|    |    |    +--- org.springframework:spring-core:6.2.1
|    |    |    |    \--- org.springframework:spring-jcl:6.2.1
|    |    |    \--- org.springframework:spring-context:6.2.1
|    |    |         +--- org.springframework:spring-aop:6.2.1
|    |    |         |    +--- org.springframework:spring-beans:6.2.1
|    |    |         |    |    \--- org.springframework:spring-core:6.2.1 (*)
|    |    |         |    \--- org.springframework:spring-core:6.2.1 (*)
|    |    |         +--- org.springframework:spring-beans:6.2.1 (*)
|    |    |         +--- org.springframework:spring-core:6.2.1 (*)
|    |    |         +--- org.springframework:spring-expression:6.2.1
|    |    |         |    \--- org.springframework:spring-core:6.2.1 (*)
|    |    |         \--- io.micrometer:micrometer-observation:1.14.2
|    |    |              \--- io.micrometer:micrometer-commons:1.14.2
|    |    +--- org.springframework.boot:spring-boot-autoconfigure:3.4.1
|    |    |    \--- org.springframework.boot:spring-boot:3.4.1 (*)
|    |    +--- org.springframework.boot:spring-boot-starter-logging:3.4.1
|    |    |    +--- ch.qos.logback:logback-classic:1.5.12
|    |    |    |    +--- ch.qos.logback:logback-core:1.5.12
|    |    |    |    \--- org.slf4j:slf4j-api:2.0.15 -> 2.0.16
|    |    |    +--- org.apache.logging.log4j:log4j-to-slf4j:2.24.3
|    |    |    |    +--- org.apache.logging.log4j:log4j-api:2.24.3
|    |    |    |    \--- org.slf4j:slf4j-api:2.0.16
|    |    |    \--- org.slf4j:jul-to-slf4j:2.0.16
|    |    |         \--- org.slf4j:slf4j-api:2.0.16
|    |    +--- jakarta.annotation:jakarta.annotation-api:2.1.1
|    |    +--- org.springframework:spring-core:6.2.1 (*)
|    |    \--- org.yaml:snakeyaml:2.3
|    +--- org.springframework.boot:spring-boot-starter-jdbc:3.4.1
|    |    +--- org.springframework.boot:spring-boot-starter:3.4.1 (*)
|    |    +--- com.zaxxer:HikariCP:5.1.0
|    |    |    \--- org.slf4j:slf4j-api:1.7.36 -> 2.0.16
|    |    \--- org.springframework:spring-jdbc:6.2.1
|    |         +--- org.springframework:spring-beans:6.2.1 (*)
|    |         +--- org.springframework:spring-core:6.2.1 (*)
|    |         \--- org.springframework:spring-tx:6.2.1
|    |              +--- org.springframework:spring-beans:6.2.1 (*)
|    |              \--- org.springframework:spring-core:6.2.1 (*)
|    +--- org.hibernate.orm:hibernate-core:6.6.4.Final
|    |    +--- jakarta.persistence:jakarta.persistence-api:3.1.0
|    |    +--- jakarta.transaction:jakarta.transaction-api:2.0.1
|    |    +--- org.jboss.logging:jboss-logging:3.5.0.Final -> 3.6.1.Final
|    |    +--- org.hibernate.common:hibernate-commons-annotations:7.0.3.Final
|    |    +--- io.smallrye:jandex:3.2.0
|    |    +--- com.fasterxml:classmate:1.5.1 -> 1.7.0
|    |    +--- net.bytebuddy:byte-buddy:1.14.18 -> 1.15.11
|    |    +--- jakarta.xml.bind:jakarta.xml.bind-api:4.0.0 -> 4.0.2
|    |    |    \--- jakarta.activation:jakarta.activation-api:2.1.3
|    |    +--- org.glassfish.jaxb:jaxb-runtime:4.0.2 -> 4.0.5
|    |    |    \--- org.glassfish.jaxb:jaxb-core:4.0.5
|    |    |         +--- jakarta.xml.bind:jakarta.xml.bind-api:4.0.2 (*)
|    |    |         +--- jakarta.activation:jakarta.activation-api:2.1.3
|    |    |         +--- org.eclipse.angus:angus-activation:2.0.2
|    |    |         |    \--- jakarta.activation:jakarta.activation-api:2.1.3
|    |    |         +--- org.glassfish.jaxb:txw2:4.0.5
|    |    |         \--- com.sun.istack:istack-commons-runtime:4.1.2
|    |    +--- jakarta.inject:jakarta.inject-api:2.0.1
|    |    \--- org.antlr:antlr4-runtime:4.13.0
|    +--- org.springframework.data:spring-data-jpa:3.4.1
|    |    +--- org.springframework.data:spring-data-commons:3.4.1
|    |    |    +--- org.springframework:spring-core:6.2.1 (*)
|    |    |    +--- org.springframework:spring-beans:6.2.1 (*)
|    |    |    \--- org.slf4j:slf4j-api:2.0.2 -> 2.0.16
|    |    +--- org.springframework:spring-orm:6.2.1
|    |    |    +--- org.springframework:spring-beans:6.2.1 (*)
|    |    |    +--- org.springframework:spring-core:6.2.1 (*)
|    |    |    +--- org.springframework:spring-jdbc:6.2.1 (*)
|    |    |    \--- org.springframework:spring-tx:6.2.1 (*)
|    |    +--- org.springframework:spring-context:6.2.1 (*)
|    |    +--- org.springframework:spring-aop:6.2.1 (*)
|    |    +--- org.springframework:spring-tx:6.2.1 (*)
|    |    +--- org.springframework:spring-beans:6.2.1 (*)
|    |    +--- org.springframework:spring-core:6.2.1 (*)
|    |    +--- org.antlr:antlr4-runtime:4.13.0
|    |    +--- jakarta.annotation:jakarta.annotation-api:2.0.0 -> 2.1.1
|    |    \--- org.slf4j:slf4j-api:2.0.2 -> 2.0.16
|    \--- org.springframework:spring-aspects:6.2.1
|         \--- org.aspectj:aspectjweaver:1.9.22.1
+--- org.springframework.boot:spring-boot-starter-data-rest -> 3.4.1
|    +--- org.springframework.boot:spring-boot-starter-web:3.4.1
|    |    +--- org.springframework.boot:spring-boot-starter:3.4.1 (*)
|    |    +--- org.springframework.boot:spring-boot-starter-json:3.4.1
|    |    |    +--- org.springframework.boot:spring-boot-starter:3.4.1 (*)
|    |    |    +--- org.springframework:spring-web:6.2.1
|    |    |    |    +--- org.springframework:spring-beans:6.2.1 (*)
|    |    |    |    +--- org.springframework:spring-core:6.2.1 (*)
|    |    |    |    \--- io.micrometer:micrometer-observation:1.14.2 (*)
|    |    |    +--- com.fasterxml.jackson.core:jackson-databind:2.18.2
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-annotations:2.18.2
|    |    |    |    |    \--- com.fasterxml.jackson:jackson-bom:2.18.2
|    |    |    |    |         +--- com.fasterxml.jackson.core:jackson-annotations:2.18.2 (c)
|    |    |    |    |         +--- com.fasterxml.jackson.core:jackson-core:2.18.2 (c)
|    |    |    |    |         +--- com.fasterxml.jackson.core:jackson-databind:2.18.2 (c)
|    |    |    |    |         +--- com.fasterxml.jackson.datatype:jackson-datatype-jdk8:2.18.2 (c)
|    |    |    |    |         +--- com.fasterxml.jackson.datatype:jackson-datatype-jsr310:2.18.2 (c)
|    |    |    |    |         +--- com.fasterxml.jackson.module:jackson-module-parameter-names:2.18.2 (c)
|    |    |    |    |         \--- com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:2.18.2 (c)
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-core:2.18.2
|    |    |    |    |    \--- com.fasterxml.jackson:jackson-bom:2.18.2 (*)
|    |    |    |    \--- com.fasterxml.jackson:jackson-bom:2.18.2 (*)
|    |    |    +--- com.fasterxml.jackson.datatype:jackson-datatype-jdk8:2.18.2
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-core:2.18.2 (*)
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-databind:2.18.2 (*)
|    |    |    |    \--- com.fasterxml.jackson:jackson-bom:2.18.2 (*)
|    |    |    +--- com.fasterxml.jackson.datatype:jackson-datatype-jsr310:2.18.2
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-annotations:2.18.2 (*)
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-core:2.18.2 (*)
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-databind:2.18.2 (*)
|    |    |    |    \--- com.fasterxml.jackson:jackson-bom:2.18.2 (*)
|    |    |    \--- com.fasterxml.jackson.module:jackson-module-parameter-names:2.18.2
|    |    |         +--- com.fasterxml.jackson.core:jackson-core:2.18.2 (*)
|    |    |         +--- com.fasterxml.jackson.core:jackson-databind:2.18.2 (*)
|    |    |         \--- com.fasterxml.jackson:jackson-bom:2.18.2 (*)
|    |    +--- org.springframework.boot:spring-boot-starter-tomcat:3.4.1
|    |    |    +--- jakarta.annotation:jakarta.annotation-api:2.1.1
|    |    |    +--- org.apache.tomcat.embed:tomcat-embed-core:10.1.34
|    |    |    +--- org.apache.tomcat.embed:tomcat-embed-el:10.1.34
|    |    |    \--- org.apache.tomcat.embed:tomcat-embed-websocket:10.1.34
|    |    |         \--- org.apache.tomcat.embed:tomcat-embed-core:10.1.34
|    |    +--- org.springframework:spring-web:6.2.1 (*)
|    |    \--- org.springframework:spring-webmvc:6.2.1
|    |         +--- org.springframework:spring-aop:6.2.1 (*)
|    |         +--- org.springframework:spring-beans:6.2.1 (*)
|    |         +--- org.springframework:spring-context:6.2.1 (*)
|    |         +--- org.springframework:spring-core:6.2.1 (*)
|    |         +--- org.springframework:spring-expression:6.2.1 (*)
|    |         \--- org.springframework:spring-web:6.2.1 (*)
|    \--- org.springframework.data:spring-data-rest-webmvc:4.4.1
|         +--- org.springframework.data:spring-data-rest-core:4.4.1
|         |    +--- org.springframework:spring-tx:6.2.1 (*)
|         |    +--- org.springframework.hateoas:spring-hateoas:2.4.1
|         |    |    +--- org.springframework:spring-aop:6.2.1 (*)
|         |    |    +--- org.springframework:spring-beans:6.2.1 (*)
|         |    |    +--- org.springframework:spring-context:6.2.1 (*)
|         |    |    +--- org.springframework:spring-core:6.2.1 (*)
|         |    |    +--- org.springframework:spring-web:6.2.1 (*)
|         |    |    +--- org.springframework.plugin:spring-plugin-core:3.0.0
|         |    |    |    +--- org.springframework:spring-beans:6.0.0 -> 6.2.1 (*)
|         |    |    |    +--- org.springframework:spring-context:6.0.0 -> 6.2.1 (*)
|         |    |    |    +--- org.springframework:spring-aop:6.0.0 -> 6.2.1 (*)
|         |    |    |    \--- org.slf4j:slf4j-api:2.0.3 -> 2.0.16
|         |    |    +--- com.jayway.jsonpath:json-path:2.9.0
|         |    |    |    +--- net.minidev:json-smart:2.5.0 -> 2.5.1
|         |    |    |    |    \--- net.minidev:accessors-smart:2.5.1
|         |    |    |    |         \--- org.ow2.asm:asm:9.6
|         |    |    |    \--- org.slf4j:slf4j-api:2.0.11 -> 2.0.16
|         |    |    \--- org.slf4j:slf4j-api:2.0.16
|         |    +--- org.springframework.data:spring-data-commons:3.4.1 (*)
|         |    +--- org.springframework.plugin:spring-plugin-core:3.0.0 (*)
|         |    +--- org.atteo:evo-inflector:1.3
|         |    +--- com.fasterxml.jackson.core:jackson-annotations:2.18.2 (*)
|         |    +--- com.fasterxml.jackson.datatype:jackson-datatype-jdk8:2.18.2 (*)
|         |    \--- org.slf4j:slf4j-api:2.0.2 -> 2.0.16
|         +--- org.springframework:spring-webmvc:6.2.1 (*)
|         +--- com.fasterxml.jackson.core:jackson-databind:2.18.2 (*)
|         +--- com.fasterxml.jackson.core:jackson-annotations:2.18.2 (*)
|         \--- org.slf4j:slf4j-api:2.0.2 -> 2.0.16
+--- org.springframework.boot:spring-boot-starter-web -> 3.4.1 (*)
+--- org.springdoc:springdoc-openapi-starter-webmvc-ui:2.8.3
|    +--- org.springdoc:springdoc-openapi-starter-webmvc-api:2.8.3
|    |    +--- org.springdoc:springdoc-openapi-starter-common:2.8.3
|    |    |    +--- org.springframework.boot:spring-boot-autoconfigure:3.4.1 (*)
|    |    |    \--- io.swagger.core.v3:swagger-core-jakarta:2.2.27
|    |    |         +--- org.apache.commons:commons-lang3:3.17.0
|    |    |         +--- org.slf4j:slf4j-api:2.0.9 -> 2.0.16
|    |    |         +--- io.swagger.core.v3:swagger-annotations-jakarta:2.2.27
|    |    |         +--- io.swagger.core.v3:swagger-models-jakarta:2.2.27
|    |    |         |    \--- com.fasterxml.jackson.core:jackson-annotations:2.16.2 -> 2.18.2 (*)
|    |    |         +--- org.yaml:snakeyaml:2.3
|    |    |         +--- jakarta.xml.bind:jakarta.xml.bind-api:3.0.1 -> 4.0.2 (*)
|    |    |         +--- jakarta.validation:jakarta.validation-api:3.1.0 -> 3.0.2
|    |    |         +--- com.fasterxml.jackson.core:jackson-annotations:2.16.2 -> 2.18.2 (*)
|    |    |         +--- com.fasterxml.jackson.core:jackson-databind:2.16.2 -> 2.18.2 (*)
|    |    |         +--- com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:2.16.2 -> 2.18.2
|    |    |         |    +--- com.fasterxml.jackson.core:jackson-databind:2.18.2 (*)
|    |    |         |    +--- org.yaml:snakeyaml:2.3
|    |    |         |    +--- com.fasterxml.jackson.core:jackson-core:2.18.2 (*)
|    |    |         |    \--- com.fasterxml.jackson:jackson-bom:2.18.2 (*)
|    |    |         \--- com.fasterxml.jackson.datatype:jackson-datatype-jsr310:2.16.2 -> 2.18.2 (*)
|    |    \--- org.springframework:spring-webmvc:6.2.1 (*)
|    +--- org.webjars:swagger-ui:5.18.2
|    \--- org.webjars:webjars-locator-lite:1.0.1
|         \--- org.jspecify:jspecify:1.0.0
\--- com.h2database:h2 -> 2.3.232

runtimeClasspath - Runtime classpath of source set 'main'.
+--- org.springframework.boot:spring-boot-starter-data-jpa -> 3.4.1
|    +--- org.springframework.boot:spring-boot-starter:3.4.1
|    |    +--- org.springframework.boot:spring-boot:3.4.1
|    |    |    +--- org.springframework:spring-core:6.2.1
|    |    |    |    \--- org.springframework:spring-jcl:6.2.1
|    |    |    \--- org.springframework:spring-context:6.2.1
|    |    |         +--- org.springframework:spring-aop:6.2.1
|    |    |         |    +--- org.springframework:spring-beans:6.2.1
|    |    |         |    |    \--- org.springframework:spring-core:6.2.1 (*)
|    |    |         |    \--- org.springframework:spring-core:6.2.1 (*)
|    |    |         +--- org.springframework:spring-beans:6.2.1 (*)
|    |    |         +--- org.springframework:spring-core:6.2.1 (*)
|    |    |         +--- org.springframework:spring-expression:6.2.1
|    |    |         |    \--- org.springframework:spring-core:6.2.1 (*)
|    |    |         \--- io.micrometer:micrometer-observation:1.14.2
|    |    |              \--- io.micrometer:micrometer-commons:1.14.2
|    |    +--- org.springframework.boot:spring-boot-autoconfigure:3.4.1
|    |    |    \--- org.springframework.boot:spring-boot:3.4.1 (*)
|    |    +--- org.springframework.boot:spring-boot-starter-logging:3.4.1
|    |    |    +--- ch.qos.logback:logback-classic:1.5.12
|    |    |    |    +--- ch.qos.logback:logback-core:1.5.12
|    |    |    |    \--- org.slf4j:slf4j-api:2.0.15 -> 2.0.16
|    |    |    +--- org.apache.logging.log4j:log4j-to-slf4j:2.24.3
|    |    |    |    +--- org.apache.logging.log4j:log4j-api:2.24.3
|    |    |    |    \--- org.slf4j:slf4j-api:2.0.16
|    |    |    \--- org.slf4j:jul-to-slf4j:2.0.16
|    |    |         \--- org.slf4j:slf4j-api:2.0.16
|    |    +--- jakarta.annotation:jakarta.annotation-api:2.1.1
|    |    +--- org.springframework:spring-core:6.2.1 (*)
|    |    \--- org.yaml:snakeyaml:2.3
|    +--- org.springframework.boot:spring-boot-starter-jdbc:3.4.1
|    |    +--- org.springframework.boot:spring-boot-starter:3.4.1 (*)
|    |    +--- com.zaxxer:HikariCP:5.1.0
|    |    |    \--- org.slf4j:slf4j-api:1.7.36 -> 2.0.16
|    |    \--- org.springframework:spring-jdbc:6.2.1
|    |         +--- org.springframework:spring-beans:6.2.1 (*)
|    |         +--- org.springframework:spring-core:6.2.1 (*)
|    |         \--- org.springframework:spring-tx:6.2.1
|    |              +--- org.springframework:spring-beans:6.2.1 (*)
|    |              \--- org.springframework:spring-core:6.2.1 (*)
|    +--- org.hibernate.orm:hibernate-core:6.6.4.Final
|    |    +--- jakarta.persistence:jakarta.persistence-api:3.1.0
|    |    +--- jakarta.transaction:jakarta.transaction-api:2.0.1
|    |    +--- org.jboss.logging:jboss-logging:3.5.0.Final -> 3.6.1.Final
|    |    +--- org.hibernate.common:hibernate-commons-annotations:7.0.3.Final
|    |    +--- io.smallrye:jandex:3.2.0
|    |    +--- com.fasterxml:classmate:1.5.1 -> 1.7.0
|    |    +--- net.bytebuddy:byte-buddy:1.14.18 -> 1.15.11
|    |    +--- jakarta.xml.bind:jakarta.xml.bind-api:4.0.0 -> 4.0.2
|    |    |    \--- jakarta.activation:jakarta.activation-api:2.1.3
|    |    +--- org.glassfish.jaxb:jaxb-runtime:4.0.2 -> 4.0.5
|    |    |    \--- org.glassfish.jaxb:jaxb-core:4.0.5
|    |    |         +--- jakarta.xml.bind:jakarta.xml.bind-api:4.0.2 (*)
|    |    |         +--- jakarta.activation:jakarta.activation-api:2.1.3
|    |    |         +--- org.eclipse.angus:angus-activation:2.0.2
|    |    |         |    \--- jakarta.activation:jakarta.activation-api:2.1.3
|    |    |         +--- org.glassfish.jaxb:txw2:4.0.5
|    |    |         \--- com.sun.istack:istack-commons-runtime:4.1.2
|    |    +--- jakarta.inject:jakarta.inject-api:2.0.1
|    |    \--- org.antlr:antlr4-runtime:4.13.0
|    +--- org.springframework.data:spring-data-jpa:3.4.1
|    |    +--- org.springframework.data:spring-data-commons:3.4.1
|    |    |    +--- org.springframework:spring-core:6.2.1 (*)
|    |    |    +--- org.springframework:spring-beans:6.2.1 (*)
|    |    |    \--- org.slf4j:slf4j-api:2.0.2 -> 2.0.16
|    |    +--- org.springframework:spring-orm:6.2.1
|    |    |    +--- org.springframework:spring-beans:6.2.1 (*)
|    |    |    +--- org.springframework:spring-core:6.2.1 (*)
|    |    |    +--- org.springframework:spring-jdbc:6.2.1 (*)
|    |    |    \--- org.springframework:spring-tx:6.2.1 (*)
|    |    +--- org.springframework:spring-context:6.2.1 (*)
|    |    +--- org.springframework:spring-aop:6.2.1 (*)
|    |    +--- org.springframework:spring-tx:6.2.1 (*)
|    |    +--- org.springframework:spring-beans:6.2.1 (*)
|    |    +--- org.springframework:spring-core:6.2.1 (*)
|    |    +--- org.antlr:antlr4-runtime:4.13.0
|    |    +--- jakarta.annotation:jakarta.annotation-api:2.0.0 -> 2.1.1
|    |    \--- org.slf4j:slf4j-api:2.0.2 -> 2.0.16
|    \--- org.springframework:spring-aspects:6.2.1
|         \--- org.aspectj:aspectjweaver:1.9.22.1
+--- org.springframework.boot:spring-boot-starter-data-rest -> 3.4.1
|    +--- org.springframework.boot:spring-boot-starter-web:3.4.1
|    |    +--- org.springframework.boot:spring-boot-starter:3.4.1 (*)
|    |    +--- org.springframework.boot:spring-boot-starter-json:3.4.1
|    |    |    +--- org.springframework.boot:spring-boot-starter:3.4.1 (*)
|    |    |    +--- org.springframework:spring-web:6.2.1
|    |    |    |    +--- org.springframework:spring-beans:6.2.1 (*)
|    |    |    |    +--- org.springframework:spring-core:6.2.1 (*)
|    |    |    |    \--- io.micrometer:micrometer-observation:1.14.2 (*)
|    |    |    +--- com.fasterxml.jackson.core:jackson-databind:2.18.2
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-annotations:2.18.2
|    |    |    |    |    \--- com.fasterxml.jackson:jackson-bom:2.18.2
|    |    |    |    |         +--- com.fasterxml.jackson.core:jackson-annotations:2.18.2 (c)
|    |    |    |    |         +--- com.fasterxml.jackson.core:jackson-core:2.18.2 (c)
|    |    |    |    |         +--- com.fasterxml.jackson.core:jackson-databind:2.18.2 (c)
|    |    |    |    |         +--- com.fasterxml.jackson.datatype:jackson-datatype-jdk8:2.18.2 (c)
|    |    |    |    |         +--- com.fasterxml.jackson.datatype:jackson-datatype-jsr310:2.18.2 (c)
|    |    |    |    |         +--- com.fasterxml.jackson.module:jackson-module-parameter-names:2.18.2 (c)
|    |    |    |    |         \--- com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:2.18.2 (c)
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-core:2.18.2
|    |    |    |    |    \--- com.fasterxml.jackson:jackson-bom:2.18.2 (*)
|    |    |    |    \--- com.fasterxml.jackson:jackson-bom:2.18.2 (*)
|    |    |    +--- com.fasterxml.jackson.datatype:jackson-datatype-jdk8:2.18.2
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-core:2.18.2 (*)
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-databind:2.18.2 (*)
|    |    |    |    \--- com.fasterxml.jackson:jackson-bom:2.18.2 (*)
|    |    |    +--- com.fasterxml.jackson.datatype:jackson-datatype-jsr310:2.18.2
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-annotations:2.18.2 (*)
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-core:2.18.2 (*)
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-databind:2.18.2 (*)
|    |    |    |    \--- com.fasterxml.jackson:jackson-bom:2.18.2 (*)
|    |    |    \--- com.fasterxml.jackson.module:jackson-module-parameter-names:2.18.2
|    |    |         +--- com.fasterxml.jackson.core:jackson-core:2.18.2 (*)
|    |    |         +--- com.fasterxml.jackson.core:jackson-databind:2.18.2 (*)
|    |    |         \--- com.fasterxml.jackson:jackson-bom:2.18.2 (*)
|    |    +--- org.springframework.boot:spring-boot-starter-tomcat:3.4.1
|    |    |    +--- jakarta.annotation:jakarta.annotation-api:2.1.1
|    |    |    +--- org.apache.tomcat.embed:tomcat-embed-core:10.1.34
|    |    |    +--- org.apache.tomcat.embed:tomcat-embed-el:10.1.34
|    |    |    \--- org.apache.tomcat.embed:tomcat-embed-websocket:10.1.34
|    |    |         \--- org.apache.tomcat.embed:tomcat-embed-core:10.1.34
|    |    +--- org.springframework:spring-web:6.2.1 (*)
|    |    \--- org.springframework:spring-webmvc:6.2.1
|    |         +--- org.springframework:spring-aop:6.2.1 (*)
|    |         +--- org.springframework:spring-beans:6.2.1 (*)
|    |         +--- org.springframework:spring-context:6.2.1 (*)
|    |         +--- org.springframework:spring-core:6.2.1 (*)
|    |         +--- org.springframework:spring-expression:6.2.1 (*)
|    |         \--- org.springframework:spring-web:6.2.1 (*)
|    \--- org.springframework.data:spring-data-rest-webmvc:4.4.1
|         +--- org.springframework.data:spring-data-rest-core:4.4.1
|         |    +--- org.springframework:spring-tx:6.2.1 (*)
|         |    +--- org.springframework.hateoas:spring-hateoas:2.4.1
|         |    |    +--- org.springframework:spring-aop:6.2.1 (*)
|         |    |    +--- org.springframework:spring-beans:6.2.1 (*)
|         |    |    +--- org.springframework:spring-context:6.2.1 (*)
|         |    |    +--- org.springframework:spring-core:6.2.1 (*)
|         |    |    +--- org.springframework:spring-web:6.2.1 (*)
|         |    |    +--- org.springframework.plugin:spring-plugin-core:3.0.0
|         |    |    |    +--- org.springframework:spring-beans:6.0.0 -> 6.2.1 (*)
|         |    |    |    +--- org.springframework:spring-context:6.0.0 -> 6.2.1 (*)
|         |    |    |    +--- org.springframework:spring-aop:6.0.0 -> 6.2.1 (*)
|         |    |    |    \--- org.slf4j:slf4j-api:2.0.3 -> 2.0.16
|         |    |    +--- com.jayway.jsonpath:json-path:2.9.0
|         |    |    |    +--- net.minidev:json-smart:2.5.0 -> 2.5.1
|         |    |    |    |    \--- net.minidev:accessors-smart:2.5.1
|         |    |    |    |         \--- org.ow2.asm:asm:9.6
|         |    |    |    \--- org.slf4j:slf4j-api:2.0.11 -> 2.0.16
|         |    |    \--- org.slf4j:slf4j-api:2.0.16
|         |    +--- org.springframework.data:spring-data-commons:3.4.1 (*)
|         |    +--- org.springframework.plugin:spring-plugin-core:3.0.0 (*)
|         |    +--- org.atteo:evo-inflector:1.3
|         |    +--- com.fasterxml.jackson.core:jackson-annotations:2.18.2 (*)
|         |    +--- com.fasterxml.jackson.datatype:jackson-datatype-jdk8:2.18.2 (*)
|         |    \--- org.slf4j:slf4j-api:2.0.2 -> 2.0.16
|         +--- org.springframework:spring-webmvc:6.2.1 (*)
|         +--- com.fasterxml.jackson.core:jackson-databind:2.18.2 (*)
|         +--- com.fasterxml.jackson.core:jackson-annotations:2.18.2 (*)
|         \--- org.slf4j:slf4j-api:2.0.2 -> 2.0.16
+--- org.springframework.boot:spring-boot-starter-web -> 3.4.1 (*)
+--- org.springdoc:springdoc-openapi-starter-webmvc-ui:2.8.3
|    +--- org.springdoc:springdoc-openapi-starter-webmvc-api:2.8.3
|    |    +--- org.springdoc:springdoc-openapi-starter-common:2.8.3
|    |    |    +--- org.springframework.boot:spring-boot-autoconfigure:3.4.1 (*)
|    |    |    \--- io.swagger.core.v3:swagger-core-jakarta:2.2.27
|    |    |         +--- org.apache.commons:commons-lang3:3.17.0
|    |    |         +--- org.slf4j:slf4j-api:2.0.9 -> 2.0.16
|    |    |         +--- io.swagger.core.v3:swagger-annotations-jakarta:2.2.27
|    |    |         +--- io.swagger.core.v3:swagger-models-jakarta:2.2.27
|    |    |         |    \--- com.fasterxml.jackson.core:jackson-annotations:2.16.2 -> 2.18.2 (*)
|    |    |         +--- org.yaml:snakeyaml:2.3
|    |    |         +--- jakarta.xml.bind:jakarta.xml.bind-api:3.0.1 -> 4.0.2 (*)
|    |    |         +--- jakarta.validation:jakarta.validation-api:3.1.0 -> 3.0.2
|    |    |         +--- com.fasterxml.jackson.core:jackson-annotations:2.16.2 -> 2.18.2 (*)
|    |    |         +--- com.fasterxml.jackson.core:jackson-databind:2.16.2 -> 2.18.2 (*)
|    |    |         +--- com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:2.16.2 -> 2.18.2
|    |    |         |    +--- com.fasterxml.jackson.core:jackson-databind:2.18.2 (*)
|    |    |         |    +--- org.yaml:snakeyaml:2.3
|    |    |         |    +--- com.fasterxml.jackson.core:jackson-core:2.18.2 (*)
|    |    |         |    \--- com.fasterxml.jackson:jackson-bom:2.18.2 (*)
|    |    |         \--- com.fasterxml.jackson.datatype:jackson-datatype-jsr310:2.16.2 -> 2.18.2 (*)
|    |    \--- org.springframework:spring-webmvc:6.2.1 (*)
|    +--- org.webjars:swagger-ui:5.18.2
|    \--- org.webjars:webjars-locator-lite:1.0.1
|         \--- org.jspecify:jspecify:1.0.0
\--- com.h2database:h2 -> 2.3.232

runtimeElements - Runtime elements for the 'main' feature. (n)
No dependencies

runtimeOnly - Runtime-only dependencies for the 'main' feature. (n)
\--- com.h2database:h2 (n)

testAndDevelopmentOnly - Configuration for test and development-only dependencies such as Spring Boot's DevTools.
No dependencies

testAnnotationProcessor - Annotation processors and their dependencies for source set 'test'.
No dependencies

testCompileClasspath - Compile classpath for source set 'test'.
+--- org.springframework.boot:spring-boot-starter-data-jpa -> 3.4.1
|    +--- org.springframework.boot:spring-boot-starter:3.4.1
|    |    +--- org.springframework.boot:spring-boot:3.4.1
|    |    |    +--- org.springframework:spring-core:6.2.1
|    |    |    |    \--- org.springframework:spring-jcl:6.2.1
|    |    |    \--- org.springframework:spring-context:6.2.1
|    |    |         +--- org.springframework:spring-aop:6.2.1
|    |    |         |    +--- org.springframework:spring-beans:6.2.1
|    |    |         |    |    \--- org.springframework:spring-core:6.2.1 (*)
|    |    |         |    \--- org.springframework:spring-core:6.2.1 (*)
|    |    |         +--- org.springframework:spring-beans:6.2.1 (*)
|    |    |         +--- org.springframework:spring-core:6.2.1 (*)
|    |    |         +--- org.springframework:spring-expression:6.2.1
|    |    |         |    \--- org.springframework:spring-core:6.2.1 (*)
|    |    |         \--- io.micrometer:micrometer-observation:1.14.2
|    |    |              \--- io.micrometer:micrometer-commons:1.14.2
|    |    +--- org.springframework.boot:spring-boot-autoconfigure:3.4.1
|    |    |    \--- org.springframework.boot:spring-boot:3.4.1 (*)
|    |    +--- org.springframework.boot:spring-boot-starter-logging:3.4.1
|    |    |    +--- ch.qos.logback:logback-classic:1.5.12
|    |    |    |    +--- ch.qos.logback:logback-core:1.5.12
|    |    |    |    \--- org.slf4j:slf4j-api:2.0.15 -> 2.0.16
|    |    |    +--- org.apache.logging.log4j:log4j-to-slf4j:2.24.3
|    |    |    |    +--- org.apache.logging.log4j:log4j-api:2.24.3
|    |    |    |    \--- org.slf4j:slf4j-api:2.0.16
|    |    |    \--- org.slf4j:jul-to-slf4j:2.0.16
|    |    |         \--- org.slf4j:slf4j-api:2.0.16
|    |    +--- jakarta.annotation:jakarta.annotation-api:2.1.1
|    |    +--- org.springframework:spring-core:6.2.1 (*)
|    |    \--- org.yaml:snakeyaml:2.3
|    +--- org.springframework.boot:spring-boot-starter-jdbc:3.4.1
|    |    +--- org.springframework.boot:spring-boot-starter:3.4.1 (*)
|    |    +--- com.zaxxer:HikariCP:5.1.0
|    |    |    \--- org.slf4j:slf4j-api:1.7.36 -> 2.0.16
|    |    \--- org.springframework:spring-jdbc:6.2.1
|    |         +--- org.springframework:spring-beans:6.2.1 (*)
|    |         +--- org.springframework:spring-core:6.2.1 (*)
|    |         \--- org.springframework:spring-tx:6.2.1
|    |              +--- org.springframework:spring-beans:6.2.1 (*)
|    |              \--- org.springframework:spring-core:6.2.1 (*)
|    +--- org.hibernate.orm:hibernate-core:6.6.4.Final
|    |    +--- jakarta.persistence:jakarta.persistence-api:3.1.0
|    |    \--- jakarta.transaction:jakarta.transaction-api:2.0.1
|    +--- org.springframework.data:spring-data-jpa:3.4.1
|    |    +--- org.springframework.data:spring-data-commons:3.4.1
|    |    |    +--- org.springframework:spring-core:6.2.1 (*)
|    |    |    +--- org.springframework:spring-beans:6.2.1 (*)
|    |    |    \--- org.slf4j:slf4j-api:2.0.2 -> 2.0.16
|    |    +--- org.springframework:spring-orm:6.2.1
|    |    |    +--- org.springframework:spring-beans:6.2.1 (*)
|    |    |    +--- org.springframework:spring-core:6.2.1 (*)
|    |    |    +--- org.springframework:spring-jdbc:6.2.1 (*)
|    |    |    \--- org.springframework:spring-tx:6.2.1 (*)
|    |    +--- org.springframework:spring-context:6.2.1 (*)
|    |    +--- org.springframework:spring-aop:6.2.1 (*)
|    |    +--- org.springframework:spring-tx:6.2.1 (*)
|    |    +--- org.springframework:spring-beans:6.2.1 (*)
|    |    +--- org.springframework:spring-core:6.2.1 (*)
|    |    +--- org.antlr:antlr4-runtime:4.13.0
|    |    +--- jakarta.annotation:jakarta.annotation-api:2.0.0 -> 2.1.1
|    |    \--- org.slf4j:slf4j-api:2.0.2 -> 2.0.16
|    \--- org.springframework:spring-aspects:6.2.1
|         \--- org.aspectj:aspectjweaver:1.9.22.1
+--- org.springframework.boot:spring-boot-starter-data-rest -> 3.4.1
|    +--- org.springframework.boot:spring-boot-starter-web:3.4.1
|    |    +--- org.springframework.boot:spring-boot-starter:3.4.1 (*)
|    |    +--- org.springframework.boot:spring-boot-starter-json:3.4.1
|    |    |    +--- org.springframework.boot:spring-boot-starter:3.4.1 (*)
|    |    |    +--- org.springframework:spring-web:6.2.1
|    |    |    |    +--- org.springframework:spring-beans:6.2.1 (*)
|    |    |    |    +--- org.springframework:spring-core:6.2.1 (*)
|    |    |    |    \--- io.micrometer:micrometer-observation:1.14.2 (*)
|    |    |    +--- com.fasterxml.jackson.core:jackson-databind:2.18.2
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-annotations:2.18.2
|    |    |    |    |    \--- com.fasterxml.jackson:jackson-bom:2.18.2
|    |    |    |    |         +--- com.fasterxml.jackson.core:jackson-annotations:2.18.2 (c)
|    |    |    |    |         +--- com.fasterxml.jackson.core:jackson-core:2.18.2 (c)
|    |    |    |    |         +--- com.fasterxml.jackson.core:jackson-databind:2.18.2 (c)
|    |    |    |    |         +--- com.fasterxml.jackson.datatype:jackson-datatype-jdk8:2.18.2 (c)
|    |    |    |    |         +--- com.fasterxml.jackson.datatype:jackson-datatype-jsr310:2.18.2 (c)
|    |    |    |    |         +--- com.fasterxml.jackson.module:jackson-module-parameter-names:2.18.2 (c)
|    |    |    |    |         \--- com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:2.18.2 (c)
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-core:2.18.2
|    |    |    |    |    \--- com.fasterxml.jackson:jackson-bom:2.18.2 (*)
|    |    |    |    \--- com.fasterxml.jackson:jackson-bom:2.18.2 (*)
|    |    |    +--- com.fasterxml.jackson.datatype:jackson-datatype-jdk8:2.18.2
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-core:2.18.2 (*)
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-databind:2.18.2 (*)
|    |    |    |    \--- com.fasterxml.jackson:jackson-bom:2.18.2 (*)
|    |    |    +--- com.fasterxml.jackson.datatype:jackson-datatype-jsr310:2.18.2
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-annotations:2.18.2 (*)
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-core:2.18.2 (*)
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-databind:2.18.2 (*)
|    |    |    |    \--- com.fasterxml.jackson:jackson-bom:2.18.2 (*)
|    |    |    \--- com.fasterxml.jackson.module:jackson-module-parameter-names:2.18.2
|    |    |         +--- com.fasterxml.jackson.core:jackson-core:2.18.2 (*)
|    |    |         +--- com.fasterxml.jackson.core:jackson-databind:2.18.2 (*)
|    |    |         \--- com.fasterxml.jackson:jackson-bom:2.18.2 (*)
|    |    +--- org.springframework.boot:spring-boot-starter-tomcat:3.4.1
|    |    |    +--- jakarta.annotation:jakarta.annotation-api:2.1.1
|    |    |    +--- org.apache.tomcat.embed:tomcat-embed-core:10.1.34
|    |    |    +--- org.apache.tomcat.embed:tomcat-embed-el:10.1.34
|    |    |    \--- org.apache.tomcat.embed:tomcat-embed-websocket:10.1.34
|    |    |         \--- org.apache.tomcat.embed:tomcat-embed-core:10.1.34
|    |    +--- org.springframework:spring-web:6.2.1 (*)
|    |    \--- org.springframework:spring-webmvc:6.2.1
|    |         +--- org.springframework:spring-aop:6.2.1 (*)
|    |         +--- org.springframework:spring-beans:6.2.1 (*)
|    |         +--- org.springframework:spring-context:6.2.1 (*)
|    |         +--- org.springframework:spring-core:6.2.1 (*)
|    |         +--- org.springframework:spring-expression:6.2.1 (*)
|    |         \--- org.springframework:spring-web:6.2.1 (*)
|    \--- org.springframework.data:spring-data-rest-webmvc:4.4.1
|         +--- org.springframework.data:spring-data-rest-core:4.4.1
|         |    +--- org.springframework:spring-tx:6.2.1 (*)
|         |    +--- org.springframework.hateoas:spring-hateoas:2.4.1
|         |    |    +--- org.springframework:spring-aop:6.2.1 (*)
|         |    |    +--- org.springframework:spring-beans:6.2.1 (*)
|         |    |    +--- org.springframework:spring-context:6.2.1 (*)
|         |    |    +--- org.springframework:spring-core:6.2.1 (*)
|         |    |    +--- org.springframework:spring-web:6.2.1 (*)
|         |    |    +--- org.springframework.plugin:spring-plugin-core:3.0.0
|         |    |    |    +--- org.springframework:spring-beans:6.0.0 -> 6.2.1 (*)
|         |    |    |    +--- org.springframework:spring-context:6.0.0 -> 6.2.1 (*)
|         |    |    |    +--- org.springframework:spring-aop:6.0.0 -> 6.2.1 (*)
|         |    |    |    \--- org.slf4j:slf4j-api:2.0.3 -> 2.0.16
|         |    |    +--- com.jayway.jsonpath:json-path:2.9.0
|         |    |    \--- org.slf4j:slf4j-api:2.0.16
|         |    +--- org.springframework.data:spring-data-commons:3.4.1 (*)
|         |    +--- org.springframework.plugin:spring-plugin-core:3.0.0 (*)
|         |    +--- org.atteo:evo-inflector:1.3
|         |    +--- com.fasterxml.jackson.core:jackson-annotations:2.18.2 (*)
|         |    +--- com.fasterxml.jackson.datatype:jackson-datatype-jdk8:2.18.2 (*)
|         |    \--- org.slf4j:slf4j-api:2.0.2 -> 2.0.16
|         +--- org.springframework:spring-webmvc:6.2.1 (*)
|         +--- com.fasterxml.jackson.core:jackson-databind:2.18.2 (*)
|         +--- com.fasterxml.jackson.core:jackson-annotations:2.18.2 (*)
|         \--- org.slf4j:slf4j-api:2.0.2 -> 2.0.16
+--- org.springframework.boot:spring-boot-starter-web -> 3.4.1 (*)
+--- org.springdoc:springdoc-openapi-starter-webmvc-ui:2.8.3
|    +--- org.springdoc:springdoc-openapi-starter-webmvc-api:2.8.3
|    |    +--- org.springdoc:springdoc-openapi-starter-common:2.8.3
|    |    |    +--- org.springframework.boot:spring-boot-autoconfigure:3.4.1 (*)
|    |    |    \--- io.swagger.core.v3:swagger-core-jakarta:2.2.27
|    |    |         +--- org.apache.commons:commons-lang3:3.17.0
|    |    |         +--- org.slf4j:slf4j-api:2.0.9 -> 2.0.16
|    |    |         +--- io.swagger.core.v3:swagger-annotations-jakarta:2.2.27
|    |    |         +--- io.swagger.core.v3:swagger-models-jakarta:2.2.27
|    |    |         |    \--- com.fasterxml.jackson.core:jackson-annotations:2.16.2 -> 2.18.2 (*)
|    |    |         +--- org.yaml:snakeyaml:2.3
|    |    |         +--- jakarta.xml.bind:jakarta.xml.bind-api:3.0.1 -> 4.0.2
|    |    |         |    \--- jakarta.activation:jakarta.activation-api:2.1.3
|    |    |         +--- jakarta.validation:jakarta.validation-api:3.1.0 -> 3.0.2
|    |    |         +--- com.fasterxml.jackson.core:jackson-annotations:2.16.2 -> 2.18.2 (*)
|    |    |         +--- com.fasterxml.jackson.core:jackson-databind:2.16.2 -> 2.18.2 (*)
|    |    |         +--- com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:2.16.2 -> 2.18.2
|    |    |         |    +--- com.fasterxml.jackson.core:jackson-databind:2.18.2 (*)
|    |    |         |    +--- org.yaml:snakeyaml:2.3
|    |    |         |    +--- com.fasterxml.jackson.core:jackson-core:2.18.2 (*)
|    |    |         |    \--- com.fasterxml.jackson:jackson-bom:2.18.2 (*)
|    |    |         \--- com.fasterxml.jackson.datatype:jackson-datatype-jsr310:2.16.2 -> 2.18.2 (*)
|    |    \--- org.springframework:spring-webmvc:6.2.1 (*)
|    +--- org.webjars:swagger-ui:5.18.2
|    \--- org.webjars:webjars-locator-lite:1.0.1
|         \--- org.jspecify:jspecify:1.0.0
\--- org.springframework.boot:spring-boot-starter-test -> 3.4.1
     +--- org.springframework.boot:spring-boot-starter:3.4.1 (*)
     +--- org.springframework.boot:spring-boot-test:3.4.1
     |    +--- org.springframework.boot:spring-boot:3.4.1 (*)
     |    \--- org.springframework:spring-test:6.2.1
     |         \--- org.springframework:spring-core:6.2.1 (*)
     +--- org.springframework.boot:spring-boot-test-autoconfigure:3.4.1
     |    +--- org.springframework.boot:spring-boot:3.4.1 (*)
     |    +--- org.springframework.boot:spring-boot-test:3.4.1 (*)
     |    \--- org.springframework.boot:spring-boot-autoconfigure:3.4.1 (*)
     +--- com.jayway.jsonpath:json-path:2.9.0
     +--- jakarta.xml.bind:jakarta.xml.bind-api:4.0.2 (*)
     +--- net.minidev:json-smart:2.5.1
     |    \--- net.minidev:accessors-smart:2.5.1
     |         \--- org.ow2.asm:asm:9.6
     +--- org.assertj:assertj-core:3.26.3
     |    \--- net.bytebuddy:byte-buddy:1.14.18 -> 1.15.11
     +--- org.awaitility:awaitility:4.2.2
     |    \--- org.hamcrest:hamcrest:2.1 -> 2.2
     +--- org.hamcrest:hamcrest:2.2
     +--- org.junit.jupiter:junit-jupiter:5.11.4
     |    +--- org.junit:junit-bom:5.11.4
     |    |    +--- org.junit.jupiter:junit-jupiter:5.11.4 (c)
     |    |    +--- org.junit.jupiter:junit-jupiter-api:5.11.4 (c)
     |    |    +--- org.junit.jupiter:junit-jupiter-params:5.11.4 (c)
     |    |    \--- org.junit.platform:junit-platform-commons:1.11.4 (c)
     |    +--- org.junit.jupiter:junit-jupiter-api:5.11.4
     |    |    +--- org.junit:junit-bom:5.11.4 (*)
     |    |    +--- org.opentest4j:opentest4j:1.3.0
     |    |    +--- org.junit.platform:junit-platform-commons:1.11.4
     |    |    |    +--- org.junit:junit-bom:5.11.4 (*)
     |    |    |    \--- org.apiguardian:apiguardian-api:1.1.2
     |    |    \--- org.apiguardian:apiguardian-api:1.1.2
     |    \--- org.junit.jupiter:junit-jupiter-params:5.11.4
     |         +--- org.junit:junit-bom:5.11.4 (*)
     |         +--- org.junit.jupiter:junit-jupiter-api:5.11.4 (*)
     |         \--- org.apiguardian:apiguardian-api:1.1.2
     +--- org.mockito:mockito-core:5.14.2
     |    +--- net.bytebuddy:byte-buddy:1.15.4 -> 1.15.11
     |    \--- net.bytebuddy:byte-buddy-agent:1.15.4 -> 1.15.11
     +--- org.mockito:mockito-junit-jupiter:5.14.2
     |    \--- org.mockito:mockito-core:5.14.2 (*)
     +--- org.skyscreamer:jsonassert:1.5.3
     |    \--- com.vaadin.external.google:android-json:0.0.20131108.vaadin1
     +--- org.springframework:spring-core:6.2.1 (*)
     +--- org.springframework:spring-test:6.2.1 (*)
     \--- org.xmlunit:xmlunit-core:2.10.0

testCompileOnly - Compile only dependencies for source set 'test'. (n)
No dependencies

testImplementation - Implementation only dependencies for source set 'test'. (n)
\--- org.springframework.boot:spring-boot-starter-test (n)

testRuntimeClasspath - Runtime classpath of source set 'test'.
+--- org.springframework.boot:spring-boot-starter-data-jpa -> 3.4.1
|    +--- org.springframework.boot:spring-boot-starter:3.4.1
|    |    +--- org.springframework.boot:spring-boot:3.4.1
|    |    |    +--- org.springframework:spring-core:6.2.1
|    |    |    |    \--- org.springframework:spring-jcl:6.2.1
|    |    |    \--- org.springframework:spring-context:6.2.1
|    |    |         +--- org.springframework:spring-aop:6.2.1
|    |    |         |    +--- org.springframework:spring-beans:6.2.1
|    |    |         |    |    \--- org.springframework:spring-core:6.2.1 (*)
|    |    |         |    \--- org.springframework:spring-core:6.2.1 (*)
|    |    |         +--- org.springframework:spring-beans:6.2.1 (*)
|    |    |         +--- org.springframework:spring-core:6.2.1 (*)
|    |    |         +--- org.springframework:spring-expression:6.2.1
|    |    |         |    \--- org.springframework:spring-core:6.2.1 (*)
|    |    |         \--- io.micrometer:micrometer-observation:1.14.2
|    |    |              \--- io.micrometer:micrometer-commons:1.14.2
|    |    +--- org.springframework.boot:spring-boot-autoconfigure:3.4.1
|    |    |    \--- org.springframework.boot:spring-boot:3.4.1 (*)
|    |    +--- org.springframework.boot:spring-boot-starter-logging:3.4.1
|    |    |    +--- ch.qos.logback:logback-classic:1.5.12
|    |    |    |    +--- ch.qos.logback:logback-core:1.5.12
|    |    |    |    \--- org.slf4j:slf4j-api:2.0.15 -> 2.0.16
|    |    |    +--- org.apache.logging.log4j:log4j-to-slf4j:2.24.3
|    |    |    |    +--- org.apache.logging.log4j:log4j-api:2.24.3
|    |    |    |    \--- org.slf4j:slf4j-api:2.0.16
|    |    |    \--- org.slf4j:jul-to-slf4j:2.0.16
|    |    |         \--- org.slf4j:slf4j-api:2.0.16
|    |    +--- jakarta.annotation:jakarta.annotation-api:2.1.1
|    |    +--- org.springframework:spring-core:6.2.1 (*)
|    |    \--- org.yaml:snakeyaml:2.3
|    +--- org.springframework.boot:spring-boot-starter-jdbc:3.4.1
|    |    +--- org.springframework.boot:spring-boot-starter:3.4.1 (*)
|    |    +--- com.zaxxer:HikariCP:5.1.0
|    |    |    \--- org.slf4j:slf4j-api:1.7.36 -> 2.0.16
|    |    \--- org.springframework:spring-jdbc:6.2.1
|    |         +--- org.springframework:spring-beans:6.2.1 (*)
|    |         +--- org.springframework:spring-core:6.2.1 (*)
|    |         \--- org.springframework:spring-tx:6.2.1
|    |              +--- org.springframework:spring-beans:6.2.1 (*)
|    |              \--- org.springframework:spring-core:6.2.1 (*)
|    +--- org.hibernate.orm:hibernate-core:6.6.4.Final
|    |    +--- jakarta.persistence:jakarta.persistence-api:3.1.0
|    |    +--- jakarta.transaction:jakarta.transaction-api:2.0.1
|    |    +--- org.jboss.logging:jboss-logging:3.5.0.Final -> 3.6.1.Final
|    |    +--- org.hibernate.common:hibernate-commons-annotations:7.0.3.Final
|    |    +--- io.smallrye:jandex:3.2.0
|    |    +--- com.fasterxml:classmate:1.5.1 -> 1.7.0
|    |    +--- net.bytebuddy:byte-buddy:1.14.18 -> 1.15.11
|    |    +--- jakarta.xml.bind:jakarta.xml.bind-api:4.0.0 -> 4.0.2
|    |    |    \--- jakarta.activation:jakarta.activation-api:2.1.3
|    |    +--- org.glassfish.jaxb:jaxb-runtime:4.0.2 -> 4.0.5
|    |    |    \--- org.glassfish.jaxb:jaxb-core:4.0.5
|    |    |         +--- jakarta.xml.bind:jakarta.xml.bind-api:4.0.2 (*)
|    |    |         +--- jakarta.activation:jakarta.activation-api:2.1.3
|    |    |         +--- org.eclipse.angus:angus-activation:2.0.2
|    |    |         |    \--- jakarta.activation:jakarta.activation-api:2.1.3
|    |    |         +--- org.glassfish.jaxb:txw2:4.0.5
|    |    |         \--- com.sun.istack:istack-commons-runtime:4.1.2
|    |    +--- jakarta.inject:jakarta.inject-api:2.0.1
|    |    \--- org.antlr:antlr4-runtime:4.13.0
|    +--- org.springframework.data:spring-data-jpa:3.4.1
|    |    +--- org.springframework.data:spring-data-commons:3.4.1
|    |    |    +--- org.springframework:spring-core:6.2.1 (*)
|    |    |    +--- org.springframework:spring-beans:6.2.1 (*)
|    |    |    \--- org.slf4j:slf4j-api:2.0.2 -> 2.0.16
|    |    +--- org.springframework:spring-orm:6.2.1
|    |    |    +--- org.springframework:spring-beans:6.2.1 (*)
|    |    |    +--- org.springframework:spring-core:6.2.1 (*)
|    |    |    +--- org.springframework:spring-jdbc:6.2.1 (*)
|    |    |    \--- org.springframework:spring-tx:6.2.1 (*)
|    |    +--- org.springframework:spring-context:6.2.1 (*)
|    |    +--- org.springframework:spring-aop:6.2.1 (*)
|    |    +--- org.springframework:spring-tx:6.2.1 (*)
|    |    +--- org.springframework:spring-beans:6.2.1 (*)
|    |    +--- org.springframework:spring-core:6.2.1 (*)
|    |    +--- org.antlr:antlr4-runtime:4.13.0
|    |    +--- jakarta.annotation:jakarta.annotation-api:2.0.0 -> 2.1.1
|    |    \--- org.slf4j:slf4j-api:2.0.2 -> 2.0.16
|    \--- org.springframework:spring-aspects:6.2.1
|         \--- org.aspectj:aspectjweaver:1.9.22.1
+--- org.springframework.boot:spring-boot-starter-data-rest -> 3.4.1
|    +--- org.springframework.boot:spring-boot-starter-web:3.4.1
|    |    +--- org.springframework.boot:spring-boot-starter:3.4.1 (*)
|    |    +--- org.springframework.boot:spring-boot-starter-json:3.4.1
|    |    |    +--- org.springframework.boot:spring-boot-starter:3.4.1 (*)
|    |    |    +--- org.springframework:spring-web:6.2.1
|    |    |    |    +--- org.springframework:spring-beans:6.2.1 (*)
|    |    |    |    +--- org.springframework:spring-core:6.2.1 (*)
|    |    |    |    \--- io.micrometer:micrometer-observation:1.14.2 (*)
|    |    |    +--- com.fasterxml.jackson.core:jackson-databind:2.18.2
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-annotations:2.18.2
|    |    |    |    |    \--- com.fasterxml.jackson:jackson-bom:2.18.2
|    |    |    |    |         +--- com.fasterxml.jackson.core:jackson-annotations:2.18.2 (c)
|    |    |    |    |         +--- com.fasterxml.jackson.core:jackson-core:2.18.2 (c)
|    |    |    |    |         +--- com.fasterxml.jackson.core:jackson-databind:2.18.2 (c)
|    |    |    |    |         +--- com.fasterxml.jackson.datatype:jackson-datatype-jdk8:2.18.2 (c)
|    |    |    |    |         +--- com.fasterxml.jackson.datatype:jackson-datatype-jsr310:2.18.2 (c)
|    |    |    |    |         +--- com.fasterxml.jackson.module:jackson-module-parameter-names:2.18.2 (c)
|    |    |    |    |         \--- com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:2.18.2 (c)
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-core:2.18.2
|    |    |    |    |    \--- com.fasterxml.jackson:jackson-bom:2.18.2 (*)
|    |    |    |    \--- com.fasterxml.jackson:jackson-bom:2.18.2 (*)
|    |    |    +--- com.fasterxml.jackson.datatype:jackson-datatype-jdk8:2.18.2
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-core:2.18.2 (*)
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-databind:2.18.2 (*)
|    |    |    |    \--- com.fasterxml.jackson:jackson-bom:2.18.2 (*)
|    |    |    +--- com.fasterxml.jackson.datatype:jackson-datatype-jsr310:2.18.2
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-annotations:2.18.2 (*)
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-core:2.18.2 (*)
|    |    |    |    +--- com.fasterxml.jackson.core:jackson-databind:2.18.2 (*)
|    |    |    |    \--- com.fasterxml.jackson:jackson-bom:2.18.2 (*)
|    |    |    \--- com.fasterxml.jackson.module:jackson-module-parameter-names:2.18.2
|    |    |         +--- com.fasterxml.jackson.core:jackson-core:2.18.2 (*)
|    |    |         +--- com.fasterxml.jackson.core:jackson-databind:2.18.2 (*)
|    |    |         \--- com.fasterxml.jackson:jackson-bom:2.18.2 (*)
|    |    +--- org.springframework.boot:spring-boot-starter-tomcat:3.4.1
|    |    |    +--- jakarta.annotation:jakarta.annotation-api:2.1.1
|    |    |    +--- org.apache.tomcat.embed:tomcat-embed-core:10.1.34
|    |    |    +--- org.apache.tomcat.embed:tomcat-embed-el:10.1.34
|    |    |    \--- org.apache.tomcat.embed:tomcat-embed-websocket:10.1.34
|    |    |         \--- org.apache.tomcat.embed:tomcat-embed-core:10.1.34
|    |    +--- org.springframework:spring-web:6.2.1 (*)
|    |    \--- org.springframework:spring-webmvc:6.2.1
|    |         +--- org.springframework:spring-aop:6.2.1 (*)
|    |         +--- org.springframework:spring-beans:6.2.1 (*)
|    |         +--- org.springframework:spring-context:6.2.1 (*)
|    |         +--- org.springframework:spring-core:6.2.1 (*)
|    |         +--- org.springframework:spring-expression:6.2.1 (*)
|    |         \--- org.springframework:spring-web:6.2.1 (*)
|    \--- org.springframework.data:spring-data-rest-webmvc:4.4.1
|         +--- org.springframework.data:spring-data-rest-core:4.4.1
|         |    +--- org.springframework:spring-tx:6.2.1 (*)
|         |    +--- org.springframework.hateoas:spring-hateoas:2.4.1
|         |    |    +--- org.springframework:spring-aop:6.2.1 (*)
|         |    |    +--- org.springframework:spring-beans:6.2.1 (*)
|         |    |    +--- org.springframework:spring-context:6.2.1 (*)
|         |    |    +--- org.springframework:spring-core:6.2.1 (*)
|         |    |    +--- org.springframework:spring-web:6.2.1 (*)
|         |    |    +--- org.springframework.plugin:spring-plugin-core:3.0.0
|         |    |    |    +--- org.springframework:spring-beans:6.0.0 -> 6.2.1 (*)
|         |    |    |    +--- org.springframework:spring-context:6.0.0 -> 6.2.1 (*)
|         |    |    |    +--- org.springframework:spring-aop:6.0.0 -> 6.2.1 (*)
|         |    |    |    \--- org.slf4j:slf4j-api:2.0.3 -> 2.0.16
|         |    |    +--- com.jayway.jsonpath:json-path:2.9.0
|         |    |    |    +--- net.minidev:json-smart:2.5.0 -> 2.5.1
|         |    |    |    |    \--- net.minidev:accessors-smart:2.5.1
|         |    |    |    |         \--- org.ow2.asm:asm:9.6
|         |    |    |    \--- org.slf4j:slf4j-api:2.0.11 -> 2.0.16
|         |    |    \--- org.slf4j:slf4j-api:2.0.16
|         |    +--- org.springframework.data:spring-data-commons:3.4.1 (*)
|         |    +--- org.springframework.plugin:spring-plugin-core:3.0.0 (*)
|         |    +--- org.atteo:evo-inflector:1.3
|         |    +--- com.fasterxml.jackson.core:jackson-annotations:2.18.2 (*)
|         |    +--- com.fasterxml.jackson.datatype:jackson-datatype-jdk8:2.18.2 (*)
|         |    \--- org.slf4j:slf4j-api:2.0.2 -> 2.0.16
|         +--- org.springframework:spring-webmvc:6.2.1 (*)
|         +--- com.fasterxml.jackson.core:jackson-databind:2.18.2 (*)
|         +--- com.fasterxml.jackson.core:jackson-annotations:2.18.2 (*)
|         \--- org.slf4j:slf4j-api:2.0.2 -> 2.0.16
+--- org.springframework.boot:spring-boot-starter-web -> 3.4.1 (*)
+--- org.springdoc:springdoc-openapi-starter-webmvc-ui:2.8.3
|    +--- org.springdoc:springdoc-openapi-starter-webmvc-api:2.8.3
|    |    +--- org.springdoc:springdoc-openapi-starter-common:2.8.3
|    |    |    +--- org.springframework.boot:spring-boot-autoconfigure:3.4.1 (*)
|    |    |    \--- io.swagger.core.v3:swagger-core-jakarta:2.2.27
|    |    |         +--- org.apache.commons:commons-lang3:3.17.0
|    |    |         +--- org.slf4j:slf4j-api:2.0.9 -> 2.0.16
|    |    |         +--- io.swagger.core.v3:swagger-annotations-jakarta:2.2.27
|    |    |         +--- io.swagger.core.v3:swagger-models-jakarta:2.2.27
|    |    |         |    \--- com.fasterxml.jackson.core:jackson-annotations:2.16.2 -> 2.18.2 (*)
|    |    |         +--- org.yaml:snakeyaml:2.3
|    |    |         +--- jakarta.xml.bind:jakarta.xml.bind-api:3.0.1 -> 4.0.2 (*)
|    |    |         +--- jakarta.validation:jakarta.validation-api:3.1.0 -> 3.0.2
|    |    |         +--- com.fasterxml.jackson.core:jackson-annotations:2.16.2 -> 2.18.2 (*)
|    |    |         +--- com.fasterxml.jackson.core:jackson-databind:2.16.2 -> 2.18.2 (*)
|    |    |         +--- com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:2.16.2 -> 2.18.2
|    |    |         |    +--- com.fasterxml.jackson.core:jackson-databind:2.18.2 (*)
|    |    |         |    +--- org.yaml:snakeyaml:2.3
|    |    |         |    +--- com.fasterxml.jackson.core:jackson-core:2.18.2 (*)
|    |    |         |    \--- com.fasterxml.jackson:jackson-bom:2.18.2 (*)
|    |    |         \--- com.fasterxml.jackson.datatype:jackson-datatype-jsr310:2.16.2 -> 2.18.2 (*)
|    |    \--- org.springframework:spring-webmvc:6.2.1 (*)
|    +--- org.webjars:swagger-ui:5.18.2
|    \--- org.webjars:webjars-locator-lite:1.0.1
|         \--- org.jspecify:jspecify:1.0.0
+--- com.h2database:h2 -> 2.3.232
+--- org.springframework.boot:spring-boot-starter-test -> 3.4.1
|    +--- org.springframework.boot:spring-boot-starter:3.4.1 (*)
|    +--- org.springframework.boot:spring-boot-test:3.4.1
|    |    +--- org.springframework.boot:spring-boot:3.4.1 (*)
|    |    \--- org.springframework:spring-test:6.2.1
|    |         \--- org.springframework:spring-core:6.2.1 (*)
|    +--- org.springframework.boot:spring-boot-test-autoconfigure:3.4.1
|    |    +--- org.springframework.boot:spring-boot:3.4.1 (*)
|    |    +--- org.springframework.boot:spring-boot-test:3.4.1 (*)
|    |    \--- org.springframework.boot:spring-boot-autoconfigure:3.4.1 (*)
|    +--- com.jayway.jsonpath:json-path:2.9.0 (*)
|    +--- jakarta.xml.bind:jakarta.xml.bind-api:4.0.2 (*)
|    +--- net.minidev:json-smart:2.5.1 (*)
|    +--- org.assertj:assertj-core:3.26.3
|    |    \--- net.bytebuddy:byte-buddy:1.14.18 -> 1.15.11
|    +--- org.awaitility:awaitility:4.2.2
|    |    \--- org.hamcrest:hamcrest:2.1 -> 2.2
|    +--- org.hamcrest:hamcrest:2.2
|    +--- org.junit.jupiter:junit-jupiter:5.11.4
|    |    +--- org.junit:junit-bom:5.11.4
|    |    |    +--- org.junit.jupiter:junit-jupiter:5.11.4 (c)
|    |    |    +--- org.junit.jupiter:junit-jupiter-api:5.11.4 (c)
|    |    |    +--- org.junit.jupiter:junit-jupiter-engine:5.11.4 (c)
|    |    |    +--- org.junit.jupiter:junit-jupiter-params:5.11.4 (c)
|    |    |    +--- org.junit.platform:junit-platform-engine:1.11.4 (c)
|    |    |    +--- org.junit.platform:junit-platform-launcher:1.11.4 (c)
|    |    |    \--- org.junit.platform:junit-platform-commons:1.11.4 (c)
|    |    +--- org.junit.jupiter:junit-jupiter-api:5.11.4
|    |    |    +--- org.junit:junit-bom:5.11.4 (*)
|    |    |    +--- org.opentest4j:opentest4j:1.3.0
|    |    |    \--- org.junit.platform:junit-platform-commons:1.11.4
|    |    |         \--- org.junit:junit-bom:5.11.4 (*)
|    |    +--- org.junit.jupiter:junit-jupiter-params:5.11.4
|    |    |    +--- org.junit:junit-bom:5.11.4 (*)
|    |    |    \--- org.junit.jupiter:junit-jupiter-api:5.11.4 (*)
|    |    \--- org.junit.jupiter:junit-jupiter-engine:5.11.4
|    |         +--- org.junit:junit-bom:5.11.4 (*)
|    |         +--- org.junit.platform:junit-platform-engine:1.11.4
|    |         |    +--- org.junit:junit-bom:5.11.4 (*)
|    |         |    +--- org.opentest4j:opentest4j:1.3.0
|    |         |    \--- org.junit.platform:junit-platform-commons:1.11.4 (*)
|    |         \--- org.junit.jupiter:junit-jupiter-api:5.11.4 (*)
|    +--- org.mockito:mockito-core:5.14.2
|    |    +--- net.bytebuddy:byte-buddy:1.15.4 -> 1.15.11
|    |    +--- net.bytebuddy:byte-buddy-agent:1.15.4 -> 1.15.11
|    |    \--- org.objenesis:objenesis:3.3
|    +--- org.mockito:mockito-junit-jupiter:5.14.2
|    |    +--- org.mockito:mockito-core:5.14.2 (*)
|    |    \--- org.junit.jupiter:junit-jupiter-api:5.11.2 -> 5.11.4 (*)
|    +--- org.skyscreamer:jsonassert:1.5.3
|    |    \--- com.vaadin.external.google:android-json:0.0.20131108.vaadin1
|    +--- org.springframework:spring-core:6.2.1 (*)
|    +--- org.springframework:spring-test:6.2.1 (*)
|    \--- org.xmlunit:xmlunit-core:2.10.0
\--- org.junit.platform:junit-platform-launcher -> 1.11.4
     +--- org.junit:junit-bom:5.11.4 (*)
     \--- org.junit.platform:junit-platform-engine:1.11.4 (*)

testRuntimeOnly - Runtime only dependencies for source set 'test'. (n)
\--- org.junit.platform:junit-platform-launcher (n)

(c) - A dependency constraint, not a dependency. The dependency affected by the constraint occurs elsewhere in the tree.
(*) - Indicates repeated occurrences of a transitive dependency subtree. Gradle expands transitive dependency subtrees only once per project; repeat occurrences only display the root of the subtree, followed by this annotation.

(n) - A dependency or dependency configuration that cannot be resolved.

A web-based, searchable dependency report is available by adding the --scan option.

BUILD SUCCESSFUL in 2s
1 actionable task: 1 executed
```
