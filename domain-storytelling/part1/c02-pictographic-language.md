# Chapter 2: The Pictographic Language (그림문자 언어)
> 상호 의사소통이 가능한 수준으로 표현된 이미지/아이콘이라는 뜻으로 해석하는게 좋을 듯

<pre>
도메인 스토리 모델링이란?
"누구(Actors)가 누구(Another Actors)오 무엇(Work Objexts)으로 무엇(Activties0을 하는지 시각화 하는 활동"
</pre>

## 구성 요소
### Actors (액터, 사용자/역할자의 의미)
<p align="center">
  <img width="320" height="320" src="https://github.com/haesiku/books/blob/main/domain-storytelling/part1/images/c02/actors.png"/>
</p>
<p align="center">Actors (사용자/역할자)</p>

- 도메인 스토리는 Actor의 관점에서 전달된다.
- 의미를 명확하게 표현할 수 있는 아이콘을 그리고, 하단에 구체적인 역할의 이름을 작성한다. 일반적으로 명사형
- 이름은 구체적이고 명확한 도메인 언어로 표현한다.
  (예)"영화팬"은 영화티켓을 구매하기 위해 돈을 지불한다.
- Actor는 도메인 스토리에 한번 출현(?)한다. 아래 설명할 Work Objects는 어려번 나타날 수 있다.

### Work Objects (작업 객체, 객체 자체 또는 작업 객체에 대한 정보가 교환되는 매체)
<p align="center">
  <img width="480" height="440" src="https://github.com/haesiku/books/blob/main/domain-storytelling/part1/images/c02/work-objects.png"/>
</p>
<p align="center">Work Objects (작업 객체)</p>

- 의미를 명확하게 표현할 수 있는 아이콘을 그리고, 하단에 구체적인 객체의 이름을 작성한다. 일반적으로 명사형
* 도메인의 개념은 Actors와 Work Objects로 모델링 될 수 있다. 따라서 다른 어떤 유형보다도 이 두개의 유형울 실플하지만 명확하게 표현하는것이 중요하다. 
아이콘은 Google의 Matrial 아이콘을 사용한다.
아이콘은 표현하려는 정보의 의미를 명확하고 단순하게 표현할 수 있는 것을 선택한다.
너무 많은 아이콘들을 사용하면 이해하 어려울 수 있다. (작성한 사람도 며칠 후 다시보면 이해 안갈 수 있음)

### Activities (활동, Actors의 행위 또는 활동)
<p align="center">
  <img width="260" height="260" src="https://github.com/haesiku/books/blob/main/domain-storytelling/part1/images/c02/activities.png"/>
</p>
<p align="center">Activites (활동)</p>

- 행위자의 활동을 방향이 있는 화살표로 표시하고 하단에 활동 내용을 작성한다. 일반적으로 동사형

### Sequence Numbers (일련 번호, 스토리를의 순서를 나타내는 숫자)
<p align="center">
  <img width="240" height="220" src="https://github.com/haesiku/books/blob/main/domain-storytelling/part1/images/c02/seq-numbers.png"/>
</p>
<p align="center">Sequence Numbers (일련 번호)</p>

스토리는 어려개의 문장으로 표현되므로 일련의 순서를 부여한다 원안에 숫자로
일반적으로 Activities(활동)을 나타내는 화살표 상단에 숫자를 작성한다.
대부분 활동이 연속적으로 발생하므로 숫자는 한번만 사용되지만, 동시에 발생하는 활동의 경우 동일한 번호로 작성할 수 있다. 활동 순서 이해가 어려워질 수 있으므로 가능한 적게 사용하는 것을 추천

### Annotations (주석, 구성요소 등 모델에 대한 부연 설명)
<p align="center">
  <img width="680" height="140" src="https://github.com/haesiku/books/blob/main/domain-storytelling/part1/images/c02/annotations.png"/>
</p>
<p align="center">Annotations (주석)</p>

- 모델링 공간의 빈곳, 여백에 주석을 작성하고 부연 설명하려는 항목 점선으로 연결한다.
- 아이콘과 이름 표현으로 이해하기 어려운 부분, 부가적인 설명이 필요한 부분이 있는 경우 작성한다. 별도 작성 방법은 없고, 명확하게 이해될 수 있도록 작성하는 것이 중요하다.

### Modeling Canvas (모델링 캔버스, 화이트보드 등 모델링할 공간으로 아날로그, 디지털 다 가능)
<p align="center">
  <img width="640" height="600" src="https://github.com/haesiku/books/blob/main/domain-storytelling/part1/images/c02/model-canvas.png"/>
</p>
<p align="center">Modeling Canvas (모델링 캔버스)</p>

- 캔버스에 도메인 스토리 이름을 작성한다.
- 도메인 스토리가 동작하기 위해 필요한 Assumtions(기정/추정)을 작성한다. (Optional)
- 도메인 스토리의 Activities를 설명하는 Comments를 작성한다. (Optional)

### Groups (그룹, 스토리 내 묶을 수 있는 하위 스토리의 묶음)
<p align="center">
  <img width="400" height="520" src="https://github.com/haesiku/books/blob/main/domain-storytelling/part1/images/c02/groups.png"/>
</p>
<p align="center">Groups (그룹)</p>

- 스토리 내에 함께 묶을 수 있는 스토리들을 묶는다. 직사각형, 원 또는 모든 형태로 표현할 수 있다.
- 그룹 이르을 작성하고, 그룹의 의미를 설명할 수 있는 내용을 작성한다.
- 그룹으로 표현할 수 있는 몇가지 예시
  - 반복되는 활동
  - 선택사항(Optional)인 활동
  - 다른 곳에서 일어나는 스토리
  - 조직의 경계
  - 하위 도메인(?)

<p align="center">
  <img width="500" height="640" src="https://github.com/haesiku/books/blob/main/domain-storytelling/part1/images/c02/groups-ex.png"/>
</p>
<p align="center">(예시) 하위 도메인별로 그룹화된 영화 보기 스토리</p>

### Colors (색상, 강조 또는 차별화를 표현하기 위해 아이콘/이름에 검정색 외 다른 색상으로 표시)
<p align="center">
  <img width="80" height="100" src="https://github.com/haesiku/books/blob/main/domain-storytelling/part1/images/c02/colors.png"/>
</p>
<p align="center">Colors (색상)</p>

일반적으로 도메인 스토리 모델은 검정색, 즉 흑백으로 표현하지만, 강조 또는 차이점을 시각화하기 위해새 색상으 추가할 수 있다.
색상은 Actors, Activities 등 모든 유형에 적용할 수 있다.
색상은 어떤 모델링 도구를 사용하는지에 따라 사용할 색상이 결정될 수 있고, 이때는 색상의 의미를 나타내는 범례를 추가하는 것이 좋다.

<p align="center">
  <img width="620" height="620" src="https://github.com/haesiku/books/blob/main/domain-storytelling/part1/images/c02/colors-ex.png"/>
</p>
<p align="center">(예시) 영화 보러가기 </p>

### No Conditionals (조건 없음)
<p align="center">
  <img width="620" height="320" src="https://github.com/haesiku/books/blob/main/domain-storytelling/part1/images/c02/no-conditionals.png"/>
</p>
<p align="center">No Conditionals (조건 없음)</p>

BPMN, Business Process Model and Notation과 비슷한데 분기/조건 부분을 단순화한 형태
사용 이유, 목적에 대해서 좀더 알아보고 업데이트 예정

[[Prev]](https://github.com/haesiku/books/tree/main/domain-storytelling/part1/c01-introduction.md) [[Home]](https://github.com/haesiku/books/tree/main/domain-storytelling/readme.md) [[Next]](https://github.com/haesiku/books/tree/main/domain-storytelling/part1/c03-scenario-based-modeling.md) 

