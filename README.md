# **I’m 示** 전시회 추천 및 정보 제공 서비스

**프로젝트 진행 기간:**
2022. 10 ~ 2022. 12

## :bookmark_tabs: 프로젝트 개요
최근 SNS나 길거리를 지나가다 보면 다양한 주제의 전시회가 열리고 있고, 그에 대한 사람들의 관심도도 높아지고 있다. 그러나 전시회에 대한 정보는 획일적 광고가 대부분이며, 직접 찾아보지 않는 이상 개인이 관심있는 분야(취향)에서 열리고 있는 전시회에 대한 정보를 알기 어렵다. 또 SNS에 미숙한 세대는 관련 정보를 찾기가 더욱 힘들다. 따라서 본 프로젝트에서는 회원에 따라 취향에 맞는 전시회를 추천 및 필터별로 정렬해 문화인에게 전시회에 대한 **‘접근성’**, **‘다앙성**을 제공하는 것을 목표로 한다.
<br>
📌 **'I’m 示'** 는  취향 분석 테스트를 통해 회원 개인의 취향을 분석하고, 회원을 카테고리 별로 분류하여 해당 카테고리에 걸맞은 전시회 정보를 회원에게 제공하는 웹이다. 더 나아가 다양한 전시회를 필터별(인기순, 최신순 등)로 정렬한다. <br><br>


## :bookmark_tabs: 프로젝트 배경

사용자의 취향별 전시회 정보 소개 웹페이지로, 현존해 있는 전시회 정보 사이트들은 대부분 단순히 전시회들의 정보를 소개하여 사용자가 관련 전시회에 대한 정보를 파악하고 있어야 하는 페이지들이 대부분이다. 연령층에 구애 없이 전시회를 관람하는 사람들이 증가하고 있지만, 전시 회에 대해 접한 지 얼마 되지 않은 사용자들 또한 증가하고 있어, 자신이 원하는 종류의 전시회 를 찾기에서 어려움을 겪는다. 이러한 문제들을 해결하기 위해 회원가입 시, 사용자들에게 질문과 그림들을 통해 각 사용자의 취향을 분석하고 저장하여 원하는 전시회를 소개할 수 있도록 한다. 이 웹페이지를 통하여 전시회를 자주 방문하는 사람들은 더 쉽게 전시회를 찾을 수 있을 뿐만 아 니라 전시회를 자주 접해보지 않아서 선택에 어려움을 겪는 사용자들까지 쉽게 원하는 전시회를 찾을 수 있게 된다. 또한 원하는 전시회를 클릭하면 전시회의 위치, 가격, 관련 링크 등을 통하여 정보들을 얻고 북마크를 통하여 더 많은 사람이 문화생활을 좀 더 다양하고 편하게 즐길 수 있음을 기대할 수 있다.

## :bookmark_tabs: 기능 소개
 ✔️ **회원 전시 취향 분석:** <br>
 -로그인을 하면 취향 분석 테스트를 할 수 있는 링크가 생성되고 이를 통해 로그인한 회원이 선택하는 대답에 따라서 취향(ex, 현대적, 전통적 등)을 분석하여 Exhibition DB에 있는 Accounts Table에 들어있는 키워드로 분류하여 회원정보와 함께 저장한다.<br>
<br>
 ✔️ **전시 키워드 필터 정렬(최신순, 취향별):** <br>
-Exhibition_detail Table로부터 등록된 전시회 리스트를 받아온 후 필터를 사용해 취향별 (키워드), 최신순으로 정렬하고 이를 사용자에게 보여준다.<br>
<br>
 ✔️ **전시 정보 제공:** <br>
-[일반 사용자]: 사용자가 전시회 리스트에서 누른 전시의 상세정보를 보여준다. 상세정보는 전시회 이름, 전시회 상세설명, 장소, 가격, 공식홈페이지 링크, 사진 촬영 가능 여부를 포함한다. <br>
-[관리자]: 전시정보를 등록하는 것으로 전시회 이름, 전시회 상세설명, 장소, 가격, 공식홈페이지 링크, 사진 촬영 가능 여부에 대한 정보를 삽입, 삭제, 갱신(수정)이 가능하도록 한다.<br><br>


<img width="683" alt="스크린샷 2023-09-12 오전 1 58 12" src="https://github.com/kjw4420/exhibition_platform/assets/97749184/3bf166cf-8f29-40c9-af77-76fcf0767f8a"><br>
<img width="683" alt="스크린샷 2023-09-12 오전 1 58 05" src="https://github.com/kjw4420/exhibition_platform/assets/97749184/87064bbc-0f45-4cd3-9d2f-ca029c936fe2"><br>
<img width="683" alt="스크린샷 2023-09-12 오전 1 58 24" src="https://github.com/kjw4420/exhibition_platform/assets/97749184/47ddc16d-e29e-4f6f-aa94-ca2ceca2942d"><br>
<img width="820" alt="스크린샷 2023-09-12 오전 1 58 41" src="https://github.com/kjw4420/exhibition_platform/assets/97749184/3b540fc5-2575-4e7d-b67c-14b9fa6a8e30"><br>
<img width="820" alt="스크린샷 2023-09-12 오전 1 58 54" src="https://github.com/kjw4420/exhibition_platform/assets/97749184/ab56812d-dbc5-4548-8328-9890e4f9ecda">




## 👩🏻‍💻 멤버

### Front-end/back-end

|               | github                             |
| ------------- | ---------------------------------- |
| 김지원  |https://github.com/kjw4420    |
| 조서현        |   https://github.com/westnowise      |

### 디자인

조서현

## :hammer_and_wrench: 사용 기술

### Front-end

**프로그래밍 언어**<br>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=HTML5&logoColor=white"/> <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=CSS3&logoColor=white"/> <img src="https://img.shields.io/badge/Javascript-F7DF1E?style=flat-square&logo=Javascript&logoColor=white"/>
<br>


### Back-end

**언어**<br>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/> <img src="https://img.shields.io/badge/Javascript-F7DF1E?style=flat-square&logo=Javascript&logoColor=white"/><br><br>
**프레임워크/라이브러리**<br>
<img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white"/> <br>

**데이터베이스**<br>
<img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">


