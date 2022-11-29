## 🚀 프로젝트 소개
> 이번 주차는 치킨집을 구현한다.
>
<br>

### 입출력 요구 사항

<details>
    <summary>실행 결과 예시</summary>
    <div markdown="1">

```

```

<br>
</div>
</details>

- [ ] `InputView` : 유저가 처음에 주문등록, 결제하기, 프로그램 종료 중 하나를 선택한다.

### 주문 등록
- [ ] `InputView` : 테이블 번호 입력받기
  - [ ] `Exception` : 테이블 번호가 1~8 범위를 벗어나면 오류 발생
- [ ] `InputView` : 유저로부터 메뉴 번호를 입력받기
    - [ ] `Exception` : 메뉴에 있지 않은 번호를 고르면 오류 발생
- [ ] `InputView` : 유저로부터 메뉴의 수량을 입력 받기
    - [ ] `Exception` : 99를 초과하는 수량 입력시 오류 발생

### 결제하기
- [ ] `InputView` : 테이블 번호 입력받기
    - [ ] `Exception` : 주문하지 않은 테이블 번호 선택시 오류 발생
- [ ] `OutputView` : 주문 내역 확인하기
- [ ] `InputView` : 결제 방식 입력하기
  - [ ] `InputView` : 헌금, 카드가 아닐 경우 예외 발생
- [ ] 치킨 구매에 따른 할인 적용하기
- [ ] 현금 구매에 따른 할인 적용하기
- [ ] `OutputView` : 최종 결제 금액을 확인하기