## Spring Batch를 이용한 쇼핑몰 구현

#### Spring Batch: 대량의 데이터 처리를 위한 경량화된 프레임워크
- Job(일)구동 ➡ Step(일의 항목, 단계) 실행 ➡ Tasklet(Step 안에서 단일 테스크로 수행, 진행 내용) 실행

#### 구성
- base(테스트 데이터 생성), cart(장바구니), cash(결제), member(회원), order(주문), product(상품)
- Spring boot에서 제공하는 Spring Data JPA를 사용하여 쿼리를 자동으로 생성하여 사용
    * join, save, findAllByIdLessThan 등등

![image](https://github.com/ohyo555/batch_ex_24_04/assets/153146836/2dafc30d-f7ac-4478-81ff-cb213e162416)
![image](https://github.com/ohyo555/batch_ex_24_04/assets/153146836/a90aacbd-c35f-4ef7-a99f-e33babf57670)

- Tistory <br/>
  [Spring Batch_쇼핑몰 구현](https://ohyohyo.tistory.com/search/batch)
