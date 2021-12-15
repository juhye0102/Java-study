- 반복문

  반복문은 실행문을 반복적으로 실행해야 할 때 사용함.

  반복문의 종류는 while문, do-while문, for문이 있음.

- while문

  - 조건문의 실행 결과가 true일 동안 반복해서 실행함.

  ```java
  while(조건문) {
  		실행문;
  }
  ```

  - 10번 반복하면서 0부터 9까지 출력하는 반복문

  ```java
  int i = 0;
  // while에서 사용할 변수 선언
  
  while(i < 10){
  		System.out.println(i);
  		i++;
  		// 조건문을 원하는 만큼만 반복하고 빠져나가기 위함.
  }
  ```

  - 1부터 100까지의 합을 출력하는 while문

  ```java
  public class WhileExam2 {
  		public static void main(string[] args) {
  				int total = 0;
  				// i의 값을 누적할 변수를 선언
  				int i = 1;
  				while(i <= 100){
  						total = total + i;
  						i++;
  				}
  		}
  }
  ```