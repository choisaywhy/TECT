# :seedling:TECT

### 신은지, 양석진, 최세화

> 충북대학교 소프트웨어학과 2021년도 졸업작품 프로젝트 TECT의 repo입니다.

## Content

> - [0. ProjectRoute](#project-route)
> - [1. (Mac) Project Setup](#mac-project-setup)
> - [2. (Windows) Project Setup](#windows-project-setup)

## project route
### 1. 프로젝트 경로

> 아래 경로를 참고하여 환경 세팅을 해주세요. <br>

        + TECT  <br>
        | \ + tect  <br>
        |   | \ + account <br>
        |   |   + tectapp <br>
        |   |   + TectProject <br>
        | + manage.py <br>
        | + requirements.txt <br>
        + README.md <>
        + .gitignore <br>

## mac project setup

### 1-1. 환경 세팅

- git clone

  ```
  $ git clone https://github.com/SchoolPizza/TECT
  $ cd TECT
  ```

- 가상환경 생성 및 활성화

  ```
  $ python3 -m venv bdcv
  $ source bdcv/bin/activate
  (bdcv) $
  ```

- 필요 패키지 설치

  ```
  (bdcv) $ cd tect
  (bdcv) $ pip3 install -r requirements.txt
  ```

### 1-2. Backend : Django 세팅

- Django Setup

  ```
  (bdcv) $ python3 manage.py makemigrations
  (bdcv) $ python3 manage.py migrate
  ```

- Django Admin

```
(bdcv) $ python3 manage.py createsuperuser
```

- Runserver

```
(bdcv) $ python3 manage.py runserver
```

> runserver 이후, url 경로에 **http://127.0.0.1:8000/** 를 입력하여 웹 서비스를 이용할 수 있습니다. <br>

## windows project setup

### 2-1. 환경 세팅

- git clone

  ```
  $ git clone https://github.com/SchoolPizza/TECT
  $ cd TECT
  ```

- 가상환경 생성 및 활성화

  ```
  $ python -m venv venv
  $ source venv/Scripts
  $ activate
  (venv) $
  ```

- 필요 패키지 설치

  ```
  (venv) $ cd tect
  (venv) $ pip install -r requirements.txt
  ```

### 1-2. Backend : Django 세팅

- Django Setup

  ```
  (venv) $ python manage.py makemigrations
  (venv) $ python manage.py migrate
  ```

- Django Admin

```
(venv) $ python manage.py createsuperuser
```

- Runserver

```
(venv) $ python manage.py runserver
```

> runserver 이후, url 경로에 **http://127.0.0.1:8000/** 를 입력하여 웹 서비스를 이용할 수 있습니다. <br>

