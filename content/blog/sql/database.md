---
title: '데이터베이스(Database,DB)'
excerpt: 데이터베이스란?
date: 2020-11-27
category: 'SQL'
draft: false
---


## 데이터베이스(DATABASE)란?
   
데이터베이스란 일반적으로 컴퓨터 시스템에 전자 방식으로 저장된 구조화된 정보   
또는 데이터의 체계적인 집합을 의미한다.   


> 여러 사람이 공유하고 사용할 목적으로 통합 관리되는 정보의 집합이다.    
> 파일을 조직적으로 통합하여 자료 항목의 중복을 없애고  
> 자료를 구조화하여 기억시켜 놓은 자료의 집합체라고 할 수 있다.  
> 출처:위키백과




### 데이터베이스의 장단점


**데이터베이스 장점**


데이터 중복 최소화  
데이터 공유  
일관성, 무결성, 보안성 유지  
최신의 데이터 유지  
데이터의 표준화 가능  
데이터의 논리적, 물리적 독립성  
용이한 데이터 접근  
데이터 저장 공간 절약  






**데이터베이스 단점**


데이터베이스 전문가 필요  
많은 비용 부담  
데이터 백업과 복구가 어려움  
시스템의 복잡함  
대용량 디스크로 엑세스가 집중되면 과부하 발생  






### SQL(Structured QUery Language)
SQL(Structured Query Language)은 데이터베이스에서 데이터를   
정의, 조작, 제어하기 위해 사용하는 언어입니다.   
따라서 SQL 구문도 위의 목적에 맞게 크게 세 가지로 구분할 수 있습니다.   


- DDL(Data Definition Language)

- DML(Data Manipulation Language)

- DCL(Data Control Language)






### 데이터 정의 언어(DDL)

데이터베이스나 테이블등을 생성, 삭제하거나 그 구조를 변경하기 위한 명령어   

CREATE : 정의  
ALTER : 수정  
DROP : 삭제  






### 데이터 조작 언어(DML)

데이터베이스에 저장된 데이터를 처리하거나 조회, 검색하기 위한 명령어   

INSERT : 추가   
UPDATE : 수정  
DELETE : 삭제  
SELECT : 조회  






### 데이터 제어 언어(DCL)

데이터베이스에 저장된 데이터를 관리하기 위하여   
데이터의 보안성 및 무결성 등을 제어하기 위한 명령어   

- GRANT : 사용자에게 권한 부여   
- REVOKE : 권한 취소   
- COMMIT : 작업 결과 반영  
- ROLLBACK : 복구  






### DBMS

DataBase Management System  
데이터베이스를 사용하기 위해서는 **데이터베이스 관리 시스템**이 필요하다.    
대표적으로 Oracle, MYSQL, MS-SQL 등이 있다.   
