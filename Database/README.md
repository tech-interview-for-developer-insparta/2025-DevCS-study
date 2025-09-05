# 데이터베이스 커리큘럼 로드맵

| 단계 | 주제 | 세부 내용 / 예시 | 비고 |
|------|------|------------------|------|
| **기초** | 데이터베이스 기본 | DBMS 개념, 스키마, 테이블, 레코드 | 필수 |
|  | 키(Key) | 기본키, 후보키, 대체키, 외래키 | 필수 |
|  | SQL 기초 | SELECT, INSERT, UPDATE, DELETE | 필수 |
|  | SQL JOIN | INNER, LEFT, RIGHT, FULL JOIN | 필수 |
|  | 정규화(Normalization) | 제1~제3정규형, BCNF | 필수 |
|  | 이상(Anomaly) | 삽입/갱신/삭제 이상 | 필수 |
| **중급** | 인덱스(Index) | B-Tree, B+Tree, 클러스터드/논클러스터드 인덱스 | 필수 |
|  | 트랜잭션(Transaction) | ACID 특성 | 필수 |
|  | 트랜잭션 격리 수준 | Read Uncommitted, Committed, Repeatable Read, Serializable | 필수 |
|  | 뷰(View) & 저장 프로시저 | View, Stored Procedure 개념과 활용 | 선택 |
|  | 동시성 제어 | Lock, Deadlock, MVCC | 필수 |
| **심화** | SQL 최적화 | 실행 계획, 인덱스 튜닝 | 필수 (실무) |
|  | NoSQL | Key-Value, Document, Column, Graph DB | 필수 (현대 시스템) |
|  | 분산 DB | Sharding, Replication, CAP 이론 | 선택 |
|  | Redis | In-memory DB, 캐싱 전략 | 선택 |
|  | NewSQL | 분산 + 트랜잭션 지원 DB (CockroachDB 등) | 선택 |
