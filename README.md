# 오르미 클라이밍 커뮤니티

## 프로젝트 소개
오르미 클라이밍 커뮤니티는 등반을 사랑하는 사람들이 함께 정보를 공유하고, 소통하며,  
클라이밍 활동을 즐길 수 있는 클라이밍 통합 **플랫폼**입니다.  
관리자, 크루장, 운영진, 일반 회원 등 역할별로 로그인 및 권한이 부여되며,  
**공지사항**, **갤러리**, **크루(모임) 생성 및 참여** 등 다양한 기능을 제공합니다.

---

## 주요 기능

### 1. 메인화면
- `공지사항`, `갤러리`, `크루 가입/생성`, `나의 크루` 등의 메뉴가 직관적으로 배치  
- 반응형 디자인 적용으로 모바일/태블릿에서도 편리하게 이용 가능
<img src="https://github.com/user-attachments/assets/5747c95d-5e56-495d-86c5-08bd8199126f" alt="스크린샷" style="width:70%;" />

### 2. 로그인 및 회원가입
- **관리자, 일반 회원** 모두 개별 로그인 페이지 제공  
- **BCrypt**를 이용한 안전한 암호화 및 로그인 검증  (구현예정)
- 회원가입 시 **아이디, 비밀번호, 이름, 생년월일, 이메일, 전화번호**  정보 입력
<br><br>


**[관리자 로그인]**
> 관리자 로그인: 관리자 전용 계정으로 시스템 내 모든 기능을 제어할 수 있습니다.<br>
<img src="https://github.com/user-attachments/assets/e15c6263-e2ce-4577-88d4-3864083756f8" alt="관리자 로그인" style="width:70%;" />
<br><br><br><br>

**[일반 회원 로그인]**  
> 일반 회원 로그인: 등반자 및 일반 사용자를 위한 로그인 페이지입니다.<br>
<img src="https://github.com/user-attachments/assets/904b1a73-be11-49b5-bd02-5c07e5b1025a" alt="일반회원 로그인" style="width:70%;" />
<br><br><br><br>


**[회원가입]**  
> 회원가입: 필요한 정보를 입력하고, 비밀번호를 설정하여 가입 완료<br>
<img src="https://github.com/user-attachments/assets/1dab542a-1bc6-4f54-8b64-cc857897c1a5" alt="회원가입" style="width:70%;" />
<br><br><br><br>



<br>

### 3. 공지사항 관리
- **관리자 전용**: 관리자만 접근 가능한 공지사항 관리 페이지 제공  <br>
- 공지사항 **생성**, **수정**, **삭제** 기능을 제공하며, 수정 및 삭제 시 즉시 반영

<br><br>

**[관리자 공지사항 접근]**  
<img src="https://github.com/user-attachments/assets/180ae6ca-9a53-477e-9c25-443f91b9e18e" alt="관리자 공지사항 접근" style="width:70%;" /><br><br><br><br>
<br><br><br><br>

**[관리자 공지사항 생성/수정/삭제]**  
> 관리자 공지사항 페이지: 등록된 공지사항 목록 확인, 신규 작성, 내용 수정, 삭제 가능  <br>

<img src="https://github.com/user-attachments/assets/d60e171a-ddb3-4eb0-a623-a11c10a22c33" alt="관리자 공지사항 생성/수정/삭제" style="width:70%;" /><br><br><br><br>
<br><br><br><br>

**[일반 회원 공지사항 접근]**  
> 일반 회원: 공지사항을 확인하고, 댓글이나 좋아요 등으로 의견을 남길 수 있습니다 <br>

<img src="https://github.com/user-attachments/assets/0f57ba01-49d9-4fd9-a7ee-29660898bafc" alt="일반 회원 공지사항 접근" style="width:70%;" /><br><br><br><br>
<br><br><br><br>

---
---

### 4. 갤러리 (구현예정)
- **사진 업로드**: 회원이 직접 클라이밍 사진을 올리고, 좋아요와 댓글로 소통  
- 클라이밍 활동 사진을 모아 볼 수 있어 커뮤니티 활성화에 기여

---

### 5. 크루 가입하기 / 크루 생성하기 (구현예정)
- 새로운 크루를 생성하거나, 이미 만들어진 크루에 가입 가능  
- 크루별로 일정 및 게시글을 공유하며 등반 활동을 함께할 수 있습니다

---

### 6. 나의 크루 (구현예정)
- 자신이 가입한 크루 목록을 한눈에 확인 가능  
- 크루별 일정, 공지사항, 사진 등을 모아볼 수 있습니다

---

## 사용 기술
- **Frontend**: React (Vite), HTML, CSS  
- **Backend**: Spring Boot, Spring Framework, Gradle
- **Database**: MySQL, MyBatis  
- **보안**: BCrypt를 통한 비밀번호 암호화, 세션 기반 로그인  
- **기타**: 반응형 디자인, REST API
- **빌드도구**: Gradle
---
