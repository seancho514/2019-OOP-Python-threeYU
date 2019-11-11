# 2019-2 객체지향 프로그래밍 프로젝트 - **{3유}**
구성원: 2-4 유동헌 | 2-6 유승화 | 2-6 조민성

## 1. 주제
괴물을 피해 미로를 탈출하라!

## 2. 동기
2014년 9월 개봉한 영화 '메이즈러너'는 모든 기억이 삭제된 채 의문의 미로에 갇힌 토마스의 이야기를 다룬다. 
조원 모두 영화 메이즈러너를 인상깊게 보아서 파이썬을 이용하여 괴물을 피해 미로를 탈출하는 게임을 만들면 재미있을 것 같아 정하게 되었다. 

## 3. 프로그램 사용 대상
영화 '메이즈 러너'를 재밌게 본 관람객 이외에도 괴물을 피해 미로를 탈출하는 게임을 해보고 싶은 전 연령의 사람들을 대상으로 한다.

## 4. 목적
영화 '메이즈 러너'를 기억하는 사람들이 이 게임을 플레이하면서 재미도 느끼고 영화 속 캐릭터 사용이나 상황 설정 등으로 영화를 회상할 수 있다.

## 5. 주요기능
가. 캐릭터 강화 기능

게임 시작시 플레이어는 가장 낮은 등급의 캐릭터로 게임을 시작하게 된다. 이때의 캐릭터 등급을 A,B,C,D라 하면, C등급의 캐릭터는 D등급의 캐릭터 2개가 모여야 생기며 B등급은 C등급의 캐릭터 2개, A등급은 B등급의 캐릭터 2개가 모여야 만들어질 수 있도록 해 게임을 진행하며 캐릭터를 점차 강화할 수 있도록 한다. 이때 가장 낮은 등급의 캐릭터는 일정 시간마다 플레이어가 생성할 수 있도록 하여 캐릭터를 성장시켜 나갈 수 있도록 한다. 나아가 캐릭터의 등급이 높아질 때마다 능력치가 상향되도록 하여 미니게임에 보다 유리하게 한다. 
 
나. 미니 게임 기능

미니게임은 미로를 주어진 시간 동안에 해결해 나가는 과정을 중심으로 하며 이때 플레이어 가 승리하는 조건은 미로를 주어진 시간 동안 탈출하는 것이며, 도중에 괴물에게 잡히거나 주어진 시간동안 미로를 해결하지 못하면 패배하게 된다. 미니게임에서는 캐릭터의 등급에 따라 움직일 수 있는 속도가 다르게 배정되며 게임에서 승리하게 되면 캐릭터를 강화할 수 있는 요소(ex.골드, 경험치)를 제공하며 미니게임 진행 라운드가 높아질수록 미로 난이도가 상향된다. 
 
다. 이벤트

일정시간마다 이벤트를 진행할 수 있게 하여(ex. 기본 캐릭터 생성 시간 감소, 캐릭터 능력   일시 강화) 미니게임이나 캐릭터 강화에 유리하게 한다.

## 6. 프로젝트 핵심
-플레이어가 자신의 캐릭터 등급을 점차 강화하면서 자율적으로 미니게임을 진행하고, 이벤트를 진행하며 게임을 진행할 수 있도록 한다. 

-미니게임 진행에 있어 랜덤으로 미로를 제작하고 괴물과 인간에 대한 클래스를 제작해 미니게임 진행이 원활하도록 한다.

## 7. 구현에 필요한 라이브러리나 기술
 라이브러리 

- pygame
: 

- random
: 랜덤미로를 생성할 때 사용할 라이브러리

- time
: 주어진 시간내에 미로를 탈출하기 위해서 타이머 기능을 구현할 때 사용할 라이브러리

- numpy
: 

 기술
 
- Recursive Backtracking
: 

- Prim's Algorithm
: 

## 8. **분업 계획**
유동헌: 랜덤 미로 생성 프로그램 제작 및 미니게임 구성

유승화: 캐릭터 강화 기능 구성 및 타이머 기능 구현

조민성: 프로그램 시각화 및 이벤트 요소 구성. 게임 보드 및 환경 구현

## 9. 기타

<hr>

#### readme 작성관련 참고하기 [바로가기](https://heropy.blog/2017/09/30/markdown/)

#### 예시 계획서 [[예시 1]](https://docs.google.com/document/d/1hcuGhTtmiTUxuBtr3O6ffrSMahKNhEj33woE02V-84U/edit?usp=sharing) | [[예시 2]](https://docs.google.com/document/d/1FmxTZvmrroOW4uZ34Xfyyk9ejrQNx6gtsB6k7zOvHYE/edit?usp=sharing) | [[예시 3]](https://github.com/goldmango328/2018-OOP-Python-Light) | [[예시4]](https://github.com/ssy05468/2018-OOP-Python-lightbulb) | [[모두보기]](https://github.com/kadragon/oop_project_ex/network/members)
