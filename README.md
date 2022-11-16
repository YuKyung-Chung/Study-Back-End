# Study-Back-End
Back-End 다루기 위해 필요한 지식 공부 기록

---

## 네트워크

### 웹 애플리케이션 작동원리

- 웹 애플리케이션 네이티브 애플리케이션의 기본 개념
- [네트워크를 만드는 기술](https://infinite-power.tistory.com/78)
  - TCP/IP
  - IP
  - TCP와 UDP 개념과 그 차이
  - PORT의 개념과 그 차이
  - URL, DNS의 기본
  - DNS 기본적인 작동원리
- 웹을 구성하는 기술
  - 웹의 기본적인 개념
  - 클라이언트-서버 아키텍처
  - 웹 애플리케이션 아키텍처
  - 웹 애플리케이션 아키텍처 요청흐름
  - 웹 애플리케이션을 구현하는 방식과 기술들
  - SSR 과 CSR의 기본 개념과 그 차이
  - CORS 의 기본 개념
  - SPA 를 가능하게 하는 AJAX
- HTTP messages의 구조
  - HTTP의 동작 방식
  - HTTP requests와 responses 구분
  - HTTP의 응답 메시지
  - 


### HTTP
- REST API
- Open API와 API Key
- Postman

---

## SQL
- 기본 문법
- ACID
- DATABASE 설계
- DATABASE 정규화
- Advanced
- [참고자료]([https://github.com/PgmJun/Study_BackEnd/blob/main/HTTP/HTTP-TIL.md#%EC%BF%A0%ED%82%A4](https://websitesetup.org/wp-content/uploads/2020/08/SQL-Cheat-Sheet-websitesetup.pdf))
---

## Spring
- Spring Framework 기본
- Spring Framework 특징
- Spring Framework 모듈 구성
- Spring Boot
- POJO(Plain Old Java Object)
- IoC(Inversion of Control)
- DI(Dependency Injection)
  - 스프링 컨테이너
  - 빈
  - 빈 스코프
- AOP(Aspect Oriented Programming)
  - AOP 필요한 이유
  - AOP 용어
  - 타입별 Advice
  - Pointcut 표현식
  - JoinPoint
  - 애너테이션을 이용한 AOP
- PSA(Portable Service Abstraction)

## Spring MVC
- API 계층
  - Spring MVC 아키텍처
  - Controller
  - DTO(Data Transfer Object)

- 서비스 계층
  - DI를 통한 서비스 계층 <-> API 계층 연동
  - Mapper를 이용한 DTO 클래스 <-> 엔티티(Entity) 클래스 매핑

- 예외 처리
  - @ExceptionHandler를 이용한 예외 처리
  - @RestControllerAdvice를 이용한 예외 처리
  - 예외 던지기(throw)

- JDBC 기반 데이터 액세스 계층
  - Spring Data JDBC
  
- JPA 기반 데이터 액세스 계층
  - Spring Data JPA

- 트랜잭션

- 테스팅
  - 단위 테스트(Unit Test)
  - 슬라이스 테스트(Slice Test)
  - Mockito
  
- API 문서화
