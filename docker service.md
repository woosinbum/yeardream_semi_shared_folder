1. 컨테이너를 다 지우고도 포트가 할당됐다면 service 재시작  
https://stackoverflow.com/questions/46176584/docker-bind-for-0-0-0-04000-failed-port-is-already-allocated

2. docker 그룹 권한을 사용자에게 부여  
sudo usermod -a -G docker $USER


출처: https://jusunglee.tistory.com/entry/유저그룹-USER-GROUP [IT 정글]
