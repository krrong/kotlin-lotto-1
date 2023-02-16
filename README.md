# kotlin-lotto

# domain
## Lotto
- [X] 일급 컬렉션으로 사용(Set)  
- [X] 검증이 필요한 부분  
    - [X] 개수가 6개면 로또 생성
    - [X] 개수가 6개가 아니라면 exception 발생
    - [X] 번호가 범위안에 들어오는지 검증  

## Lottos 
- [X] 로또들의 정보를 저장  
 
## WinningLotto
- [X] 일급 컬렉션으로 사용
- [X] 검증
  - [X] 당첨번호와 보너스 번호가 같으면 exception 발생
  - [X] 당첨번호와 보너스 번호가 다르면 winningLotto 생성
  - [X] 보너스번호가 범위안에 들어오는지 검증

## LottoSeller
- [X] 로또를 한 장 발급한다.  
- [X] 파라미터(금액 / 1000)로 입력받은 개수만큼 로또를 발급한다.  

## LottoStatistics
- [X] 당첨 통계를 낸다.
    - [X] 당첨 번호와 일치하는 숫자의 개수를 찾는다.
    - [X] 로또가 보너스 번호를 포함하는지 여부를 확인한다.
    - [X] 단일 로또를 넘겨 받아서 당첨 결과를 반환한다.
- [X] Ticket을 넘겨 받아서 당첨 번호와 비교한다.
  - [ ] 수익률을 계산한다.  

## RandomGenerator
- [X] 6개의 무작위 수 생성

## Enum class
- [X] 등수와 금액을 저장한다.
- [X] 당첨 번호와 보너스 볼 매치 여부로 당첨 등수 반환

---

# View
## InputView
- [ ] 구입 금액을 입력받는다.  
- [ ] 당첨 번호를 입력받는다.  
- [ ] 보너스 볼을 입력받는다.  

## ResultView
- [ ] 당첨 통계를 출력한다.  
- [ ] 수익률을 출력한다.  

---

# Controller
## Controller
- [ ] 전체 로직을 담당한다.  
