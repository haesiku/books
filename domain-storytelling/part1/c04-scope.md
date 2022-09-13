# Chapter 4: Scope (범위)
> 도메인 스토리텔링은 스토리를 어느수준으로 상세히 설명할 것인지, 어느 범위를 설명할 것인지 정의해야 한다.

## 구성 요소
### Granularity (세분성)
상위 수준의 도메인 스토리를 상세한 하위 수준의 도메인 스토리로 모델링한다.

아래 그림은 영화 관람객이 매표소에서 티켓을 구매하는 방법, 스토리를 상세하게 모델링 한 것이다. 
<p align="center">
  <img width="880" height="600" src="https://github.com/haesiku/books/blob/main/domain-storytelling/part1/images/c04/granularity-ex.png"/>
</p>
<p align="center">From Metropolis 1a to Metropolis 2: An activity from a COARSE-GRAINED story is detailed in a FINE-GRAINED story</p>

그림과 같이 스토리는 세분화의 수준에 따라 다르다.
표현하려는 스토리에 맞게 수준을 정해서 모델링 하는 것이 중요하다. 즉 목적에 맞는 모델링이 필요하다.

> 스토리텔링 표현 수준
> - Cloud Level
> - Kite Level
> - Sea Level : 보통 이 레벨에서 스토리텔링 모델링을 시작하며, 필요에 따라 상위 또는 하위 레벨 모델링한다.
> - Fish Level
> - Clam Level 

### Point in Time (AS-IS vs. TO-BE) (시점)
모델링의 목적은 잘못된 것을 개선하거나, 문제를 해결하는 것이기 때문에 현재 상황을 문제영역으로 정한다. 또한 도메인 스토리를 통해 개선 방향이나 개선 방법을 탐색해서 솔루션 영역에 모델링 할 수도 있다.

<p align="center">
  <img width="480" height="160" src="https://github.com/haesiku/books/blob/main/domain-storytelling/part1/images/c04/point-in-time-ex.png"/>
</p>
<p align="center">Points in time of a domain story (도메인 스토리 시점 예시)</p>

- AS-IS 스토리 : 이렇게 현재 상황을 문제영역으로 정하고 모델링하는 것, 현재 상황 == 문제 영역
- TO-BE 스토리 : 개선 방향이나 방법을 솔루션 영역에 모델링하는 것, 개선된 상황 == 솔루션 영역

### Domain Purity (PURE vs. DIGITALIZED) (도메인의 순도)
도메인 스토리를 모델링할 때 As-is 또는 To-be 소프트웨어 시스템을 포함하거나 생략할 수 있다 이 범위를 도메인 순도(Domain Purity)라고 한다.
- 순수 (Pure, 소프트웨어 시스템이 없는 도메인 스토리) : 신규 소프트웨어 시스템을 구축할 때 유용 (기존 소프트웨어에 기능 추가로 인한 복잡성을 소프트웨어적으로 모델링하지 않음으로 복잡성을 낮출 수 있다.)
- 디지털화 (Digitalized, 소프트웨어 시스템이 있는 스토리

> 개인적으로는 As-is 시스템을 도메인 스토리로 시각화하고, To-be 시스템을 순수 도메인 스토리로 모델링, 이후 소프트웨어 시스템으로 구현할 것들을 디지털화 모델링하는 것이 좋은 방법이라고 생각함 

### Combining the Scope Factors: A Typical Journey (범위 요소 결합: 일반적인 여정)
범위는 여러 요소를 결합해서 정할 수 있다.

> Scope = Granularity X DomainPurity X PointInTime
> 굳이 공식까지 만들 필요가 있을까 싶다...

<<작성중>>



