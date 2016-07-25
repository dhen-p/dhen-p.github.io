# Advanced TDD - Episode 22

## Test Process - Simple Techniques
오늘은 테스트를 작성하는 기법들에 대해서 알아보는 시간을 갖는다.

### 1. Fake it till you make it

상수값을 리턴하는 약간의 멍청한짓,.

### 2. Stairstep Tests

다음단계로 가기위한 포석
Game 객체를 만들수 밖에 없게 하려면?
test canCreateGame

### 3. Assert First

테스트 작성시 assert부터 작성하는 것이다.
오늘의 하이라이트?
처음 메소드를 만들고 True가 되도록 ? -> 1.Faket


### 4. Triangulation 

삼각법 혹은 삼각측량

한가지 값(input)만가지고 테스트케이스를 작성하면 그 테스트는 깨지기가 쉽다


> As the tests get more specific, the cod get more **GENERIC**

[junit-hiearachy](https://github.com/bechte/junit-hierarchicalcontextrunner) : inner class에서의 테스트 작성 및 실행이가능



### 5. One To Many 

켈렉션에 대해선 잘 동작?


### 6. Refactoring Tests

애자일 소프트웨어 개발론에서 계속 화두가 되는 이슈다. 
디스크가 두가지(production, test) 있을때 어떤게 깨질 것이 나을것인가?

x=10 일때,  F(x) = 100
x=20 일때, F(x) = 200을 반환한다.


x=4738439 일때, F(x) = ?

F(x) = x + 100;
