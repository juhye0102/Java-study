Arithmetic Operator

산술 연산자

- 부호(+,-), 증감(++,—), +,-,*,/,%

  - 연산식 ** x = y + z;**
    - y와 z를 더한 값을 x에 대입한다는 것을 의미
    - =과 + 는 연산자 = 은 대입연산자 이고, + 산술연산자임
    - y와 z 는 피연산자임.
    - x = y+ z 는 연산식이다.
  - 부호를 결정하는 부호 연산자
  - 산술 연산을 할 수 있는 산술 연산자
  - 1씩 증가하거나 감소 시키는 증감연산자
  - 피 연산자가 1개인 연산자는 단항 연산자
    - 부호 연산자와, 증감연산자는 단항 연산자임.

  ```java
  //부호 연산자 
      int i1 = -5;
      int i2 = +i1;
      int i3 = -i1;
  
      //증감 연산자 
      int i4 = ++i3;
      int i5 = i3++;
      int i6 = --i3;
      int i7 = i3--;
  ```

  - 피연산자 하나로 연산할 수 없는 연산자 이항 연산자

  ```java
  int i = 5;
  int j = 2;
  ```

  - 2개의 변수를 이용한 산술 연산

  ```java
  		System.out.println(i +  j);
      System.out.println(i -  j);
      System.out.println(i *  j);
      System.out.println(i /  j);  
      System.out.println(i %  j);
  ```