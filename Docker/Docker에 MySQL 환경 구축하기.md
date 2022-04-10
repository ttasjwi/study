# Docker에 MySQL 환경 구축하기

---

## 1. 가상환경에서 MySQL을 사용하기 위해 Docker 설치

![dockerInstall](img/dockerInstall.jpg)

- Windows / MacOS
    - 도커 설치 : [Get Started with Docker](https://www.docker.com/get-started/) 
    - Windows WSL2 기반 도커 실행시 vmmem 메모리 소모량 이슈가 있다. 이 부분은 아래 링크를 참조하도록 하자.
        - 참조링크 : [WSL2 기반 docker 사용시 vmmem 프로세스 메모리 소모량 줄이기](https://meaownworld.tistory.com/160)
        - `Settings > General > Start Docker Desktop when you log in` 을 끄자.
- 설치 확인
  ```shell
  PS C:\Users\ttasjwi> docker --version
  Docker version 20.10.13, build a224086
  ```

---
