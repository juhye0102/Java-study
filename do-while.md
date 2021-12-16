### do-while문

- while문의 경우 조건이 만족하지 않는다면 한 번도 반복하지 않을 수 있음. do while문의 경우는 무조건 한 번은 실행되는 반복문임.

```java
do{
		실행문
}while(조건문);
```

- do-while

```java
import java.util.Scanner;

public class DoWhileExam {
	
	public static void main(String[] args) {
			int value = 0;

			Scanner scan = new Scanner(System.in):

			do{
					value = scan.nextInt();
					System.out.println("입력받은 수 : " + value);
			}while(value != 10);

			System.out.println("반복문 종료");
	}
}
```