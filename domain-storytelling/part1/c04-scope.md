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

도메인 스토리의 일반적인 여정
1. 새 도메인 탐색 : 거칠고 순수한, As-is 모델링 (Coase-Grained, Pure, As-is)
2. 하위 도메인으로 드릴다운 : 세밀하고 순수한 As-is 모델링 (Fine-Grained, Pure, As-is)
3. 새로운 소프트웨어 소개 : 세밀하고 디지털화된 To-be 모델링 (Fine-Grained, Digitalized, To-be)
글자 그래도 일반적인 여정이니 상황에 맞게 자유롭게 범위를 정해 모델링하면 된다.

다양한 목적을 위한 스토리텔링과 범위 조정의 예

#### 새로운 도메인 탐색 (Coase-Grained, Pure, As-is)
순수한 도메인 자체를 이해하기 위해서는 소프트웨어 시스템을 생략하고, 고객의 관점에서 목적을 바라보면서 모델링하는 것이 좋다. 따라서 도메인 스토리는 종종 종단간 비즈니스 프로세스를 표현한다. 

도메인 영역 탐색을 시작할 때, 도메인 스토리의 개요를 모델링할 때, 도메인 영역에서 경계를 찾으려 할 때 이 방법을 사용할 수 있다.
순수한 도메인 자체를 이해하기 위해서는 소프트웨어 시스템을 생략하고, 고객의 관점에서 목적을 바라보면서 모델링하는 것이 좋다. 따라서 도메인 스토리는 종종 종단간 비즈니스 프로세스를 표현한다. 

#### 하위 도메인으로 드릴다운 (Fine-Grained, Pure, As-is)
도메인을 빠르게 참색하고 프로젝트 범위에 대한 컨센서스를 맞췄다면, 이후 상세하게 드릴 다운한다. 앞에서 도메인 전체를 조망했으니, 이번 단계에서는 하위 도메인에 집중해서 모델링한다. 하위 도메인은 보통 한 부서 내에서 발생하는 스토리 수준으로 정한다.

다른 하위 도메인 간, 부서 간의 인터페이스를 볼 수 있도록 하위 도메인의 시작과 끝에 커멘트(추가 설명)를 작성하면 좋다. 이렇게 하면 부서의 경계를 넘어 함께 일하는 방식을 이해하는데 도움이 된다.

이 방법을 통해 개선된 소프트웨어의 지원으로 해택을 얻을 수 있는 비즈니스 프로세스를 찾을 수 있으며, 기술적으로 복잡하지 않은 순수한 도메인 모델을 추출하고 모델을 구현할 수 있다. 또한 As-is와 To-be 도메인 스토리를 비교해서 작업(프로세스)가 어떻게 변경되는지 시각화할 수 있다.

#### 신규 소프트웨어 도입(Fine-Grained, Digitalized, As-is)
As-is에 개선된 프로세스, 새로운 역할, 새로운 소프트웨어가 어떻게 추가/변경되는지 표현한다.
세밀하고 디지털화된 To-be 스토리는 미래에 사람(역할자)과 소프트웨어 시스템이 함께 작동하는지를 보여준다. 즉, 이번 단계에서는 개선사항이 소프트웨어로 구현되었을 때 기존의 작업(프로세스)가 어떻게 변경되는지를 시각화한다.


