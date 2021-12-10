Comparing Operator

- ==, !=, <, >, <=, >=

  - 비교 연산자의 결과는 boolean임.

  ```java
  		int i = 10;
  		int j = 10;
  
  		System.out.println(i == j)
  		System.out.println(i == j) 
      System.out.println(i != j);
      System.out.println(i < j);
      System.out.println(i <= j);
      System.out.println(i > j);
      System.out.println(i >= j);
  ```

  - 단순 대입 연산자
    - i = 10
    - 오른쪽에 있는 피연산자의 값을 왼쪽 피연산자의 변수에 저장
  - 복합 대입 연산자
    - 정해진 연산을 수행한 후에 결과를 대입

  ```java
  		i += 10; 
  		
  		System.out.println(i);
  		System.out.println(i -= 5);
  		System.out.println(i);
  ```