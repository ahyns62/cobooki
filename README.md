# ✨Cobooki (Coding + book + IT)

![Untitled](https://github.com/ahyns62/cobooki/assets/90846224/afbbe38b-a6fc-4569-9233-f6900493b025)

## ✅ 서비스 소개

### IT 도서 판매 쇼핑몰입니다.

상품 등록, 장바구니 추가, 주문하기 등 쇼핑몰의 핵심 서비스를 구현합니다.

- 대상 페르소나 : 프론트엔드/백엔드/CS지식 개발 공부를 하고 있는 사람들 대상

![Untitled](https://github.com/ahyns62/cobooki/assets/90846224/39130847-3386-458e-a5e0-e6611defe6dc)

### 💡 기술스택

- **프론트엔드**

| EJS(HTML+JS) | 동적 페이지, 데이터와 뷰의 분리, 클라이언트와 서버 간 상호작용 쉽게 처리 가능 |
| ------------ | ----------------------------------------------------------------------------- |
| CSS          | 디자인을 독립적으로 관리 가능                                                 |

- **백엔드**

| Node.js | 빠른 속도와 단일 언어로 개발 가능 |
| ------- | --------------------------------- |
| Express | 간편한 라우팅 및 미들웨어 설정    |
| MongoDB | 대량의 데이터 처리 및 빠른 속도   |

- **배포**

| PM2 | 프로세스 관리 및 로그 관리에 용이 |
| --- | --------------------------------- |

### 💡 배포링크

[cobooki](http://kdt-sw-5-team04.elicecoding.com/)

### 💡시연 가능 계정

|           | 이메일            | 비밀번호  |
| --------- | ----------------- | --------- |
| 일반 회원 | test@naver.com    | test12345 |
| 관리자    | test333@naver.com | 123456789 |

## ✅ 서비스 주요 기능 설명

### 2-1 로그인

- 로그인/로그아웃
- 이메일, 비밀번호 로컬스토리지 및 세션 저장

### 2-2 회원가입

- 유효성 검사

### 2-3 회원

- 관리자와 일반사용자 계정을 구분하여 페이지 접근 분리
- 회원정보수정 및 탈퇴

### 2-4 주문

- 카테고리 리스트에서 상품을 선택
- 주문목록 및 상품 주문서 조회

### 2-5 상품

- 상품 상세 정보 열람
- 장바구니에 담아 구매
- 장바구니 리스트 중 선택적으로 구매
- 장바구니 리스트 중 부분 삭제

### 2-6 관리자

- 전체 회원 관리 조회 및 수정
- 상품 등록(상품명, 상세설명, 카테고리, 가격, 수량)
- 주문 취소
- 배송상태 수정
- 사용자 주문 리스트 조회(주문 일자, 정보, 총액)

## ✅ 상세 구조

### 💡 와이어프레임

[https://www.figma.com/file/A344rM70qGHZyYcdFtWQE7/%EB%B6%88%EC%82%AC%EC%A1%B0(4%ED%8C%80)?type=design&node-id=0-1&mode=design&t=vksy9oAPII30G4GX-0](<https://www.figma.com/file/A344rM70qGHZyYcdFtWQE7/%EB%B6%88%EC%82%AC%EC%A1%B0(4%ED%8C%80)?type=design&node-id=0-1&mode=design&t=vksy9oAPII30G4GX-0>)

### 💡 API 명세서

![Untitled](https://github.com/ahyns62/cobooki/assets/90846224/3caab481-e9f6-464c-b6bf-a8796249b7ea)

### 💡 인프라 구조

![Untitled](https://github.com/ahyns62/cobooki/assets/90846224/27f8b3e6-9e8a-48dc-944e-e71d3635e8cb)

### 💡 폴더 구조

- 프론트: `src/views` 폴더
- 백: src/views 이외 폴더 전체
- 실행: **프론트&백 동시에 express로 실행**

## ✅ 기타

### 💡 개발 기간

2023.07.03 ~ 2023.07.14 (12일)

### 💡 참여 인원

| 이름         | 담당 업무                                       |
| ------------ | ----------------------------------------------- |
| 고윤렬       | FE, 메인/회원가입/마이페이지/회원관리(관리자)   |
| 김세현       | BE, 전체 스키마 및 API 설계                     |
| 이아현(본인) | FE, 로그인/회원탈퇴/마이페이지/상품등록(관리자) |
| 위민영       | FE, 장바구니/주문내역/주문&회원관리(관리자)     |
| 황지우       | FE, 헤더&푸터/도서상세/결제                     |

## ✅ 실행 방법

1. 레포지토리를 클론하고자 하는 디렉토리에서 아래 명령어를 수행

```
git clone https://github.com/ahyns62/cobooki.git
```

1. 클론한 디렉토리에서 back-end 폴더로 들어가 아래 명령어를 통해 필요한 module 설치

```
npm install
```

1. back-end에서 필요한 `.env` 설정

```
MONGO_URI=mongodb+srv://devhyonie:sehyeon90@cluster0.vd2gs5n.mongodb.net/Express?retryWrites=true&w=majority
SECRET_KEY=code_book
```

1. express 앱을 실행

```
npm start
```
