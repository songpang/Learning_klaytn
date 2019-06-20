# Learning_klaytn

## 기존 블록체인 플랫폼의 약점

###  Scalability 
- TPS + Block Interval
  1. Transaction Per Second : 초당 거래 처리 
  2. Block Interval : 블록 생성 간격

#### TPS
> Visa : TPS 1700, Bitcoin : TPS 7, Etherum : TPS 15~20

#### Block Interval
> Bitcoin : 10분, Ethereum : 15초~20초

#### 기존의 블록체인은 왜 느린가?
- 전체 Network의 Performance가 가장 느린 Node에 맞춰진다.
- 비트코인 & 이더리움 : 많은 양의 트랜잭션을 처리하기에 부족하고 네트워크 자체 속도도 느리다.

### Finality
> 블록이 Final하다는 것 -> 블록에 담긴 TX가 바뀔 수 없다는 걸 보증

- 비트코인 & 이더리움의 Mining mechanism
  1. 최종성 부족
  2. 확률론적 최종성만 제공
  
  - 비트코인 : Finality까지의 평균 시간 ( 60분 : 6번의 검증 )
  - 이더리움 : Finality까지의 평균 시간 ( 6분 : 25번의 검증 )

### 작업증명 (PoW)방식
- 블록체인에 블록을 추가하기 위해 문제를 품 ( Hash값 찾기 )
-> 두개의 노드가 비슷한 시간대에 문제를 풀었을 경우 분기 발생


