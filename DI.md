## Dependency Injection (DI) 의존성 주입

> [!NOTE]
> 객체가 필요로 하는 어떤 것을 외부에서 전달해주는 것

> [!CAUTION]
> 한 객체에서 다른 객체를 생성하거나 다른 객체의 메서드를 호출할 때 의존성이 발생한다

—> 하지만 하나를 바꾸면 의존성에 의해 다른 것도 영향을 받을 수 있으므로, 의존성을 해결하기 위해 **객체의 의존관계를 내부에서 결장하는 것이 아니라 객체 외부에서 결정**하도록 하여. 의존성 위험도를 낮춘다

- 재사용성, 유연성이 높아진다
- 객체간 결합도가 낮아 한 클래스를 수정했을 때 다른 클래스를 수정해야하는 상황을 막아준다
- 유지보수가 쉽고, 테스트가 용이하다
- 책임이 분리되어 잇어 복잡하다
- 주입된 객체들에 대한 코드 추적이 어렵다

---

출처 : https://hudi.blog/dependency-injection/

[https://velog.io/@sana/DI-의존성-주입Dependency-Injection-의-개념과-방법](https://velog.io/@sana/DI-%EC%9D%98%EC%A1%B4%EC%84%B1-%EC%A3%BC%EC%9E%85Dependency-Injection-%EC%9D%98-%EA%B0%9C%EB%85%90%EA%B3%BC-%EB%B0%A9%EB%B2%95)
