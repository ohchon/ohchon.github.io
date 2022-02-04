# RDS 포트 열어주기

1. springboot-database 클릭
![image](https://user-images.githubusercontent.com/90609214/150950212-004b47aa-4cbf-4938-ab4b-eabf2a8294a4.png)

2. 연결 & 보안 > 보안 > VPC 보안 그룹 의 springboot-db-security 클릭
![image](https://user-images.githubusercontent.com/90609214/150950303-075ed850-d0ec-4048-9d2d-cf44600eac52.png)

3. 보안 그룹 ID 클릭
![image](https://user-images.githubusercontent.com/90609214/150950366-a2d38c1c-7b17-4fd8-a79c-e1d2d121d982.png)

4. 인바운드 규칙 편집 클릭
![image](https://user-images.githubusercontent.com/90609214/150950414-b1fab522-e383-446b-897b-6f31a5496fb5.png)

5. 소스 > 위치 무관 클릭해서 0.0.0.0/0, ::/0 생성 확인 후 "규칙 저장" 클릭
![image](https://user-images.githubusercontent.com/90609214/150950471-b22826b6-7f31-4b29-a805-e762822b47f8.png)



