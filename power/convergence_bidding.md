@def title = "Convergence Bidding - Mambo Power"
@def tags = ["syntax", "code"]

# 전력 시장에서의 Convergence Bidding

Convergence bidding, 또는 virtual bidding은 도매 전력 시장에서 널리 채택되었습니다. 이는 시장 참가자들에게 day-ahead 시장의 위치별 한계 가격과 real-time 시장의 위치별 한계 가격 사이의 차이를 차익 거래할 기회를 제공합니다.

\tableofcontents <!-- you can use \toc as well -->


## 이중 정산 시스템

미국의 표준 전력 시장 설계는 day-ahead 시장과 real-time 시장에 대한 이중 정산 시스템을 따릅니다. 이 시스템은 발전기의 시작-정지 제약과 관련된 기술적 요인에 의해 영향을 받습니다.

## Convergence Bidding

Convergence bidding은 day-ahead 시장에서 계약된 후 real-time 시장에서 청산되는 재무 거래입니다. 이는 day-ahead 시장 가격에서 사고/팔고, 그런 다음 real-time 시장 가격에서 동일한 양의 전력을 특정 노드에서 팔고/사는 것을 포함합니다. 이로 인해 day-ahead 시장 가격과 real-time 시장 가격 사이의 차이에 기반한 재무 거래가 발생합니다.

Convergence bidding은 Federal Energy Regulatory Commission (FERC)의 표준 시장 설계의 일부입니다. 이는 2011년 2월에 처음으로 캘리포니아 시장에 도입되었습니다.

## Day-Ahead 시장에서의 Convergence Bidding 역할

Convergence bidding은 시장에서 물리적 입찰과 경쟁하여 day-ahead 시장을 청산합니다. 이는 day-ahead 시장에서 물리적 발전 자원의 시작-정지에 영향을 미칩니다. day-ahead 시장에서는 가상 공급과 가상 수요가 물리적 공급과 수요와 동일하게 취급됩니다. 이들은 시장 청산에 사용되는 공급 곡선과 수요 곡선의 형성에 기여합니다. 이들은 day-ahead 시장 가격을 결정할 수 있습니다. 이들은 동일한 스케줄링 조정자 (SC)가 제출한 물리적 공급 또는 수요와는 아무런 관련이 없습니다.

## Convergence Bidding의 장점과 단점

Convergence bidding에는 여러 가지 장점이 있습니다. 이에는 시장 유동성 향상, 시장 경쟁 강화, 시장 참가자에게 위험 헤지 수단 제공, real-time 시장 가격 신호 제공 등이 포함됩니다.

그러나 이에는 몇 가지 단점도 있습니다. 이는 다른 시장 제품과 연결될 때 시장 조작을 초래할 수 있으며 비효율을 초래할 수 있습니다.

## 전력 시장에서의 Convergence Bidding 활용

Convergence bidding은 물리적 시장 참가자들이 real-time 시장 가격 변동성에 대해 헤지할 수 있도록 사용할 수 있습니다. 또한 이는 real-time 시장에서의 혼잡 위험에 대해 헤지할 수 있도록 사용할 수 있습니다. 재무 시장 참가자들은 이를 사용하여 day-ahead 시장 가격과 real-time 시장 가격 사이의 차익을 추구할 수 있습니다.

## Convergence Bidding Hedging 예제

전력 회사의 경우, day-ahead 시장에서 계획된 부하가 850 MWh이고 LMP가 $100/MWh인 경우, real-time 시장에서 실제 부하가 950 MWh이고 LMP가 $120/MWh인 경우, 수요 convergence bid를 100MWh 사용할 수 있습니다. 이는 day-ahead 시장에서 사고 real-time 시장에서 팔도록 하는 것을 포함합니다.

발전 회사의 경우, day-ahead 시장에서 계획된 발전량이 400 MWh이고 LMP가 $50/MWh인 경우, real-time 시장에서 실제 발전량이 250 MWh이고 LMP가 $65/MWh인 경우, 수요 convergence bid를 200MWh 사용할 수 있습니다. 이는 day-ahead 시장에서 사고 real-time 시장에서 팔도록 하는 것을 포함합니다.

## 결론

Convergence bidding은 전력 시장에서 중요한 역할을 하는데, 이는 시장 참가자들이 가격 변동성과 혼잡 위험에 대해 헤지하고, 차익 기회를 추구할 수 있는 메커니즘을 제공합니다. 그러나 이에는 시장 조작과 비효율의 가능성과 같은 잠재적인 단점도 있습니다. 따라서 시장 참가자들은 Convergence bidding의 작동 방식을 이해하고 전략적으로 이를 사용해야 합니다.

참조:
 A Data-Driven Convergence Bidding Strategy Based on ...
 Convergence bidding - CAISO
 Strategic Convergence Bidding in Nodal Electricity Markets: Optimal Bid ...
 Efficiency impact of convergence bidding in the California electricity ...
 Efficiency impact of convergence bidding in the California electricity ...
