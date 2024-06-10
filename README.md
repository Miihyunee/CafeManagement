# ☕ Cafe Management (1st Team Project)

첫번째 팀프로젝트입니다.
주위에서 흔히 접할 수 있는 무인 카페 시스템을 관리자 입장에서 구현해보았습니다.

<br><br>

## 🔖 목차
[1. 프로젝트 개요](#-1.-프로젝트-개요)
   - [개발 기간](#-개발-기간)
   - [사용 기술](#-사용-기술)
   - [팀원 소개](#-팀원-소개)
     
<br>

[2. 프로그램 구조](#-2.-프로그램-구조)
   - [ER Diagram](#-ER-Diagram)
   - [Usecase Diagram](#-Usecase-Diagram)
   - [테이블 명세서](#-테이블-명세서)

<br>

[3. 개별 페이지 안내](#-3.-개별-페이지-안내)

<br> 

[4. 후기 및 개선점](#-4.-후기-및-개선점)
   - [후기](#-후기)
   - [개선점](#-개선점)
<br><br>

## 1. 프로젝트 개요
### 🗓 개발 기간
* 2023.12.18 ~ 2024.1.10
* 1주차 : 프로젝트 기획 및 화면 설계, DB 구축, 파트별 레이아웃 및 핵심 기능 설계
* 2주차 : 파트별 DB 설계 및 구축, 프로그램 화면 및 세부 기능 구현, 1차 통합 및 프레젠테이션 자료 준비
* 3주차 : 기능 테스트 진행 및 2차 통합, 최종 점검 및 프로젝트 완성

<br><br>

### 🖥 사용 기술
* OS : <img src="https://img.shields.io/badge/windows 11-0078D4?style=for-the-badge&logo=windows11&logoColor=white"> <img src="https://img.shields.io/badge/android-34A853?style=for-the-badge&logo=android&logoColor=white"> 
* Language : <img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white">
* DB : <img src="https://img.shields.io/badge/sqlite-003B57?style=for-the-badge&logo=sqlite&logoColor=white">
* Tools : <img src="https://img.shields.io/badge/android studio-3DDC84?style=for-the-badge&logo=androidstudio&logoColor=white">
* Test device : Emulator (Pixel XL API 34)

<br><br>
### 👩‍💻 팀원 소개
* [도경민](https://github.com/mindyhere)
  : 메뉴 관리
* 박미현🙋‍♀️
  : 재고 관리
* [양미영](https://github.com/didaldud)
  : 메인 화면
* [조연우](https://github.com/yunuyununu)
  : 매출 관리
* [홍재희](https://github.com/jh91019)
  : 회원 관리
  
<br><br>

## 2. 프로그램 구조
### 🔹 ER Diagram
![erDiagram](https://github.com/Miihyunee/CafeManagement/assets/151993240/70e248d1-a79c-42d5-b056-0240cd307183)


### 🔹 Usecase Diagram
![usecase](https://github.com/Miihyunee/CafeManagement/assets/151993240/1e849b0f-62ef-4467-bc7a-94c518d0e8af)


### 🔹 테이블 명세서
![db1](https://github.com/Miihyunee/CafeManagement/assets/151993240/373a261c-d24b-4264-8c71-c2d554cfe69f)

![db2](https://github.com/Miihyunee/CafeManagement/assets/151993240/a6a195b3-b6b0-4425-83f8-0f33286c63ce)



## 3. 개별 페이지 안내



## 4. 후기 및 개선점
### 📝 후기
- 웹 & 앱에서 각 이용되는 데이터베이스를 사용해 봄으로써 데이터베이스의 종류에 대해 알게 됨
- 기본 제공 위젯이나 어댑터 등을 각자 다양한 방식로 활용해 보며 많은 공부가 되었음
- 파트 분담 후 통합하는 과정에서 서로 간에 충분한 논의나 주석 활용을 통해 더 효율적으로 진행하지 못한 점이 아쉬움으로 남음
<br><br>
### 🛠 개선점
- 전체 프로젝트 structure 및 각 액티비티에 공통으로 사용되는 메소드를 호출하는 방식 등을 고려한 재구성
- 더 간결하고 깔끔한 코드로 구성하여 가독성 향상 
- 향후 훈련 과정을 통해 학습하게 될 jsp, Spring 등을 활용하여 웹과 연동할 수 있도록 추가 확장
- 관리자 계정 등록 기능 및 사용자 화면 구성하여 연결
