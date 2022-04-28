# spring-boot-rest-api
- 스프링 부트에서 REST API 구현
- React Front-End 소스
  (https://github.com/seongjinna/todo-react-app)

## Getting Started
- Java version : JDK 8
- Spring Boot : 2.6.6

### Dependencies
- Spring Web : Web
- Spring Data JPA : SQL
- H2 Database : SQL
- Lombok : Developers Tools

### Test
- http://localhost:8080/test
- http://localhost:8080/test/testGetMapping
- http://localhost:8080/test/{id}
- http://localhost:8080/test/testRequestParam?id={id}
- http://localhost:8080/test/testRequestBody
- http://localhost:8080/test/testResponseBody
- http://localhost:8080/test/testResponseEntity
- http://localhost:8080/todo

### Lessons learned
- HTTP POST를 이용하는 Create REST API 개발
- HTTP Get를 이용하는 Retrieve REST API 개발
- HTTP Put를 이용하는 Update REST API 개발
- HTTP Delete를 이용하는 Delete REST API 개발
- 레이어드 아키텍처를 따라 패키지를 model, dto, persistence, service, controller로 나줘서 적용
- REST 아키텍처(@RequestMapping, @GetMapping, @RequestBody, @RequestParam @PathVariable 등)을 이용해 테스트 REST API 구현
- JPA와 Spring DATA JPA 적용
- JDK 8에서 제공하는 Lambda, Stream 등 문법 연습
- CORS(Cross-Origin Resources Sharing) 적용
- Spring Security 적용 및 JWT 인증 로직 구현, 패스워드 암호화 로직 구현 
