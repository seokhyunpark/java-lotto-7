# java-lotto-precourse

## 기능 요구 사항
1. 사용자가 로또를 구매할 금액을 입력
   - 한 장당 1,000원
2. 구입 금액에 해당하는 만큼 로또 번호를 생성
   - 로또 번호의 숫자 범위는 1~45
   - 1개의 로또에는 중복되지 않은 숫자 6개
3. 사용자가 당첨 번호를 입력
4. 사용자가 보너스 번호를 입력
5. 사용자가 구매한 로또 번호와 당첨/보너스 번호를 비교
   - 1등: 6개 번호 일치 (2,000,000,000원)
   - 2등: 5개 번호 + 보너스 번호 일치 (30,000,000원)
   - 3등: 5개 번호 일치 (1,500,000원)
   - 4등: 4개 번호 일치 (50,000원)
   - 5등: 3개 번호 일치 (5,000원)
6. 통계 출력
   - 각 등수와 일치한 로또 개수
   - 총 수익률

## 구현할 기능 목록
### 로또 구입 금액 입력
- [x] 로또 구입 금액 안내 문구를 출력하는 기능
- [x] 로또 구입 금액을 입력받는 기능
- [x] 입력한 금액에 대한 유효성 검사
  - [x] 입력한 금액이 0 이상이 아닌 경우 예외 처리 기능
  - [x] 입력한 금액이 1,000원으로 나누어 떨어지지 않는 경우 예외 처리 기능
- [x] 예외 발생 시 다시 입력을 받는 기능

### 로또 번호 생성
- [x] 생성한 로또 번호 개수 안내 문구를 출력하는 기능
- [x] 중복이 없는 로또 번호 6개를 구입 금액에 해당하는 만큼 생성하는 기능
- [x] 생성한 로또 번호를 오름차순으로 정렬하는 기능
- [x] 생성한 로또 번호를 출력하는 기능

### 당첨 번호 입력
- [x] 당첨 번호 안내 문구를 출력하는 기능
- [x] 당첨 번호를 입력받는 기능
- [x] 입력한 당첨 번호를 `,`를 기준으로 구분하는 기능
- [x] 입력한 당첨 번호에 대한 유효성 검사
  - [x] 당첨 번호가 1~45 사이의 숫자가 아닌 경우 예외 처리 기능
- [x] 예외 발생 시 다시 입력을 받는 기능

### 보너스 번호 입력
- [x] 보너스 번호 안내 문구를 출력하는 기능
- [x] 보너스 번호를 입력받는 기능
- [x] 입력한 보너스 번호에 대한 유효성 검사
  - [x] 보너스 번호가 1~45 사이의 숫자가 아닌 경우 예외 처리 기능
  - [x] 보너스 번호가 당첨 번호와 중복되는 경우 예외 처리 기능
- [ ] 예외 발생 시 다시 입력을 받는 기능

### 당첨 통계
- [ ] 당첨 통계 안내 문구를 출력하는 기능
- [ ] 로또 결과를 계산하는 기능
- [ ] 로또 결과를 출력하는 기능
- [ ] 총 수익률을 계산하는 기능
- [ ] 총 수익률을 출력하는 기능
