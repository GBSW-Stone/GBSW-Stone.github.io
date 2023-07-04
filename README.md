<h2 align="middle">경북소프트웨어고등학교 SowonLive [ Team - Stone ]</h2>

# SowonLive
> 교내 익명 커뮤니티

## 프로젝트 개요
### 주제 및 선정 배경
- 기숙사 및 학교의 중요 공지나 안내사항을 듣지 못하는 상황이 줄어들어 생활개선 및 선후배 사이의 교류가 활발해지며 나아가 학교의 좋은 분위기의 커뮤니티 형성을 본 프로젝트 목표로 선정하였음.

###개발 수행 및 목표
- 교내 커뮤니티 활성화
- 선후배 친구 사이의 활발한 소통
## 팀소개
* 김창환 -
(팀장), 디자인, 프론트 보조 문서 관리 및 발표 | <a href="https://github.com/Takoyaa" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/></a>
* 변예준 - 
(팀원) 프론트 및 백엔드 개발 및 DB 서버 구축 관리 총괄 | <a href="https://github.com/yejun178" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/></a>


### 사용기술
- Frontend
  - Javascript
  
- Backend
  - Node.js
  
### Framework
- Frontend
  - React
- Backend
  - Express.js
  
### Database
- Backend
  - MongoDB
  
### Library
- Frontend
  - Redux
  - Styled-components
  - Axios
  - @material-ui/lab

- Backend
  - Mongoose
  - Bcrypt
  - JWT

  - Server
  - AWS (EC2)


## 프로젝트 진행 과정 (월별 진행 상황)
 + 프로젝트 구상과 팀원 역할 분배(2023년 4/1  ~ 4/30)
 + 프론트 UI/UX 구성 및 디자인(2023년 4/31 ~ 5/10)
 + 프론트 개발 및 모바일 반응형 페이지 제작 (5/10 ~ 5/31)
 + 백엔드 및 API 개발 및 보안 점검 (6/1 ~ 6/31)
 + 서버 구축 및 배포 오류 수정 및 디버깅 (7/1 ~)
## 프로젝트 상세 소개
#### 로그인 & 회원가입
<p align="center">
  <img width="280" alt="7" src="https://github.com/GBSW-Stone/.github/assets/64297220/d1f9686a-251e-451b-86e5-bcce1d09716d">
  &nbsp;&nbsp;&nbsp;
  <img width="280" alt="7" src="https://github.com/GBSW-Stone/.github/assets/64297220/693d0cd2-1e2a-4be4-ba1f-d61ff6082a13">
</p>

### 데이터베이스 구조
#### 유저 테이블
| Field | data type | explanation | properties |
| ---------- | -------- | --------------- | -------- |
| id | String | 사용자 아이디 |
| grade | INT | 학년 | N |
| class | INT | 반 | N |
| number | INT | 번호 | N |
| name | VARCHAR(10) | 이름 | NN |
| phone | VARCHAR(11) | 유저 전화번호 | NN |
| account | VARCHAR(30) | 계정 아이디 | NN |
| password | CHAR(64) | 비밀번호 | NN |
| position | TINYINT | 역할을 숫자로 나누어 중,고등학생과 중,고등 교사를 구분 | NN |
| salt | VARCHAR(10) | 입력된 비밀번호와 함께 HASH함수에 넣어 주는 값 | NN |

## 사용자 수행 흐름도


## Preview

### [Github.io 페이지](https://github.com/GBSW-Stone)
