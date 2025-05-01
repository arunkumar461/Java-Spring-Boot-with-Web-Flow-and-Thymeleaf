# Spring Boot 3, Java 21, Spring Web Flow, and Thymeleaf Demo

This project demonstrates how to use Spring Web Flow with Spring Boot 3 and Java 21, along with Thymeleaf for templating. It provides a working example of integrating Spring Web Flow into a modern Spring Boot application.

Starter Spring Boot project with Spring Web Flow and Thymeleaf configured. I've been struggling with this one for quite some time until realized I've missed one line of code. 

Well, I don't want you guys to waste time like I've done, so here you go :)

## Key Features
- Spring Boot 3
- Java 21
- Spring Web Flow integration
- Thymeleaf templating
- Example registration flow (see `src/main/resources/flows/register/signup-flow.xml`)
- Bootstrap CSS for modern UI

## Project Structure
- `src/main/java/com/example/demo/` - Main application source code
- `src/main/resources/flows/` - Spring Web Flow XML definitions
- `src/main/resources/templates/` - Thymeleaf templates
- `src/main/resources/static/` - Static assets (CSS, JS)

## Getting Started
1. **Prerequisites:**
   - Java 21
   - Maven 3.8+
2. **Build and Run:**
   ```sh
   ./mvnw spring-boot:run
   ```
3. **Access the App:**
   - Open [http://localhost:8080](http://localhost:8080) in your browser.

## How It Works
- The project uses Spring Web Flow to manage complex page flows, such as user registration.
- Flows are defined in XML (see `signup-flow.xml`) and referenced in controllers.
- Thymeleaf is used for rendering views, with fragments for reusable HTML.
- Bootstrap is included for responsive design.

## Thymeleaf configuration with Spring Webflow
What Thymeleaf says about integrating with Webflow is told [on this page](https://www.thymeleaf.org/doc/tutorials/3.1/thymeleafspring.html#spring-webflow-integration).

## References
- [Spring Web Flow Documentation](https://docs.spring.io/spring-webflow/docs/current/reference/html/)
- [Spring Boot Documentation](https://docs.spring.io/spring-boot/docs/current/reference/html/)
- [Thymeleaf Documentation](https://www.thymeleaf.org/documentation.html)
