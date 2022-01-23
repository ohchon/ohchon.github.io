# How to release

## 스프링

* JAR파일 빌드해서 올려서 돌릴려면 (종료할 때 단축키 따로 있는데 까먹음..)

            java -jar JAR파일명.jar

* 원격 접속을 종료하더라도 계속 돌아가게 할려면

            nohup java -jar JAR파일명.jar &


* nohup명령으로 돌아가는 것을 멈출려면 (한줄씩)

   1. 돌아가는 서버프로세스 아이디(PID) 찾기 

            ps -ef | grep java
            
   2. 위에명령어로 끄기
   
            kill -9 [pid값]
