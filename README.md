# say argument "t" is null

run this application `./gradlew bootRun` ,

and access to <http://localhost:8080/swagger-ui/index.html> ,

your console will say..."Graceful exception occurred"

```console
WARN 12367 --- [say-argument-t-is-null] [nio-8080-exec-4] o.s.c.utils.SpringDocAnnotationsUtils    : Graceful exception occurred

java.lang.IllegalArgumentException: argument "t" is null
        at com.fasterxml.jackson.databind.ObjectMapper._assertNotNull(ObjectMapper.java:5072) ~[jackson-databind-2.18.2.jar:2.18.2]
        at com.fasterxml.jackson.databind.ObjectMapper.constructType(ObjectMapper.java:2252) ~[jackson-databind-2.18.2.jar:2.18.2]
        at org.springdoc.core.converters.SortOpenAPIConverter.resolve(SortOpenAPIConverter.java:82) ~[springdoc-openapi-starter-common-2.8.3.jar:2.8.3]
...
```
