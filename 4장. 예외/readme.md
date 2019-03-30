# 4장 예외
## 4.1 사라진 SQLException
4.1.1 [초난감 예외처리](https://github.com/devSoyoung/2019-KHU-spring-study/edit/master/4%EC%9E%A5.%20%EC%98%88%EC%99%B8/readme.md)<br>
      예외 블랙홀<br>
      무의미하고 무책임한 throws<br>
4.1.2 예외의 종류와 특징<br>
4.1.3 예외처리 방법<br>
      예외 복구<br>
      예외처리 회피<br>
      예외 전환<br>
4.1.4 예외처리 전략<br>
      런타임 예외의 보편화<br>
      add() 메소드의 예외처리<br>
      애플리케이션 예외<br>
4.1.5 SQLException은 어떻게 됐나?<br>

## 4.2 예외 전환
4.2.1 JDBC의 한계<br>
      비표준 SQL<br>
      호환성 없는 SQLException의 DB 에러정보<br>
4.2.2 DB 에러 코드 매핑을 통한 전환<br>
4.2.3 DAO 인터페이스와 DataAccessException 계층구조<br>
      DAO 인터페이스와 구현의 분리<br>
      데이터 액세스 예외 추상화와 DataAccessException 계층구조<br>
4.2.4 기술에 독립적인 UserDao 만들기<br>
      인터페이스 적용<br>
      테스트 보완<br>
      DataAccessException 활용 시 주의사항<br>

## 4.3 정리 
