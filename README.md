# 기술면접 대비 CS 스터디 커리큘럼

## 운영 방식
- 매주 발표자 1명이 주제를 준비하고 발표 (10~15분)
- 나머지 멤버들은 면접관 역할로 질문 및 꼬리 질문
- 발표 → 질문 → 꼬리질문 → 피드백 순서
- 스터디 후 발표자는 보완 정리 → Markdown 문서 업로드

---

## 주차별 학습 계획

### 1주차: 운영체제 (OS)
- 프로세스 vs 스레드
- 컨텍스트 스위칭
- 메모리 구조 (Heap / Stack / Data / Code)
- CPU 스케줄링
- 동기화 (Semaphore, Mutex, Deadlock)

### 2주차: 네트워크 (Network)
- OSI 7계층
- TCP vs UDP
- HTTP vs HTTPS
- 3-way handshake / 4-way termination
- REST API 원리
- DNS 동작 과정

### 3주차: 데이터베이스 (Database)
- RDB vs NoSQL
- 트랜잭션과 ACID
- 인덱스 구조 (B-Tree, Hash)
- 정규화 vs 비정규화
- JOIN과 쿼리 최적화
- 동시성 제어 (락)

### 4주차: 자료구조 (DataStructure)
- 배열, 연결리스트
- 스택, 큐, 해시맵
- 시간/공간 복잡도
- 기초 문제 풀이

### 5주차: 알고리즘 (Algorithm)
- 정렬 알고리즘 (퀵, 머지, 힙)
- DFS / BFS
- 우선순위 큐, 힙
- 그래프 탐색 문제

### 6주차: 자바 (Interview/Java)
- JVM 구조
- Garbage Collection
- Java Collections (HashMap, ConcurrentHashMap)
- 오버로딩 vs 오버라이딩
- 예외 처리

### 7주차: 스프링 (Interview/Spring)
- IoC / DI / Bean Lifecycle
- AOP
- Spring Boot Auto Configuration
- JPA & 영속성 컨텍스트
- N+1 문제와 해결 방법

### 8주차: 종합 모의 면접 (Interview)
- 랜덤 주제 질문 & 답변
- 실제 면접처럼 진행
- Q&A 정리 후 리포지토리에 기록

---

## 기록 방식
- 주차별로 `docs/week01.md` 형식 문서화
- 디렉토리 구조는 다음과 같이 사용:

```
2025-DevCS-study
┣ 📂 OS
┣ 📂 Network
┣ 📂 Database
┣ 📂 DataStructure
┣ 📂 Algorithm
┣ 📂 SoftwareEngineering
┣ 📂 Interview
┣ 📂 Web
┣ 📂 Etc
┗ README.md
```


