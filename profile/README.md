# 수강신청 : 올클각

## 기간
2019.09.23 - 2019.12.23 (3달)

## 팀소개
### 팀명
    솜이가요 솜이가
### 팀원
    김명진 : 풀스택
    김채연 : 풀스택
    이예린 : 풀스택
    한수현 : 풀스택


## 프로젝트 소개
### 개발 동기
    매번 수강신청을 하기 위해서는 수강 신청 사이트 외에 다양한 창(서버 시간 사이트, 시간표 관리 어플 등)을 사용해야하는 불편함이 있다.
    그래서 기존 수강신청 사이트의 기능들은 그대로 유지하고 빈시간 강의 보기 기능, 위시리스트에 해당 강의를 몇명이 담았는지 보여주는 기능, 서버시간을 보여주는 기능 등 다양한 기능을 한번에 제공하여 편리한 수강신청 서비스를 만들고자 한다.

### Use Case
![usecase](https://github.com/course-registeration/.github/assets/75843997/edddcda7-d73e-4f84-9802-d21c975eb278)

### 주요 기능 및 세부기능
1. 로그인, 로그아웃
    - 교수용, 학생용
2. 사용자 정보 보여주기
    - 교수용, 학생용
3. 학생
    - 서버시간 보여주기 기능
    - 강의 검색 기능
        - 학과명, 교수명, 과목명, 학수번호로 검색하기
    - 수강신청 기능
        - 최종 위시리스트에서 신청하기
        - 검색을 통해서 신청하기
        - 강의의 신청 인원 보기
        - 최종 수강신청 결과 보기, 시간표로 보기
    - 위시리스트
        - 위시리스트 결과 보기
        - 빈 강의 추천 기능으로 담기
        - 담은 강의 삭제하기
        - 위시 테이블 추가, 삭제
        - 빈 시간 강의 보여주기
        - 최종 위시 테이블 설정하기
        - 강의를 위시리스트에 담은 인원 보기
        - 위시리스트 결과 보기, 시간표로 보기
        - 위시리스트에 있는 강의 우선순위 설정하기
4. 교수
    - 교수가 맡은 강의를 수강신청한 학생 인원 보기
    - 교수가 맡은 강의를 위시리스트에 담은 학생 인원 보기

### MVC 구조 및 request 처리 흐름 설계
- 미리보기
![MVC 구조 및 request 처리 흐름 설계](https://github.com/course-registeration/.github/assets/75843997/6260a5f2-db4f-420c-8642-88918844fbda)

- [MVC 구조 및 request 처리 흐름 설계](https://docs.google.com/spreadsheets/d/1wnTQ7MFoZn1KgMXSsMvs5PFGTgXUf2ouyigYE0AZJug/edit#gid=0)

### UI 및 request 처리 흐름도

![UI 및 request 처리 흐름도1](https://github.com/course-registeration/.github/assets/75843997/5911010b-ce1f-4dda-9dc7-adc7c67860e6)
![UI 및 request 처리 흐름도2](https://github.com/course-registeration/.github/assets/75843997/5e15027c-08d7-48b2-8ba9-580c0214b94d)
![UI 및 request 처리 흐름도3](https://github.com/course-registeration/.github/assets/75843997/e93afa0a-b2a9-442b-97f9-375dd108990d)
![UI 및 request 처리 흐름도4](https://github.com/course-registeration/.github/assets/75843997/1228150e-6fd4-4db4-8ab2-31a9e6b147b5)
![UI 및 request 처리 흐름도5](https://github.com/course-registeration/.github/assets/75843997/e29e5228-e2c5-4c05-b162-760fc7d7390c)
![UI 및 request 처리 흐름도6](https://github.com/course-registeration/.github/assets/75843997/1c19c0d1-a73c-468c-b331-61dfbfa082b0)
![UI 및 request 처리 흐름도7](https://github.com/course-registeration/.github/assets/75843997/786d90dd-45d2-440e-8f83-d31274c6efee)
![UI 및 request 처리 흐름도8](https://github.com/course-registeration/.github/assets/75843997/64f04e87-d08d-4aa8-b2ad-f890c78659a5)
![UI 및 request 처리 흐름도9](https://github.com/course-registeration/.github/assets/75843997/ce367158-e5aa-4f3e-8700-9cd961fd8542)

### 데이터 베이스 설계
![데이터 베이스 설계](https://github.com/course-registeration/.github/assets/75843997/c836a76e-06b3-41c1-9955-d10c4bdb9ea2)

### 클래스 설계
![클래스 설계](https://github.com/course-registeration/.github/assets/75843997/34044493-8649-4674-a4b5-1708aa9b84d8)

### 시스템 특징
- 웹 기반 사용 환경
- JSP, HTML, JAVA 사용
- MVC 모델 사용 (Model, Controller 통합)

### 구현된 파일 목록
![구현된파일목록](https://github.com/course-registeration/.github/assets/75843997/1821a2ee-d034-42d8-abfa-bb53ae925cff)

### 알고리즘 및 구현 기술
![알고리즘1](https://github.com/course-registeration/.github/assets/75843997/2280d6af-b209-4704-9f84-e1168951d465)
![알고리즘2](https://github.com/course-registeration/.github/assets/75843997/fa7495cd-a1c7-4a4a-a97f-4597809b277c)
![알고리즘3](https://github.com/course-registeration/.github/assets/75843997/7f321600-81ed-4026-b0ab-3c2bf146fa66)
![알고리즘4](https://github.com/course-registeration/.github/assets/75843997/732e3d4b-3ecf-4c49-a0d2-e66e83b8f40a)
![알고리즘5](https://github.com/course-registeration/.github/assets/75843997/e2882614-14e4-4ea4-9f8b-710aedae832a)

### 데모 영상
- [학생용 수강신청 데모영상](https://drive.google.com/file/d/1pTCcqbFogLCJCvYsUFT6M29v5oI4Ecaj/view?usp=sharing)
- [교수용 수강신청 데모영상](https://drive.google.com/file/d/1l3ugTXUSf6nYXvTNft546tKA6cONVIpU/view?usp=sharing
)

