# How to set with Spring 

1. src > main > resources > application.properties 파일 열기

2. 아래코드 붙혀넣기

          spring.h2.console.enabled=true
          spring.datasource.url=jdbc:h2:mem:springcoredb
          
3. 프로그램 돌리고 아래 URL로 접속합니다. 

     http://localhost:8080/h2-console 

4. 그러면 아래 이미지처럼 나올 것 입니다. 그리고 Connect 버튼을 클릭해주세요.
![image](https://user-images.githubusercontent.com/90609214/150941450-7078a594-fa44-4e43-85a0-7ca996bcdfa8.png)

5, 아래이미지처럼 나오면 성공입니다. 
![image](https://user-images.githubusercontent.com/90609214/150942390-cc90e5cd-82d7-434b-b931-9042a3737ae9.png)

(위에 이미지처럼 안나오면 JDBC URL 확인해주세요)
