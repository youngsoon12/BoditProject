# 프리온보딩 2주차 과제 - 7Team

### WEEK 1-2 - 보딧
- 과제 목표 : 센서 리스트와 데이터 그래프 대시보드 화면 만들기
- 수행 기간 : 2022/10/7 ~ 2022/10/9 (3일)

<br><br>

# 배포 링크
- [링크](https://bodit-team7.netlify.app/)

<br><br>

# 7팀 소개 및 역할
 
| 이름   | 역할  |
| ------ | ------ |
| 김영수 | 초기 셋팅 |
| 서수민 | 그래프 , 확대/축소 기능 |
| 정억화 | 센서 리스트, 달력, csv export 버튼 |

<br><br>

# 프로젝트 실행 방법
1. git clone
```bash
 git clone https://github.com/youngsoon12/BoditProject.git
```
2. npm install
```bash
 $ npm install
```
3. project start
```bash
 $ npm start
```

<br><br>

# 프로젝트 구조
```bash
📦src
 ┣ 📂api
 ┃ ┗ 📜get.js
 ┣ 📂components
 ┃ ┗ 📜components.js
 ┣ 📂pages
 ┃ ┣ 📂GraphDashBoard
 ┃ ┃ ┣ 📂components
 ┃ ┃ ┃ ┣ 📜Graph.js
 ┃ ┃ ┃ ┗ 📜GraphLayout.js
 ┃ ┃ ┗ 📜GraphDashBoard.js
 ┃ ┣ 📂SensorList
 ┃ ┃ ┣ 📂components
 ┃ ┃ ┃ ┣ 📜BackTopBtn.js
 ┃ ┃ ┃ ┣ 📜GraphDash.js
 ┃ ┃ ┃ ┗ 📜TableBoard.js
 ┃ ┃ ┣ 📜sensorlist.css
 ┃ ┃ ┗ 📜SensorList.js
 ┃ ┗ 📜pages.js
 ┣ 📂styles
 ┃ ┣ 📜GlobalStyle.js
 ┃ ┗ 📜theme.js
 ┣ 📜index.css
 ┣ 📜index.js
 ┗ 📜Router.js
```

<br><br>

# 사용기술 스택

<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=HTML5&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white"/> <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=white"/> <img src="https://img.shields.io/badge/React Router-CA4245?style=flat-square&logo=React-Router&logoColor=white"/> <img src="https://img.shields.io/badge/styled components-DB7093?style=flat-square&logo=styled-components&logoColor=white"/>

<br><br>

# 과제 및 구현 내용

## 과제 요건

#### 공통

- 반응형 레이아웃 구현
- 작업물 배포

<br>

#### 센서 리스트(첫번째 화면)

- 센서 리스트 출력
- 내림차순, 올림차순 정렬
- 다중 필터링
- hover 기능 구현
- 20%이하 배터리 부족 표시
  
<br>

#### 그래프(두번째 화면)

- 온도,습도,기압 세가지 그래프 표시
- 특정 날짜 선택하여 해당 데이터(24시간) 확인
- 그래프 x축 확대 / 축소 기능 구현
- 데이터를 csv로 export
- 입력 데이터는 API요청
<br>

## 구현 내용

### 공통

- axios를 이용한 api 통신으로 데이터를 불러옴
- 동적 라우팅 구현
- 반응형 디자인 적용(web, tablet, mobile)

<br>

### 센서 리스트(첫번째 화면)


#### 센서 목록 화면
- ANTD 라이브러리를 사용하요 TABLE구현 


<br>

### 데이터 그래프 대시 보드(두번째 화면)

#### 그래프
- 
<br>

#### 달력(날짜 선택)
- 

#### csv export
- 
<br>
<br><br>

# 팀 노션
- [링크](https://www.notion.so/wecode/7-d9c9440b686f465bbda33f31a87b6e2f)
