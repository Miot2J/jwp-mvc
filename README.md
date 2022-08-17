# 프레임워크 구현

## 요구사항 1 - 클래스 정보 출력

- [x] 클래스의 모든 필드를 출력한다.
- [x] 클래스의 모든 생성자를 출력한다.
- [x] 클래스의 모든 메소드를 출력한다.

## 요구사항 2 - `test`로 시작하는 메소드만 Java Reflection을 활용해 실행하도록 구현

- [x] Junit3Test 클래스의 모든 메소드 중 test로 시작하는 메소드만 실행된다.

## 요구사항 3 - `@Test` 애노테이션이 설정되어 있는 메소드를 자동으로 실행하도록 구현

- [x] Junit4Test 클래스에서 @MyTest 애노테이션으로 설정되어 있는 메소드만 Java Reflection을 활용해 실행하도록 구현한다.

## 요구사항4 - private field에 값 할당

- [x] Student 클래스의 name과 age 필드에 값을 할당한 후 getter 메소드를 통해 값을 확인

## 요구사항 5 - 인자를 가진 생성자의 인스턴스 생성

- [x] Question 클래스의 인스턴스를 자바 Reflection API를 활용해 Question 인스턴스를 생성

## - 요구사항 6 - component scan 구현

- [ ] @Controller, @Service, @Repository 애노테이션이 설정되어 있는 모든 클래스를 찾아 출력