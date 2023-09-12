# **I’m 示** 전시회 추천 및 정보 제공 서비스

## :bookmark_tabs: 프로젝트 설명
**Target: 이런 사람에게 추천해요** 🎯<br>
 📌 전시회를 처음 가보고 싶은데 어떤 전시회를 가야 하지?<br>
 📌 SNS 유행 따라가는 전시회는 별로야! 내 취향에 맞는 전시회는 없을까?<br>
 📌 이 전시회는 너무 광고 같은데?<br>
 📌 다양한 전시회 정보를 알고 싶어!<br><br>

**내 취향에 맞는 전시회** ❗️  <br>
 ✔️ 간단한 테스트를 통한 회원별 취향 탐색: 키워드 부여 <br>
 ✔️ 회원 취향별(키워드 별) 맞춤형 전시회 추천  <br>
 ✔️ 전시회 상세 정보 확인<br><br>

<img width="683" alt="스크린샷 2023-09-12 오전 1 58 12" src="https://github.com/kjw4420/exhibition_platform/assets/97749184/3bf166cf-8f29-40c9-af77-76fcf0767f8a"><br>
<img width="683" alt="스크린샷 2023-09-12 오전 1 58 05" src="https://github.com/kjw4420/exhibition_platform/assets/97749184/87064bbc-0f45-4cd3-9d2f-ca029c936fe2"><br>
<img width="683" alt="스크린샷 2023-09-12 오전 1 58 24" src="https://github.com/kjw4420/exhibition_platform/assets/97749184/47ddc16d-e29e-4f6f-aa94-ca2ceca2942d"><br>
<img width="820" alt="스크린샷 2023-09-12 오전 1 58 41" src="https://github.com/kjw4420/exhibition_platform/assets/97749184/3b540fc5-2575-4e7d-b67c-14b9fa6a8e30"><br>
<img width="820" alt="스크린샷 2023-09-12 오전 1 58 54" src="https://github.com/kjw4420/exhibition_platform/assets/97749184/ab56812d-dbc5-4548-8328-9890e4f9ecda">


  최근 SNS나 길거리를 지나가다 보면 다양한 주제의 전시회가 열리고 있고, 그에 대한 사람들의 관심도도 높아지고 있다. 그러나 전시회에 대한 정보는 획일적 광고가 대부분이며, 직접 찾아보지 않는 이상 개인이 관심있는 분야(취향)에서 열리고 있는 전시회에 대한 정보를 알기 어렵다. 또 SNS에 미숙한 세대는 관련 정보를 찾기가 더욱 힘들다. 따라서 본 프로젝트에서는 회원에 따라 취향에 맞는 전시회를 추천 및 필터별로 정렬해 문화인에게 전시회에 대한 **‘접근성’**, **‘다앙성**을 제공하는 것을 목표로 한다.

## 📗 주요 기능
🔍**회원가입 및 로그인**<br>
회원가입 페이지에 아이디, 비밀번호, 이름, 닉네임을 받아와 서버를 통해 ExhibitionDB에 있는 Accounts Table에 저장한 후 로그인을 진행한다. 로그인 창에 입력한 아이디와 비밀번호가 Accounts Table에 있는 정보와 일치하면 로그인이 허가된다.<br><br>
🔍**취향 분석(분류; 회원 취향 분석)**<br>
로그인을 하면 취향 분석 테스트를 할 수 있는 링크가 생성되고 이를 통해 로그인한 회원이 선택하는 대답에 따라서 취향(ex, 현대적, 전통적 등)을 분석하여 Exhibition DB에 있는 Accounts Table에 들어있는 키워드로 분류하여 회원정보와 함께 저장한다.<br><br>
🔍**필터 정렬(읽기; 최신순, 취향별)**<br>
Exhibition_detail Table로부터 등록된 전시회 리스트를 받아온 후 필터를 사용해 취향별 (키워드), 최신순으로 정렬하고 이를 사용자에게 보여준다.<br><br>
🔍**전시정보<사용자>(삽입, 읽기, 상세정보)**<br>
사용자가 전시회 리스트에서 누른 전시의 상세정보를 보여준다. 상세정보는 전시회 이름, 전시회 상세설명, 장소, 가격, 공식홈페이지 링크, 사진 촬영 가능 여부를 포함한다.<br><br>
🔍**전시정보<관리자>(삽입, 삭제, 갱신(수정); 상세정보)**<br>
전시정보를 등록하는 것으로 전시회 이름, 전시회 상세설명, 장소, 가격, 공식홈페이지 링크, 사진 촬영 가능 여부에 대한 정보를 삽입, 삭제, 갱신(수정)이 가능하도록 한다.<br><br>


## 👩🏻‍💻 멤버

### Front-end/back-end

|               | github                             |
| ------------- | ---------------------------------- |
| **김지원** 🥇 |https://github.com/kjw4420    |
| 조서현        |         |

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


