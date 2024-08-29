JPA 순서
repository -> jpa -> jdbc api -> database

같은 트랜잭션 동일 데이터 보장. jpa가 캐싱했다가 결과값 돌려줌. db안감
member1 == member2 - true

버퍼라이팅 가능
