# Spring

# 1. POJO(Plain Old Java Object) 기반의 구성 

 - 일반적인 자바코드를 이용해서 객체를 구성하는 방식을 그대로 스프링에서 사용 가능

# 2. 의존성주입(DI)을 통한 객체 간의 간계 구성

- 의존성이란 하나의객체가 다른 객체 없이 제대로 된 역할을 할 수 없다는것.
- 어떤 객체인지 신경 쓸 필요없고, 어떤 객체에 의존하든 자신의 역할은 변하지 않음.
- ApplicationContext라는 존재가 필요한 객체를 생성, 주입하는 구조
- 스프링을 이용하면 객체와 객체를 분리해서 생성, 이러한 객체들을 엮는 작업을 하는 형태의 개발.
- ApplicationContext관리하는 객체들을 빈(Bean)이라고 부름.

# 3. AOP(Aspect Oriented Programming)의 지원

- 반드시 처리가 필요한 부분을 횡단 관심사(cross - concern)이라고 함. 스프링은 이러한 횡당 관심사를 분리해서 제작이 가능
- 반복적인 코드 제거.
- 핵심에만 집중 가능하게 해줌.

# 4. 트랜잭션의 지원

- 트랜잭션 : 여러 과정을 하나의 행위로 묶을 때 사용된다.
여러 단계를 수행했을때, 하나라도 실패하면 모두 취소되어야 한다. 이렇게 함으로써 데이터의 무결성을 보장한다. 모두 반영하거나 반영하지 않음.


- 스프링은 이런 트랜잭션의 관리를 어노테이션이나 xml로 설정 할수 있기 때문에 매번 코드를 수정 할 필요가 없음.
