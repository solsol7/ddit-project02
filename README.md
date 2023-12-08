# Project- NORI 대전


## 🖥️ 프로젝트 소개
대전의 관광지와 맛집을 소개하고 여행 일정을 관리할 수 있는 사이트입니다.
<br>

## 🕰️ 개발기간
* 23.07.24 - 23.08.22 (4주)

### 🧑‍🤝‍🧑 구성원 소개 및 역할
 - 개발인원 : 6명
 - 팀장  : 문선영 - 맛집 게시판, 일정 관리(목록 조회)
 - 팀원1 : 이은솔 - 관광지 게시판, 일정 관리(일정 등록 및 수정)
 - 팀원2 : 김원희 - 쿠폰 관리, 문의 게시판, 이벤트 게시판, 메인 CSS
 - 팀원3 : 이기웅 - 자유게시판, 마이페이지
 - 팀원4 : 김도현 - 댓글, FAQ
 - 팀원5 : 김소원 - 로그인, 회원가입, ID찾기, PW찾기, 공지사항 게시판

### ⚙️ 개발 환경
- `Java 8`
- `JDK 1.8.0`
- **IDE** : ECLIPSE
- **Database** : Oracle DB(11xe)
- **ORM** : Mybatis

## 📌 주요 기능
### 공통기능
#### 로그인
- ID 검증 및 로그인
- ID찾기, PW찾기
#### 회원가입
- 주소 API 연동
- ID 중복 체크
---
### 관리자
#### 맛집/관광지 게시판
- 관광지/맛집 CRUD
#### 공지사항게시판 관리
- 공지사항 CRUD
#### 자유게시판 관리
- 게시글 조회, 삭제
---
### 사용자
#### 맛집/관광지 게시판
- 관광지/ 맛집 조회
- 지도 출력
- 좋아요, 싫어요 기능
- 댓글 기능
#### 일정 관리
- 관광지/맛집 검색
- 관광지/맛집 클릭 시 지도 출력
- 일자별 일정 등록 및 수정
#### 자유게시판
- 게시판 CRUD
#### 문의게시판
- 게시판 CRUD