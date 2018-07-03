# docker_compose_mysql

## Install
* mysql dump 실행 ( local 계정 정보 셋팅은 코드에서 잘하시면 됨! )
 - 혹시 mysql 셋팅 귀찮으신 분은 아래를 참조해 docker-compose 를 이용하세요 :)
 - 단 docker-compose 실행시 기존 local 에서 사용하는 mysql 은 꺼주세요 (같은 3306 포트를 사용중이라.. )
```shell
$ cd {project_home_folder}
$ docker-compose up
```