1. 관계형 데이터베이스(RDBMS)와 비관계형 데이터베이스(NoSQL)의 장단점 비교

- 관계형 데이터베이스는 데이터들의 관계를 설정하여 조회할때 속도를 높일 수 있다.
- 비관계형 데이터베이스는 key-value형태로 대규모시스템에 적합하다.

2. 트랜잭션(transaction)이란 무엇인가요?

- 트랜잭션이란 작업의 한 단위로 sql의 시작부터 커밋이 될때까지의 작업을 말한다.

3. MySQL에서 조인(join)의 역할은 무엇인가요? 다양한 join의 방식에 대해 설명해주세요.

- 조인이란 서로다른 테이블에서 관계가 있는 컬럼끼리 묶어 조회하는 연산을 말한다.
- inner join : 서로 동일한 키끼리 조인함
- outer join : 반대쪽에 null이있는경우에도 조회가 된다.
- corss join : 키 구분없이 서로 교차하여 조회된다.

4. MySQL에서 인덱스(index)란 무엇인가요?

- 인덱스란 특정 저장소에 미리 정렬된 데이터를 저장해 두고 해당 데이터를 사용해서 조회 시간을 빠르게 하는것으 말한다.
- 때문에 index는 조회할때 자주 검색되는 컬럼으로 지정하는것이 좋다.
