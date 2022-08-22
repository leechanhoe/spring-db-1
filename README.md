![](https://velog.velcdn.com/images/dodo4723/post/80b10d83-42bc-433a-889c-440d2df15b21/image.png)

김영한 개발자님의 스프링 DB 1편 강의를 수강 일주일 후 까먹을때즈음 복습하며 정리한 내용입니다.

[1. JDBC 이해](https://github.com/leechanhoe/TIL/blob/main/Spring/Spring_db_1/1_understanding_of_JDBC.md)

[2. 커넥션풀과 데이터소스 이해](https://github.com/leechanhoe/TIL/blob/main/Spring/Spring_db_1/2_%EC%BB%A4%EB%84%A5%EC%85%98%ED%92%80%EA%B3%BC_%EB%8D%B0%EC%9D%B4%ED%84%B0%EC%86%8C%EC%8A%A4_%EC%9D%B4%ED%95%B4.md)

[3. 트랜잭션 이해](https://github.com/leechanhoe/TIL/blob/main/Spring/Spring_db_1/3_%ED%8A%B8%EB%9E%9C%EC%9E%AD%EC%85%98_%EC%9D%B4%ED%95%B4.md)

[4. 스프링과 문제 해결 - 트랜잭션](https://github.com/leechanhoe/TIL/blob/main/Spring/Spring_db_1/4_%EC%8A%A4%ED%94%84%EB%A7%81%EA%B3%BC_%EB%AC%B8%EC%A0%9C%ED%95%B4%EA%B2%B0_%ED%8A%B8%EB%9E%9C%EC%9E%AD%EC%85%98.md)

[5. 자바 예외 이해](https://github.com/leechanhoe/TIL/blob/main/Spring/Spring_db_1/5_%EC%9E%90%EB%B0%94_%EC%98%88%EC%99%B8%EC%B2%98%EB%A6%AC.md)

[6. 스프링과 문제 해결 - 예외처리, 반복](https://github.com/leechanhoe/TIL/blob/main/Spring/Spring_db_1/6_%EC%8A%A4%ED%94%84%EB%A7%81%EA%B3%BC_%EB%AC%B8%EC%A0%9C%ED%95%B4%EA%B2%B0_%EC%98%88%EC%99%B8%EC%B2%98%EB%A6%AC_md)

<br>

## 느낀 점
여러 벡엔드 기술들 중에서도 내가 가장 관심있는 주제가 **데이터베이스**이다. 이전 로드맵인 스프링 핵심원리, MVC등등의 강의를 들으면서 데이터베이스를 다루는 강의까지 오는 것을 기대했었다. 그래서인지 더 재밌게 들었던 강의였다.

특히 데이터베이스 이론서적으로 읽어만 보거나 말로만 듣던 **트랜잭션**을 직접 다뤄보는 것이 흥미있었다. 역시 개발자는 직접 다뤄봐야 더 공부효율이 좋은 것 같다.

**예외 처리**에 대해서도 공부했다. 언체크 예외와 체크예외가 인상 깊었다. 이전까지 파이썬, C++, 자바, 자바스크립트 등등 예외처리에 관한 내용을 책으로 접해보긴 했지만, C#으로 모바일 게임을 만들때도 예외처리에 관한 부분은 거의 사용하지 않고.. 이 예외처리가 그렇게 중요한 부분인가? 에 대해서는 감을 잡지 못했다. 하지만 개발에 있어서 빠질 수 없는 부분인 것 같다.

**여러 언어들을 접하면서 느낀 점**도 있는데, 생각보다 거기서 거기인 느낌이다. 문법이 조금씩 다를 뿐, 대부분 어떤 큰 틀 안에서 벗어나지 않는 것 같다. 한 언어의 클래스를 다뤄봤으면 다른 언어의 클래스도 눈에 쏙쏙 들어오는 것 같이 자바 예외 처리에 대해 공부하면 다른 언어를 공부할 경우에도 큰 도움이 될것이다.