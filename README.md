# 과제 - 프로젝트 관리 시스템 만들기

## 저장소 및 프로젝트 폴더 준비하기

- 1) 저장소로 사용할 폴더 생성
  - c:\Users\bitcamp\bitcamp-java-project
- 2) 폴더를 git 저장소로 만든다.
- 3) github.com에 "bitcamp-java-project" 저장소를 생성한다.
- 4) 로컬 저장소를 원격 저장소에 연결하기
- 5) gradle 을 이용하여 저장소를 프로젝트 폴더로 만든다.
- 6) .gitignore 파일 준비하기
  - bitcamp-workspace에서 사용하는 파일을 그대로 복사한다.
- 7) 로컬 저장소에 백업 한 후 원격 저장소에 업로드

## 구현 요구사항

- 한 명의 회원 정보를 콘솔로 출력한다.
- 한 개의 프로젝트 정보를 콘솔로 출력한다.
- 한 개의 작업 정보를 콜솔로 출력한다.

## 실습


### 1단계 - 한 명의 회원 정보를 출력한다

Mini-PMS를 이용하는 회원 정보를 출력한다. 일단 한 명의 정보만 출력한다.

```console
[회원]
번호: 101
이름: 홍길동
이메일: hong@test.com
암호: 1111
사진: hong.png
전화: 1111-2222
가입일: 2020-01-01
```

[작업 파일]

- com.eomcs.pms.App  클래스 변경
- src/test/java/com/eomcs/pms/AppTest.java 삭제
  - 당장 JUnit 관련 코딩은 하지 않기 때문에 제거한다.

### 2단계 - 한 개의 프로젝트 정보를 출력한다

회원이 진행할 프로젝트 정보를 출력한다. 일단 한 개의 프로젝트 정보만 출력한다.

```console
[프로젝트]
번호: 1201
프로젝트명: 미니 프로젝트 관리 시스템 개발
내용: 소규모 팀을 위한 프로젝트 관리 시스템을 개발한다.
시작일: 2020-01-01
종료일: 2020-12-31
만든이: 홍길동
팀원: 홍길동,김구,유관순,안중근,윤봉길
```

[작업 파일]

- com.eomcs.pms.App2  클래스 추가
  
### 3단계 - 한 개의 작업 정보를 출력한다

프로젝트에서 수행할 작업 정보를 출력한다. 일단 한 개의 작업 정보만 출력한다.

```console
[작업]
프로젝트: 미니 프로젝트 관리 시스템 개발
번호: 1
내용: 요구사항 수집
완료일: 2020-01-20
상태: 진행중
담당자: 홍길동
```

[작업 파일]

- com.eomcs.pms.App3  클래스 추가


[실습 결과]

- src/main/java/com/eomcs/pms/App.java 변경
- src/main/java/com/eomcs/pms/App2.java 추가
- src/main/java/com/eomcs/pms/App3.java 추가
- src/test/java/com/eomcs/pms/AppTest.java 삭제