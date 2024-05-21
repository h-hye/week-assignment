# 4주차 데이터베이스 이론 맛보기

## 데이터베이스

- 📕 [기본] 데이터베이스가 무엇인지 알아보기

**데이터베이스란?** 
데이터의 저장소이다.

**DBMS(Database Management System, 
데이터베이스 관리 시스템)이란?**
데이터베이스를 운영하고 관리하는 소프트웨어이다.
계층형, 망형, 관계형 DBMS 중 대부분의 DBMS가 테이블로 구성된 
관계형 DBMS(RDMBS)형태로 사용된다.

**SQL(Structured Query Language)이란?**
구조화된 질의언어라는 뜻으로 관계형 데이터베이스에서 사용되는 언어이다.

### 데이터베이스의 구성요소

- 개체(Entity)
  - 데이터로 표현하고자 하는 현실 세계의 대상체
- 속성(Attribute)
  - 열(column)
- 관계(Relationship)
  - 개체 간의 연관 관계
---
- 📕 [기본] 데이터베이스 자료형 알아보기

char 
: 고정길이 문자열이다.
뒤에 남은 자리가 있으면 공백으로 채운다.

**varchar**
: 가변길이 문자열이다.

int
: 4바이트까지 저장 가능하다.

**bigint**
: 큰 int
8바이트까지 저장 가능하다.

number
: 22바이트까지 가변길이 숫자 저장 가능하다.
38자리까지 표현할 수 있다.

---
- 📕 [기본] 관계형 데이터베이스가 무엇인지 알아보기

**관계형 데이터베이스(RDB)란?**
: 데이터가 하나 이상의 열과 행의 테이블에 저장되어 있어 사전 정의된 관계로 데이터를 구성하는 정보 모음이다.
테이블, 행, 열의 정보를 구조화하는 방식이다.

**장점**
: 직관적인 데이터 표현 방법을 제공하고 관련 데이터 포인트에
쉽게 액세스할 수 있다는 점이다.

- 유연성
- ACID 규정 준수
- 사용 편의성
- 공동 작업
- 내장된 보안 기능
- 정규화

---
- 📕 [기본] 비관계형 데이터베이스가 무엇인지 알아보기

**비관계형 데이터베이스란?**
: 테이블 형식 스키마를 사용하지 않는 데이터베이스이다.
: 비관계형 데이터베이스는 저장되는 데이터 형식의 특정 요구 사항에 맞게 최적화된 스토리지 모델을 사용한다.
: 예를 들어, 데이터는 단순 키/값 쌍, JSON 문서 또는 모서리와 꼭짓점으로 이루어진 그래프로 저장될 수 있다.

---
- 📕 [기본] 관계형 vs 비관계형 데이터베이스

**데이터모델**
- 관계형 데이터베이스는 `테이블 형식` 비관계형 데이터베이스는 `문서`, `key-value`, `그래프` 등
다양한 모델 사용한다.

**스키마**
- 관계형 데이터베이스는 `고정된` 스키마, 비관계형 데이터베이스는 `유연한` 스키마이다.

**확장성**
- 관계형 데이터베이스는 수평 확장이 어렵다.
- 비관계형 데이터베이스는 수평 확장이 용이하다.
---