## CI/CD

> [!CAUTION]
> CI (Continuous Integration) / CD (Continuous Delivery, Continuous Deployment)

---

> **CI**

- **개발 초기부터 실행이 가능한 상태로 코드를 유지하는 것**
- 새로운 코드 변경사항이 정기적으로 빌드 및 테스트 되어 공유 레포지토리에 통합되는 것
- 풀 리퀘스트와 머지로 코드를 자주 통합하여, 각자가 작성한 코드를 합치고 난 후, 모두 모여 빌드를 시작하고 나서야 문제점을 파악할 수 있는 과정이 생략가능하다
- MSA 아키텍처에서의 기능 충돌 방지의 이점을 가질 수 있다
- CI는 새로운 소스코드의 빌드, 테스트, 병합까지를 의미한다

---

> **CD**

- Continous Delivery 또는 Continuous Deployment 두 용어의 축약어이다
- **지속적인 서비스 제공 혹은 지속적인 배포**
- Continous Delivery는 공유 레포지토리로 자동으로 release 하는 것
- Continuous Deployment 는 Production 레벨까지 자동으로 deploy 하는 것이다
- CD 는 개발자의 변경이 레포지토리를 넘어 고객의 프로덕션 환경까지 릴리즈 되는것을 의미한다

---

> **CI/CD 파이프라인 구성요소**

1. 빌드 (소프트웨어 컴파일)
2. 테스트 (호환성 및 오류 검사\_
3. 릴리스 (버전 제어 저장소의 애플리케이션 업데이트)
4. 배포 (개발에서 프로덕션 환경으로의 변환)
5. 규정 준수 및 유효성 검사
   목포 : 빌드, 테스트 및 제공을 수동처리보다 더 빠르고 자동화되고 안정적으로 만드는 것

출처 : [https://velog.io/@leejungho9/CICD-란](https://velog.io/@leejungho9/CICD-%EB%9E%80)<br/>
https://artist-developer.tistory.com/24
