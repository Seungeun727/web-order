# WEB-ORDER-SYSTEM

## 🔧 Tools
<img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat-round&logo=vue.js&logoColor=white"/> <img src="https://img.shields.io/badge/express-000000?style=flat-round&logo=Express&logoColor=white"/> <img src="https://img.shields.io/badge/Node.js-339933?style=flat-round&logo=node.js&logoColor=white"/> <img src="https://img.shields.io/badge/Mysql-4479A1?style=flat-round&logo=mysql&logoColor=white"/> <img src="https://img.shields.io/badge/Amazon EC2-FF9900?style=flat-round&logo=amazonec2&logoColor=white"/> <img src="https://img.shields.io/badge/Amazon S3-FF9900?style=flat-round&logo=amazons3&logoColor=white"/>  

<br />

## 🔦 Description   
- 모바일 웹 주문 결제 시스템 페이지  
- 비대면 주문 방식의 수요 증가와 키오스크 설치의 비용 감소를 위해 프로젝트 기획하였습니다.      

<br />   

## 📑프로젝트 PPT    

<br />

## ⏰ 프로젝트 개발 기간 
버전 | 기간| Git
-----|:----|:----
`v1.0`   | 2021년 10월 18일- 2021년 12월 27일 (총 2달) | [vue3-web-order](https://github.com/seun2230/web-order)
<span style="color:#00AAFF">v1.1</span> | 2022년 06월 3일 - 2022년 07월 15일(예정) | [vue3-web-order(refactor)](https://github.com/seun2230/vue3-web-order) 

<br />

## 🧑‍💻 프로젝트 팀원 역할
팀원 | 구분 | 업무  
-----|:----|:---
강호진 | Frontend | 회원관리, 라우팅, UI/UX
이성원 | FrontEnd & Backend | Datbase 설계, Server 구축, 메뉴 & 관리자페이지
노승은 | FrontEnd | 메뉴, 리뷰, UI/UX 

<br />

## 📁 프로젝트 폴더 구조
- frontend와 backend를 독립적인 디렉터리로 구성하였습니다.

<img src="https://user-images.githubusercontent.com/87456904/175061014-84edcce7-039c-433b-af71-e6b30c6f362c.png" width="400" height="400" />

<br />

## 📙프로젝트 구조도 
<img src="https://user-images.githubusercontent.com/87456904/175069036-72926cc7-8351-4ae0-8c6f-a04d7e940f65.jpg" width="600" height="400" />

<br />

## 🗃️ MySQL-ERD 
- 프로젝트 v2에서 쿠폰, 할인, 공지 계획

<img src="https://user-images.githubusercontent.com/87456904/175063480-0f12ac9e-45e9-4889-8851-cd0d6e4c7313.png" width="600" height="400" />

<br />

# 🔥WEB-ORDER-SYSTEM.v1 기능
- 관리자 페이지와 사용자 페이지로 구분하여 페이지를 구성했습니다.

## 📌 관리자 페이지(Admin page)    

1. **상품 관리**    
  - 상품 메뉴 폼 추가 및 이미지 업로드
  - 상품 메뉴 관리 테이블 추가, 삭제
  - 상품 주문 내역 관리 및 조리 완료 내역 기능   

2. **사용자 관리**
  - 총 리뷰 게시물 관리 테이블 추가, 삭제
  - 가입한 사용자 관리 테이블 추가, 삭제   

3. **홈화면 배너 이미지 관리** 

4. **슬라이드 이미지 & 공지 관리** 
  - 게시물 이미지 없는 경우 기본 이미지 추가,수정, 삭제

<br />

## 📌사용자 페이지(User page)   

### 1. **회원관리 기능** 

- 회원가입 시 사용자 정보 입력
- 로그인 
- 마이페이지
  - 사용자 회원 정보 수정 추가
  - 메뉴 평가를 위한 리뷰 작성 추가
  - 리뷰 좋아요 한 게시물 리스트 확인
- 폼검증 기능    

### 2. **메뉴 기능** 
  - 상품 수량 조절, 메뉴 추가, 선택 삭제
  - 메뉴 선택과 주문 결제 선택을 위한 스크롤 UI 추가
  - 주문 상세 내역 기능  
<br />

### 3. **리뷰 기능** 
  - SNS형 구조를 위한 시간순으로 리뷰 정렬
  - 개인정보수집
    - 주문한 고객과 정보 수집에 동의한 사용자만 리뷰 반영
  - 주문한 사용자의 리뷰 작성, 수정, 삭제 추가
  - 리뷰 작성 시 신뢰성 향상을 위한 평점, 키워드 추가
  - 리뷰 상세 페이지의 댓글, 좋아요 등 소셜 기능 추가 

<br />