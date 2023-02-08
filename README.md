# springboot-rest-starter 
스프링 부트 기반의 RESTful API 서버 스타터 프로젝트입니다. 각종 실습용으로 사용하시기 바랍니다.    

## Project Spec  
  - JDK 11 
  - Gradle 6.9.1 (written by Groovy) 

## Included spring stater module
- Springboot module 
  - lombok
  - springboot-starter-web

## Not Included spring stater module 
- Database Connection
  - 이 프로젝트는 데이터베이스 연결 설정을 포함하고 있지 않습니다. DB 연결 구성이 필요한 프로젝트는 별도의 레포지토리를 참고 바랍니다. 
- Security 
  - 이 프로젝트는 별도의 Spring Security 모듈을 포함하고 있지 않습니다. 
- Actuator 
  - 이 프로젝트는 모니터링을 위한 Actuator 구성을 포함하고 있지 않습니다. 

## 그 외 
- 이 프로젝트는 RESTful API 서버 실행을 위한 메인 클래스로 MainApplication.java를 다음과 같이 재정의하였습니다. 실행 시 참고 바랍니다. 
```java
@SpringBootApplication
public class MainApplication {

    public static void main(String[] args) {
        SpringApplication.run(MainApplication.class, args);
    }

}
```

