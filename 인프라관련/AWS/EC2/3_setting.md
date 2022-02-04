# How to set up

### 스프링용
1. 한줄씩 명령하기 EC2 접속했을 때 

            sudo apt-get update

            sudo apt-get install openjdk-8-jdk

            java -version

2. 포트 번호를 입력하지 않아도 자동으로 접속되기 위해, 80포트로 오는 요청을 8000 포트로  전달하게 하는 포트포워딩(port forwarding) 을 사용
   
            sudo iptables -t nat -A PREROUTING -i eth0 -p tcp --dport 80 -j REDIRECT --to-port 8080

(플라스크용 추가예정) 
