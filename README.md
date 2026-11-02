# 나의 첫 웹 서버 구축 프로젝트

## 1. 프로젝트 개요
- 도커(Docker)를 이용해 Nginx 웹 서버를 실행하고, 나만의 웹 페이지를 띄우는 프로젝트입니다.

## 2. 사용한 기술
- Docker, Nginx, HTML, Git/GitHub

## 3. 실행 방법
1. 이미지 빌드: `docker build -t my-web-server .`
2. 컨테이너 실행: `docker run -d -p 8081:80 --name my-site my-web-server`

## 4. 결과 확인
- 브라우저에서 `localhost:8081` 접속