1. this란 무엇인가?
2. this에 바인딩될 객체가 결정되는 시점은?
3. 정적 메서드와 프로토타입 메서드 차이

--- 

1. this는 자신이 속한 객체 또는 자신이 생성할 인스턴스를 가리키는 자기 참조 변수다. this를 통해 자신이 속한 객체 또는 자신이 생성할 인스턴스의 프로퍼티나 메서드를 참조할 수 있다.
2. 호출 시점
3.
- 정적 메서드와 프로토타입 메서드는 자신이 속해 있는 프로토타입 체인이 다르다.
- 정적 메서드는 클래스로 호출하고 프로토타입 메서드는 인스턴스로 호출된다.
- 정적 메서드는 인스턴스 프로퍼티를 참조할 수 없지만 프로토타입 메서드는 인스턴스 프로퍼티를 참조할 수 있다. 
