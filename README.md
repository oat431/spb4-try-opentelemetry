# Try Spring boot 4 OpenTelemetry

### Reference Documentation

For further reference, please consider the following sections:

* [Official Gradle documentation](https://docs.gradle.org)
* [Spring Boot Gradle Plugin Reference Guide](https://docs.spring.io/spring-boot/4.0.1/gradle-plugin)
* [Create an OCI image](https://docs.spring.io/spring-boot/4.0.1/gradle-plugin/packaging-oci-image.html)
* [Spring Boot Actuator](https://docs.spring.io/spring-boot/4.0.1/reference/actuator/index.html)
* [Spring Boot DevTools](https://docs.spring.io/spring-boot/4.0.1/reference/using/devtools.html)
* [OpenTelemetry](https://docs.spring.io/spring-boot/4.0.1/reference/actuator/observability.html#actuator.observability.opentelemetry)
* [Spring Web](https://docs.spring.io/spring-boot/4.0.1/reference/web/servlet.html)

### Guides

1. docker compose the `compose.yml`
2. run the application with `./gradlew bootRun`
3. access `http://localhost:8003/test` a few times
4. access `http://localhost:3000` to see traces on Home > Explore > Prometheus