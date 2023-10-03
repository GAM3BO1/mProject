<img src="https://capsule-render.vercel.app/api?type=soft&color=36AD4A&height=200&section=header&text=%EC%82%B0%EB%84%98%EC%96%B4%EC%82%B0&fontSize=70&fontColor=FFFFFF" />

# Team Project
"산넘어산"
- 프로젝트 주소 : https://github.com/SeungahhHam/mProject
- 기간 : 2022.03 - 2023.06
- 팀원 : FrontEnd 3명, BackEnd 2명, AR 담당 1명

## 프로젝트 개요

---
### 목적

- 산에 대한 다양한 정보를 제공하고 등산 배지를 모으며 도전 과제를 통해 성취감을 주고 이용자의 등산 기록을 관리
- 커뮤니티 등을 통해 자신이 아는 등산 정보를 공유하고 다른 사용자의 정보를 구체적으로 이용할 수 있도록 함
- 위의 기능들을 통해 등산 초보자에게도 더 쉽게 등산에 도전할 수 있게 하며 숙련자에게도 더 많은 기회가 되도록 함

### 주요 기능

- AR배지 수집을 통한 자신이 한 산행 기록 가능
- 사용자의 편리성을 중심으로 한직관적인 UI 
- 커뮤니티 기능
- 위급상황시 구조 요청 기능 제공


## 기술 스택

---
<div style="display : flex">
    <img src="https://img.shields.io/badge/React Native-61DAFB?style=flat&logo=React&logoColor=white" />
    <img src="https://img.shields.io/badge/javascript-F7DF1E?style=flat&logo=javascript&logoColor=white"/>
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=CSS3&logoColor=white" />
    <img src="https://img.shields.io/badge/AXIOS-5A29E4?style=flat&logo=AXIOS&logoColor=white" />
</div>
<br/>
<div style="display : flex">
    <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=Node.js&logoColor=white" />
    <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=MongoDB&logoColor=white"/> 
    <img src="https://img.shields.io/badge/Amazon EC2-FF9900?style=flat&logo=Amazon EC2&logoColor=white"/> 
    <img src="https://img.shields.io/badge/Unity-000000?style=flat&logo=Unity&logoColor=white"/>
</div>
<br/>
<div style="display : flex">
    <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white"/> 
    <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=gitHub&logoColor=white"/>  
</div>

### React-Native

- 시스템 사용자를 위한 GUI 개발 도구인 JavaScript 라이브러리인 react와 native를 결합한 react-native를 이용하여 개발한다.
- AWS의 EC2 서버와 정보를 통신해 UI를 출력한다.
- 서버에서 받아온 산의 좌표를 이용해 Kakao 지도 API를 통한 웹뷰로 지도를 띄운다.

### Node.js

- 공공데이터 api를 이용하여 산의 정보와 실시간 날씨 데이터를 axios를 이용하여 받아오고 MongoDB 데이터베이스와 연결해 정보를 저장한다.
- nodejs의 웹 프레임워크인 express와 POST/GET 방식을 이용해 Client에 정보를 보낸다. 

### MongoDB

- Cluster를 생성하고 내부에 user, bordC, bordF, bordQ, bordR, 16개의 지역별 mountain, mountain_list collection을 만든다. 
- Mongoose 모듈을 이용하여 데이터 Creat, Read, Update, Delete를 사용한다.

### Unity & AR Foundation

- React-native 내부에 embedding한 유니티 파일을 이용한다.
- unity 내에서 AR 기능을 사용하기 위해 AR Foundation를 사용하였다.
- AR Foundation은 증강현실 플랫폼을 사용할 수 있도록 지원하고 개발자가 사용할 수 있는 인터페이스를 제공한다.
- AR Foundation에서 사용한 기술들은 Plane detection(평면 감지)와 Raycast이다.

### Git, GitHub

- Git으로 소스 코드 버전 관리를 하고 GitHub을 통해 협업한다. 
- GitHub의 Pull Request와 Code Review 기능을 활용하여 코드 품질을 향상시킨다.
- 버전관리 전략으로는 Git Flow를 이용하여 진행한다.
- 모든 브랜치는 Pull Request에 리뷰를 진행한 후 merge를 진행한다.

## 팀원 및 구현기능   

---

### [백엔드]
함승아 (팀장) 
- 전체적인 프로젝트 관리
- 각종 서류, 보고서 및 SW명세서 작성
- 전체적인 서버 기능과 데이터 베이스 구현
- Unity 서버통신 및 AR기능 임베딩
- react-native의 현재 좌표 서버로 전송 논문 작성/발표

이수민
- AWS EC2 서버 구축
- AWS S3 버킷 생성 및 스토리지 관리 / API 구현
- Github Action, AWS CodeDeploy를 이용한 CI/CD 구현
- 논문 발표 준비
- 유튜브 동영상 시나리오 작성


### [프론트엔드]
김준혁
- 프로젝트의 전체적인 화면 구성 설계
- 로그인, 구조요청, 커뮤니티 페이지 구현
- 클라이언트와 서버 간 이미지 처리 및 데이터 전송구현
- 전체적인 코드 정리
- 유튜브 동영상 편집

김경원
- 메인페이지와 커뮤니티페이지 UI 구현
- 메인페이지 구현 및 키워드추천 기능과 날씨정보제공 기능 구현
- 팀포스터 제작
- 최종 발표자료 작성 

이슬아
- User정보페이지 구현
- 로그인페이지, User정보페이지, 인증게시판 페이지 UI 구현
- 팀 포스터 제작
- 최종 발표 자료 작성


### [AR 담당]
손유정
- AR기능구현
- 유니티와 node.js 서버 연결
- 논문 발표 준비/ 유튜브 동영상 시나리오 작성


## 프로젝트 설계 문서

---
- 개발 구조도

![image](https://github.com/GAM3BO1/mProject/assets/95689059/22ec3adb-36b6-4f33-a106-03ac081d602c)



- 조직도

![조직도1](https://github.com/GAM3BO1/mProject/assets/95689059/1414c509-9f68-401f-8c6e-1b780735c0bb)


## 화면 설계 

---
![산출물1](https://github.com/GAM3BO1/mProject/assets/95689059/633426dd-66eb-43e2-919b-b91f783555a1)

![산출물2](https://github.com/GAM3BO1/mProject/assets/95689059/4aee194a-9568-488d-bfe6-d2772354b9fa)

![산출물3](https://github.com/GAM3BO1/mProject/assets/95689059/a40cb65e-dc01-4576-9959-26425ac28110)

![산출물4](https://github.com/GAM3BO1/mProject/assets/95689059/6ef6922b-4989-4ea7-8a19-ab1184bb3e0a)

![산출물5](https://github.com/GAM3BO1/mProject/assets/95689059/4710567e-dcc6-4726-a446-8af51fce5401)
