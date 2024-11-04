# 기능 구현 목록

## 입출력

### 입력

- 로또 구입 금액 입력
- 로또 당첨 번호 6개 (예상 번호) 입력
- 보너스 번호 1개 입력

### 출력

- 금액에 따른 로또 구입 갯수 출력
- 로또 갯수에 따른 랜덤 로또 번호 출력
- 랜덤 보너스 번호 출력
- 당첨 통계 출력
- 총 수익률 출력

## 기능 구현

### 검증

- 로또 구입 금액 검증
- 당첨번호 입력 검증
- 보너스 번호 검증

### 로또 게임 진행

- 구입한 로또 수 계산
- 로또 갯수만큼 랜덤 로또 번호 생성
- 로또 번호 오름차순으로 정렬
- 랜덤 보너스 번호 생성

### 로또 게임 당첨 통계

- 예상 숫자와 로또 번호를 비교
- 가장 많이 일치하는 로또 기준으로 일치하는 갯수 측정
- 총 수익률 계산

## 기타

### 상수화

- 입출력 문구 상수화
- 에러 메세지 상수화
- 기타 문구 상수화

## 예외처리

### 로또 구입 금액

- 입력한 금액이 숫자가 아닐때
- 입력한 금액이 음수일 때
- 입력한 금액이 0원 일 때
- 입력한 금액이 1,000원으로 나누어 떨어지지 않을 때
- 같은 숫자를 입력했을 때

### 모듈화

- 각 함수 모듈화 진행
