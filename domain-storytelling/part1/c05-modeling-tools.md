[[Home]](https://github.com/haesiku/books/tree/main/domain-storytelling/readme.md)

# Chapter 5: Modeling Tools (모델링 도구)
> 도메인 스토리텔링은 스토리를 어느수준으로 상세히 설명할 것인지, 어느 범위를 설명할 것인지 정의해야 한다.

## 모델링 도구 유형 및 모델링 도구별 비교
### Modeling on Paper or Boards
작은 그룹, 소규모 사람들과 함께 오프라인에서 특별한 준비 없이 종이와 펜만으로 모델링할 수 있다.

<p align="center">
  <img width="480" height="520" src="https://github.com/haesiku/books/blob/main/domain-storytelling/part1/images/c05/modeling-on-paper.png"/>
</p>
<p align="center">Modeling on Paper</p>

도메인 스토리 모델링은 도메인 전문가와 인터뷰, 브레인 스토밍 형태로 진행하므로 수정이 자주 발생하는데 종이에 펜으로 모델링하는 경우 수정이 어렵다. 

화이트보드에 스티커(포스트잇)를 사용해서 모델링하는 것도 좋다.
스티커에 액터(Actor), 작업 객체(Work Object)를 그려 붙이고, 펜으로 활동(Activity)과 순서(Sequence Number)를 표기한다. 보통 액터는 세로로 긴 직사각형 스티커를, 작업 객체는 정사각형 스티커를 사용하며, 더 쉬운 구분을 위해 서로 다른 색상의 스티커를 사용할 수 있다.
> 개인적으로 이벤트스토밍 워크샵에서와 같이 각 구성요소별로 다른 색상의 스티커를 정의해서 사용하는 것이 쉽게 명확한 의미를 표현할 수 있을 것 같다.
> 어떻게 하던 스타일을 일관되게 적용하는 것이 중요하다.

이 방법을 쓰더라도 스티커에 직접 아이콘을 그려야 하는 어려움이 있다. 아이콘을 그리지 않고 텍스트로만 표현할 수도 있지만,  그림은 작업 객체가 표현하는 방식을 나타낼 수 있으며, 이 표현을 통해 명확한 이해를 공유할 수 있다. 

### Modeling with Software Tools
<작성중>

### Choosing a Tool
도구 비교
Tool|Group Size|Corrections|Usage|Modeling Support
----|----|----|----|----
Sheet of paper|3 Hard|Spontaneous|None
Flip chart (with stickies)|5 Hard|Spontaneous|None
Whiteboard (with stickies)|7 OK|Spontaneous|None
Whiteboard (with kit)|7 OK|Occasional|None
Digitalized hand-drawing|10+ OK|Occasional|None
Drawing tool|10+ Easy|Frequent|None
Virtual whiteboard|10+ Easy|Frequent|None
Egon.io|10+ Easy|Frequent|Good



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
모델링의 목적은 잘못된 것을 개선하거나, 문제를 해결하는 것이기 
