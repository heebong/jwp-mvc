## GIT CONVENTION
https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716

## TODO
#### 요구사항 1
- [x] study 모듈 > src/test/java > reflection > ReflectionTest의 showClass() 메소드를 구현해 Question 클래스의 모든 필드, 생성자, 메소드에 대한 정보를 출력한다.
- [x] Question 클래스의 모든 필드 출력
- [x] Question 클래스 생성자 출력
- [x] Question 클래스 모든 메소드 출력

#### 요구사항 2
- [x] Junit3Test 클래스에서 test로 시작하는 메소드만 Java Reflection을 활용해 실행하도록 구현한다.
- [x] test1()
- [x] test2()

#### 요구사항 3
- [x] Junit4에서는 @Test 애노테이션일 설정되어 있는 메소드를 자동으로 실행한다

#### 요구사항 4
- [x] 자바 Reflection API를 활용해 다음 Student 클래스의 name과 age 필드에 값을 할당한 후 getter 메소드를 통해 값을 확인한다.

#### 요구사항 5
- [x] Question 클래스의 인스턴스를 자바 Reflection API를 활용해 Question 인스턴스를 생성한다.

#### 요구사항 6
- [x] examples 패키지에서 @Controller, @Service, @Repository 애노테이션이 설정되어 있는 모든 클래스를 찾아 출력한다.

----
#### 요구사항 1
- @Controller 인 클래스를 찾음
- @RequestMapping의 값에 따라 적절한 HandlerExecution을 반환.
- [x] HandlerExecution 생성자 생성
- [x] AnnotationHandlerMappingTest 성공하게 변경
- [x] ```@RequestMapping``` 에서 method 값이 없을 때 전부 다 매핑되게 변경
- [x] ```@RequestMapping``` 에서 value 값이 없을 때 등록 안되고 에러 로그 찍어주기

#### 요구사항 2
- [x] 몇가지 url (```/users/create```,```/users/login```, ```/users/form```, ```/users``` )일 경우 새로 만든 ```AnnotationHandlerMapping``` 사용하게 변경
