섹션3 - JPA 시작하기

JPA 순서
repository -> jpa -> jdbc api -> database

같은 트랜잭션 동일 데이터 보장. jpa가 캐싱했다가 결과값 돌려줌. db안감
member1 == member2 - true

버퍼라이팅 가능

지연로딩 - 실제사용할때 로딩
즉시로딩 - join sql로 한번에 조회

데이터베이스 방언

db마다 다른기능
페이징 : oracle - rownum, mysql - limit
문자열 자르기 함수 : sql 표준 substring, oracle - substr
가변문자 : myslq - varchar, oracle - varchar2

![image](https://github.com/user-attachments/assets/3a42ce20-660b-45cc-9d77-cc2f32851bd1)
![image](https://github.com/user-attachments/assets/a088b66b-57cc-44a5-bce7-14e1811d1ab8)
![image](https://github.com/user-attachments/assets/19c1d6f9-d206-4f15-a95f-b3f9af0acf27)
![image](https://github.com/user-attachments/assets/cea2ef14-d65b-4d0f-9157-24114ca0dec0)
![image](https://github.com/user-attachments/assets/aa96525e-46b7-4caa-9b7a-d969322fea96)


JPQL - 엔티티 객체 대상으로 쿼리 실행. DB 테이블 기반 실행이 아님. DB에 종속되지 않아야 하기 때문

