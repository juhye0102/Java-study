- if 조건문

  ### 조건식의 연산 결과에 따라 블록 내부 문장의 실행 여부를 결정할 수 있음.

  - if문

    - 조건식이 true일 경우에만 실행문이 실행됨.
    - if(조건식) 다음의 { }를 생략할 수 있음. 생략할 경우 if문에 포함되는 실행문은 단 한 줄만 포함됨.

    ```java
    if(조건식) {
    		실행문;
    		실행문;
    }
    ```

  - if - else문

    - 조건식이 true일 경우 if 블록의 실행문이 실행되고, false일 경우 else 블록의 실행문이 실행됨.

    ```java
    if(조건식) {
    		실행문;
    		실행문;
    }else{
    		실행문;
    }
    ```

  - if - else if - else문

    - 처음 if문의 조건식의 조건문이 true일 경우 처음 if문의 블록이 실행되고, false일 경우 다음 조건식의 결과에 따라 실행 블록이 달라짐.
    - else if문의 수는 제한이 없음. 그러나 너무 많은 else if문은 실행 속도를 느리게 함.
    - 마지막 else 블록은 생략 되어도 상관 없음.

    ```java
    if(조건식){
    		실행문;
    		실행문;
    }else if(조건식){
    		실행문;
    }else{
    		실행문;
    }
    ```