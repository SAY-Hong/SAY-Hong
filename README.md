## 1. Who's 'Say'?
### 1.1 프로필
이름: 홍세희(Say)  

* Birth: 2001-03-03
* Education: 소프트웨어공학, 2021~ (현재 휴학 중) 
* GitHub 링크: https://github.com/SAY-Hong

### 1.2 공부한 기술


| 기술 이름 | 키워드                                                                                 |
| --------- | ------------------------------------------------------------------------------------ |
| [Swift](#1.2.1-Swift)     |  문법                                                                                   |
| [Python](#1.2.2-Python)    |  DeepLearning 프로젝트 및 데이터 가시화                                                                                  |
| [Java](#1.2.3-Java)     | Card 게임 프로젝트                            |
| [SQL](#1.2.4-SQL)       | sql문 문법 공부 |

**1.2.1 Swift**  
앱스쿨 3기를 위해 스위프트의 기초 문법을 공부하는 중입니다.  
  
**1.2.2 Python**  
딥러닝 프로젝트와 웹브라우저 사이트의 데이터 추출을 위한 베이스 공부를 진행했습니다.  
딥러닝 모델 생성을 위해 tensorflow, keras 모듈과 이미지 추출에 필요한 역량을 쌓았습니다.  

**1.2.3 Java**  
카드 게임 프로젝트를 수행하기 위해 공부했습니다. 객체에 관한 기본 개념과 더불어 상속, 패키지 등 다양한 모듈을 프로젝트에 적용시키며 java에 대한 기초를 확립하고자 노력했습니다.    

**1.2.4 SQL**  
'마당서점' 표본을 활용하여 원하는 데이터를 추출하는 sql문 문법을 공부했습니다.  
DB 릴레이션의 충돌을 막기 위한 내용과 DB 모델을 설계하는 실습을 경험했습니다. 



<details>
<summary>기록 사이트 찾아가기</summary>
<div markdown="1">

[🔗노션 사이트🔗](https://www.notion.so/SAY-s-RECORD-8a7b085562e647e3ba6526e7e0d50425)  
[🔗블로그 사이트🔗](https://blog.naver.com/say_my_hong)

</div>
</details>

    
## 2. 'Say', Myself!
#### 2.1 어떻게 '개발'에 뛰어들었는가?
저는 원래 컴퓨터의 '컴'자에도 질색하던 사람이었습니다. 
고철덩어리의 컴퓨터의 작동원리나 기본적인 CPU, 메모리 등에 관한 내용이 주변에서 들리기 시작하면 진절머리가 났었던 시절이 있었습니다. '생명공학'의 길을 가고 싶던 와중, 진로에 대한 방황을 하며 대학교에 입학하게 되었습니다.   

1학년 때 자율전공으로 여러 전공들의 기초를 들어보게 되었고, 그 와중에 '컴퓨터의 이해'와 '프로그래밍 기초'라는 과목들을 수강하게 되었는데 그 때 이후 컴퓨터의 '컴'자에 정이 가기 시작했습니다. 1학년 때 우연히 수강하게 되었던 경험을 바탕으로 소프트웨어공학을 전공으로 해야겠다고 느끼게 되며 현재 학교에서 여러 방향의 분야를 공부해보며 저의 길을 찾아가고 있습니다. 

#### 2.2 어떻게 성장하고 싶은가?
저는 각을 잡고 공부해서 지식을 체득하기보다 천천히 탐구하고, 이해하고, 개발툴을 이용해 여러가지를 실험해보며 이해하는 타입입니다. 하나의 언어를 배우면서 그 언어와 함께 적용할 수 있는 도구가 있다면 흥미가 생길 때 슬쩍 훑어보고 '오 재밌겠는데?'라는 생각을 하며 다른 가지들도 공부하는 것을 좋아하는 것 같습니다.   

불이 꺼진 흥미에 언제든지 불을 붙일 수 있게끔 공부하는 내용을 꾸준히 기록하며 불을 붙게 하는 저만의 '매개체'를 만드는 방법을 찾아가고 싶습니다. 또한 개발의 다양성에 겁을 내지 않고 코드 실험을 하되, 어쨌든 개발이라는 직종도 다른 사람과의 협업이 중요하기에 '도전'과 '표준'의 길 사이에서 조율을 할 수 있게 고민을 하며 성장하지 않을까 싶습니다. 


## 3. Say's Projects
### 3.1 프로젝트



| 기간              | 프로젝트명            | 사용 기술 | 키워드         |
| ----------------- | --------------------- | --------- | -------------- |
| 2023.04 ~ 2023.06 | [CS3 project](#CS3-project) | python    | 숫자 인식, MLP |
| 2022.09 ~ 2023.06 | [Card Game Project](#Card-Game-Project)     | java      | 객체 |



#### ✅CS3 project: 숫자 인식 딥러닝 모델 제작  
* **프로젝트 목표:** 최소한의 자원과 파라미터를 사용하여 한국인이 작성한 숫자 표본을 학습시킨 모델 생성  
* **프로젝트 요약:** 모델 학습에 필요한  이미지 추출, 변형, 증폭의 방법을 통해 생성된 데이터를 모델에 학습시켰습니다.   
* **프로젝트에 사용한 기술:** python
* **프로젝트 진행:**   
     1. 프로젝트의 관건은 '한국인의 손글씨' 표본을 구하는 일이었습니다. 주변 지인들과 팀원이 숫자 0부터 9까지 여러 방법으로 작성하며 표본 200여개 정도 획득하고 파이썬을 통해 이미지 회전, 축소, 확대, 증폭을 통해 이미지 수를 10000개 이상으로 이미지를 생성하여 모델이 많은 표본을 학습할 수 있게 했습니다. 
    2. 최소한의 자원으로 최선의 정확도를 도출해내기 위해 MLP를 기반으로 하는 tensorflow의 Sequential 모델을 참고하여 팀만의 모델을 만들었습니다. Conv2D, MaxPooling2D 등등 계층의 매개변수를 변화시키며 전체 모델의 파라미터 수(자원 수)를 최대한 줄이는 방향으로 프로젝트를 진행했습니다. 

* **프로젝트 진행 후 얻은 역량**
    1. 시간 배분: 직접 노션 페이지를 만들며 ZOOM 회의 기록, 코드 기록, 관련 공부 내용 링크 등의 정리와 팀원들과의 일정 조율을 통해 2개월 동안 저희 팀의 소규모 목표를 하나씩 만들어서 성취하는 방향을 제시했습니다.
    2. 구글링: 무작정 지도 교수님께 내용을 물어보는 것이 아닌 도서관에서 관련 기술에 대한 자료 공부, 구글링을 통한 관련 기술 학습 방법 등을 직접 찾아보며 나에게 필요한 기술에 대한 역량 강화와 팀원들의 이해를 돕기 위한 예시 사이트 제시 등을 하며 데이터셋의 구조에 대한 근본적인 궁금을 해소하는 경험을 할 수 있었습니다. 

* **프로젝트 진행 시 아쉬웠던 부분**
    1. 코드 공유의 비효율성: 팀원끼리 깃허브를 사용하지 않아서 노션과 카톡을 통해서 코드를 공유할 수 밖에 없었습니다. 코드를 올려도 어디에 올렸는지 헷갈려하는 팀원들도 있었고 노션에 여러 코드가 섞이면서 이 코드가 저 내용을 위한 코드인가 하는 의문점에 카톡으로 팀원들과 서로 체크하며 코드를 옮겨야해서 불편했습니다. 다음 프로젝트 기회가 있다면 깃허브를 사용해서 코드 공유를 해야겠다고 느끼게 되었습니다. 
    2. 업무 배분의 비효율성: CS3 프로젝트를 진행했던 팀은 서로 해야하는 일을 나눠서 하지 않았습니다. 분량만 서로 나누고 같이 다음 단계로 나아가는 형태였습니다. 모델을 학습하는 과정에서 여러 파라미터를 실험해보며 학습을 해야하는데 정확한 경우의 구분 없이 '모델의 자원 수의 최소화'에만 맞춰서 진행하다보니 다른 팀원들과 파라미터의 수가 겹치는 경우가 있었고 나중에는 어떤 파라미터를 실험했는지 알기 어려웠습니다. 다음 프로젝트의 기회가 있다면 경우를 나눠서 일을 배분하고 결과를 저장소에 기록하며 서로 소통하는 작업을 진행할 것 같습니다. 


#### ✅Card Game Project  
* **프로젝트 목표:** java의 문법을 카드 게임 파일을 만들며 익힌다. 
* **프로젝트에 사용한 기술:** java
* **프로젝트 진행 후 얻은 역량:**  
    1. '객체 지향'
    2. 개발 프로그램 사용법
    3. 여러 모듈의 사용법
* **프로젝트 진행 시 아쉬웠던 부분:**
