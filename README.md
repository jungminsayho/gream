# 🖼 Gream

## 📍 프로젝트 개요
- **Kream 사이트를 모티브로 한 그림 거래중개 사이트 구현 프로젝트**
- **기 간**: 2021.07.19.~2021.07.30.(12일)
- **Team member**
  - Frontend: 3인(박정훈, 오지수, 이경민)
  - Backend: 3인(김한준, 서정민, 안재경)

<br>
       
## 📍 프로젝트 미리보기

![](https://images.velog.io/images/anjaekk/post/a48be216-befc-4a4b-903b-db86a34a289a/Jul-26-2021_13-16-47.gif)<br><br>
<a href="https://www.youtube.com/watch?v=Mvr7map6Y2M">데모영상 클릭</a>

<br>

## 📍 Database 설계

<details>
<summary>Database modeling</summary>
<div markdown="2">       

![image](https://user-images.githubusercontent.com/74139727/130344978-22559128-4640-45d2-a726-072be9b1fce5.png)

</div>
</details>

<br>

## 📍 구현 기능
-Unit test를 통한 코드 검사

|User(회원가입 및 로그인)|Product(상품 리스트, 상세보기)|Contract(입찰, 판매, 계약)|
|:-:|:-:|:-:|
|Bcrypt 암호화|pagination|구매자와 판매자 동일가격 입찰 체결|
|JWT 사용|카테고리별 정렬|입찰 CRUD|
|카카오 로그인 API|베스트작가, 구매, 판매 filtering|입찰상태 업데이트|
|회원가입 유효성 검사|최근 체결거래 기간별 filtering|
||계약금액 변동내역 조회||

<br>

## 📍 내가 구현한 기능
- Query Parameter를 통해, 판매/구매 구분하여 입찰 등록 기능 구현
- 기존에 등록되어 있는 입찰과 매칭시키는 즉시거래 기능 구현
- Crontab을 이용하여, 입찰기한에 따른 입찰 상태 업데이트 기능 구현
- Python 표준 라이브러리인 unittest 모듈을 통한 unit-test 진행

<br>

## 📍 API Documentation
https://documenter.getpostman.com/view/16450829/TzsZqTM6

<br>

## 📍 프로젝트 진행
<details>
<summary>Trello를 이용한 Scrum관리</summary>
<div markdown="1">       

![image](https://user-images.githubusercontent.com/74139727/130344934-2cd9d61b-26ac-4ced-b90e-3f6335ead0a2.png)


</div>
</details>

- 매일 어제 한 일, 오늘 할 일, 특이사항 공유 stand up meeting 진행
- 미팅전 Agenda 공유 
