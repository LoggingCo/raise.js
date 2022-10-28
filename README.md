## How to Run

1. 환경변수 설정하기 (cd server) > process.env 파일 생성

```javascript
mongoURI = '몽고 아틀라스 주소 입력';
TOKEN_SECRET = adsdasdasda;
```

2. cd server > yarn install (모듈 설치)
3. cd client > yarn install (모듈 설치)
4. cd server > yarn run dev (클라이언트, 서버 동시 실행)

---

## 🛠 Feature

### 로그인

1. JWT 인증방식을 이용하여 로그인
2. 로그인 시 이메일 중복확인
3. 로그인시 헤더에 이용자 이름 출력

### 회원가입

1. useForm 라이브러리 사용
2. watch를 이용하여 비밀번호, 비밀번호 확인 실시간 비교
3. 회원가입 클릭시 이메일 중복체크
4. 아이디(이메일 형식) 및 비밀번호(영문 대소문자, 숫자, 특수문자 포함) 정규식 적용
5. 필수 정보 입력(이메일, 비밀번호, 이름, 깃헙주소, 자기소개) 후 회원가입 승인

### 게시판

1. @material-ui/lab/Pagination 라이브러리를 활용하여 페이지네이션 구현
2. 실명 게시판 글 작성 및 수정, 삭제 기능 구현
3. 댓글 작성 및 수정, 삭제 기능 구현, 대댓글 작성 기능 구현
4. 게시글 좋아요 기능 구현
5. 게시글 작성자가 자신의 게시글에 댓글을 달 경우 색깔 표시 및 이름 옆 (작성자) 표시
6. 게시글 작성시간 표시 내림차순(createdAt: -1) 정렬

### 마이페이지

1. 계정 정보 변경하기 (이메일, 비밀번호, 깃헙 주소)
2. 내가 쓴 게시글, 내가 쓴 댓글, 내가 좋아요 누른 게시글, 내가 대댓글 단 댓글 확인 및 수정
3. 회원탈퇴시 작성한 게시글, 댓글, 대댓글 및 좋아요 데이터 삭제

---

## ⚙️ Library

## FrontEnd

- Redux
- React-Router
- Styled-components
- useForm(react-hook-form)
- Axios
- @material-ui
- @loadable/component
- redux-thunk, redux-promise

## BackEnd

- dotenv 환경변수 설정
- Mongoose (MongoDB)
- Bcrypt (암호화)
- JWT (인증방식)
- Express.js

## Preview
<img width="352" alt="9" src="https://user-images.githubusercontent.com/109440399/198485975-6bc6a2e0-8cf4-469f-a54c-8db115b31109.png">
<img width="649" alt="8" src="https://user-images.githubusercontent.com/109440399/198485990-54af4724-ecc2-4ab8-9593-46ee3eee7cb4.png">

