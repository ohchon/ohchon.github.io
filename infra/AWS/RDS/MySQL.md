1. AWS에서 로그인 하고 RDS 검색합니다. 
![image](https://user-images.githubusercontent.com/90609214/150947650-5601c13c-5c33-4cc9-aac5-e0d8a2be040c.png)

2. "데이터베이스 생성"을 클릭합니다
![image](https://user-images.githubusercontent.com/90609214/150947714-f74ad066-bae2-403c-aa40-16cd52978b18.png)

3. "표준생성" 과 "MySQL"을 클릭합니다.
 ![image](https://user-images.githubusercontent.com/90609214/150947917-2a5b5d95-6e50-40a2-aed5-94e188fd96c5.png)

4. "프리 티어"를 선택합니다.(기본은 프로덕션인듯 합니다) 
![image](https://user-images.githubusercontent.com/90609214/150948256-4132f5c1-9233-454b-bf5e-43e06af7f4cb.png)

5. 다음과 같이 입력합니다.
    - DB 인스턴스 식별자에 "springboot-database" 라고 입력합니다. (원하는 이름으로 바꾸셔도 돼요!)
    - 마스터 사용자 이름과 암호에 만들고 싶은 계정의 아이디, 비밀번호를 입력합니다. DB 접속용으로 사용해야 하니 꼭 기억해주세요!
![image](https://user-images.githubusercontent.com/90609214/150948464-faa8349f-429d-4fa0-823d-d8b2671cfe94.png)

6. DB 인스턴스 크기와 스토리지는 설정 그대로 두고 넘어갑니다.
![image](https://user-images.githubusercontent.com/90609214/150948695-2a156956-e9f5-4b26-a1aa-4244f5b7493a.png)

7. [중요] 연걸 > 추가 연결 구성 탭을 클릭합니다.
![image](https://user-images.githubusercontent.com/90609214/150948794-bbf386de-6883-4d55-8f75-7ab4a0b03da5.png)

8. 다음과 같이 설정합니다.
    - 퍼블릭 액세스 기능: "예" 선택

        → 이 설정이 되어있어야 우리 컴퓨터에서 AWS RDS 의 MySQL과 연결이 가능합니다. 꼭 퍼블릭 액세스 설정을 확인해주세요!

    - VPC 보안 그룹: "새로 생성" 선택
    - 새 VPC 보안 그룹 이름: springboot-db-security
    - 가용 영역: 옵션 중 아무거나 선택하셔도 괜찮아요.

![image](https://user-images.githubusercontent.com/90609214/150948976-2035f8bf-e86c-4a51-9efe-0ec8bf3b274e.png)

9. 추가 구성 > 초기 데이터베이스 이름을 입력한다.
![image](https://user-images.githubusercontent.com/90609214/150949193-c9996d89-8945-4df7-974c-f214033038da.png)

10. 데이터베이스 생성 클릭
![image](https://user-images.githubusercontent.com/90609214/150949333-effc0c57-0949-4195-95b8-6627b03158ed.png)
