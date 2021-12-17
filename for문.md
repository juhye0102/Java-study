### for문

- for 반복문은 변수 초기화, 조건식, 증감식이 한 줄에 모두 있음.

  1. 초기화식은 최초 한 번만 수행함.
  2. 조건식을 수행해서 수행 결과가 false라면 for 반복문을 빠져 나감.
  3. 수행 결과가 true라면 실행문을 수행함.
  4. 증감식을 수행함.
  5. 2번부터 4번까지 반복적으로 수행함.

  ```java
  for(초기화식; 조건식; 증감식){
  		실행문;
  		실행문;
  }
  ```

- for문을 이용하여 1부터 100까지의 합을 구하는 프로그램

```java
int total = 0;

for(int i = 1; i <= 100; i++){
		total = total + i;
}

System.out.println(total);
```

- for문을 이용하여 1부터 100까지의 짝수의 합을 구하는 프로그램

```java
public class ForExam {
		
		public static void main(String[] args) {
				int total = 0;
				for(int i = 1; i < 101; i++){
						if (i % 2 != 0) {
								continue;
						}
						total = total + i;
				}
				System.out.println(total);
		}
}
```