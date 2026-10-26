<p align="center">
  <img alt="HERE" src="https://github.com/TeamProcess11/.github/raw/main/profile/Here.png" />
</p>

# HERE
> 교내 분실물을 쉽고 빠르게 등록·검색·찾을 수 있는 웹 서비스

## 서비스 소개
 
### 문제 정의
 
학교 단체 채팅방에는 분실물 관련 글이 자주 올라오지만, 지나간 글을 다시 찾기 번거롭고 스크롤하며 뒤져야 합니다.
분실물만 따로 모아 볼 수 있어야 주인을 빨리 찾을 수 있습니다.
 
### 서비스 흐름

- **분실자**: 분실물을 등록하고, 습득물 목록에서 비슷한 물건을 찾아 댓글로 연락한 뒤, 물건을 찾으면 상태를 '완료'로 바꿉니다.
- **습득자**: 습득물을 등록하고, 분실자가 댓글을 남기면 물건을 전달하거나 지정된 장소(예: 교무실)에 맡긴 뒤 상태를 '완료'로 바꿉니다.

---
 
## 주요 기능
 
| 영역 | 기능 |
| --- | --- |
| 회원 | 회원가입(아이디 중복 확인, 비밀번호 설정, 학번·이름 입력), 로그인, 로그아웃, 프로필 사진 변경 |
| 게시글 | 분실물·습득물 등록(제목, 사진, 카테고리, 위치, 분실·습득 일시), 목록·상세 조회, 본인 글 수정·삭제 |
| 상태 관리 | 게시글 상태를 찾는 중(`FINDING`) → 완료(`COMPLETED`)로 변경 |
| 탐색 | 카테고리별 분류, 최신순 / 오래된순 정렬, 단어 검색 (예: 에어팟, 생활복) |
| 댓글 | 게시글에 댓글 작성·조회·수정·삭제, 본인 댓글만 수정·삭제 |
 
- 게시글 등록과 댓글 작성은 회원가입 / 로그인이 필요합니다.
 
---
 
## 기술 스택
 
### Frontend
 
| 분류 | 기술 |
| --- | --- |
| Language | HTML, CSS, JavaScript |
| Library | React |
| Build Tool | Vite |
 
### Backend
 
| 분류 | 기술 |
| --- | --- |
| Language | Java |
| Framework | Spring Boot |
| Auth | Spring Security, JWT |
| Persistence | Spring Data JPA, MySQL |
 
### Tools
 
| 분류 | 기술 |
| --- | --- |
| Design | Figma |
| Version Control | Git, GitHub |
| Docs | Notion |
 
---
 
