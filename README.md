# pikolo_server

'pikolo.life' Server Settings

## 📌 목차
1. [개요](#-개요-)
2. [개발기간](#-개발기간-)
3. [멤버구성](#-멤버구성)
4. [기술스택](#-기술스택-)
5. [서비스 구성](#-서비스-구성)
6. [실행](#-실행)

## 🖥️ 개요
> 프로젝트 이름: pikolo_server
> 'pikolo.life' 애플리케이션의 서버 환경을 설정하는 프로젝트입니다.
> Docker Compose를 사용하여 Nginx, Spring Boot, Oracle 데이터베이스 환경을 구성합니다.

## 🕰️ 개발기간
> (개발 기간을 여기에 작성해주세요)

## 🧑‍🤝‍🧑 멤버구성
> ### 강태일(tgncosist2)
>
> Server 개발
>
> ### 심규민(gyumin6349)
>
> Server 개발

## ⚙️ 기술스택
> ### Server
>
> ![Docker](https://img.shields.io/badge/docker-%232496ED.svg?style=for-the-badge&logo=docker&logoColor=white)
> ![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)
>
> ### Back End
>
> ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
>
> ### DataBase
>
> ![Oracle DataBase 19c](https://img.shields.io/badge/Oracle%20DataBase%2019c-F80000?style=for-the-badge&logo=oracle&logoColor=white)
>
> ### Environment
>
> #### Version control ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

## 🔧 서비스 구성
> `docker-compose.yml` 파일은 다음 세 가지 서비스를 정의합니다.
> - **my-nginx**: 웹 서버 및 리버스 프록시 역할을 합니다.
> - **my-spring**: Spring Boot 애플리케이션을 실행합니다.
> - **my-oracle**: Oracle 데이터베이스를 실행합니다.

## ▶️ 실행
> ### Docker Compose 실행
> ```bash
> docker-compose up -d
> ```
