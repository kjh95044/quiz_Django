## 프로젝트 생성 (Window 10)

### 1) cmd
1. 원하는 폴더에서 cmd 실행
2. ```python -m venv venv``` <- "venv" 라는 이름으로 가상환경 생성
3. ```venv/bin/activate``` <- 가상환경 활성화
4. ```pip install django djangorestframework``` <- 장고 rest 프레임워크 패키지 설치
5. ```django-admin startproject myapi .``` <- "myapi" 라는 이름의 프로젝트를 현재 폴더에 생성
6. ```python manage.py startapp quiz``` <- "quiz" 이라는 이름의 앱 생성

### 2) myapi -> settings.py 수정

1. ```ALLOWED_HOSTS = ['*']```
2. ```TIME_ZONE = 'Asia/Seoul'```
3. INSTALLED_APPS에 ```'quiz', 'rest_framework'``` 추가

## 나머지 코드
- 나머지 코드는 commit 메시지로 작성 진행 하도록 하겠습니다.

## 비고
- 인프런 강의중 권태뿡님의 "플러터-장고-퀴즈앱-서버-풀스택"을 참고 했습니다.

참고 링크 : [강의 링크](https://www.inflearn.com/course/%ED%94%8C%EB%9F%AC%ED%84%B0-%EC%9E%A5%EA%B3%A0-%ED%80%B4%EC%A6%88%EC%95%B1-%EC%84%9C%EB%B2%84-%ED%92%80%EC%8A%A4%ED%83%9D/dashboard)﻿
