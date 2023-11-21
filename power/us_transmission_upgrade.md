@def title = "US Transmission Upgrade - Mambo Power"
@def tags = ["syntax", "code"]

# 미국 송전 계획 및 설비 확충 사례

\tableofcontents <!-- you can use \toc as well -->

##  개황

2021년 바이든 행정부의 출범 이후 미국의 에너지정책은 탄소중립을 키워드로 하여 청정에너지 육성에 중점을 두고 있다. 
이와 함께, 경제 전반적으로 더욱 가속화되고 있는 전기화, 보다 높은 전력 계통 신뢰성과 복원력에 대한 규제 기관 및 고객의 요구와 같은 요인들에 의해 미국의 송전망에 대한 투자의 필요성은 해마다 증가하고 있다. 

미국에서의 송전 설비 계획 및 확충은 그 범위에 따라 크게 세 가지로 구분하여 볼 수 있는데 송전 설비 계획 region 내에 위치한 단일 송전 서비스 제공자 혹은 단일 소매 배전 회사의 서비스 구역으로 제한된 local 송전 설비 계획, region 단위의 region 송전 설비 계획, 그리고 여러 region들이 동시에 고려되는 inter-region 송전 설비 계획이 그 세 가지이다.

미국 주들 간의 상거래에서 전력의 도매 판매 및 송전에 대한 규제를 담당하는 FERC (Federal Energy Regulatory Commission)는 미국 전력 송전에 대한 규제기관 중 최상위 기관 중 하나인데 FERC는 아래의 그림 1과 같이 송전 설비 계획 region들을 지정하고 있다. 
본 포스팅에서는 주로 region 송전 설비 계획 및 확충을 논의하도록 한다.


![](/assets/images/TransmissionPlanningRegion.jpg)

그림 1. FERC에서 지정된 송전 설비 계획 Region 
(출처: [FERC](https://www.ferc.gov/media/regions-map-printable-version-order-no-1000))

## 미국 송전 계획 현황과 확충 사례

### 미국 송전 계획 규제 및 현황

2007년 발행된 FERC 오더 890번과 2011년 발행된 오더 1000번은 region 송전 설비 비용 할당에 대한 기본 원칙과 송전 설비 계획 region들이 region 송전 설비 계획 및 확충 비용 할당할 때 따라야 하는 요구 사항들을 설정하고 있다. 
특히 FERC 오더 1000번은 다음과 같은 6가지 비용 할당 원칙을 결정하였다.

-   region 송전 설비 계획으로 선택된 송전 설비의 비용은 설비로 인하여 이익을 얻는 이들에게 그 예상 이익에 대략적으로 상응하는 방식으로 할당되어야 한다.
-   현재 또는 미래에 송전 설비로부터 혜택을 받지 못하는 이들에게 송전 설비의 비용을 비자발적으로 할당해서는 안된다. 
-   송전 설비 프로젝트를 선택하는 기준으로 비용 대비 편익 비율을 사용할 경우, 임계 비율은 1.25 대 1을 초과할 수 없다. 
-   비용은 region 밖의 다른 주체가 자발적으로 해당 비용의 일부를 부담하지 않는 한 region 내에서만 할당되어야 한다.
-   송전 설비 혜택과 수혜자를 식별하는 방법은 투명해야 한다. 
-   다양한 유형의 송전 설비에 대해 서로 다른 region 비용 할당 방법을 선택할 수 있다.

이에 따라 각 region들은 각자의 지역별 실정과 규제에 맞추어 송전 설비 계획 수립 및 확충 절차를 개발하였는데, 다음의 두 가지 접근법으로 크게 나누어 볼 수 있다.

-   후원 접근법: 
    후원 접근 방식은 region의 송전 관리 책임 단체가 송전 설비 개발자들에게 region 송전 설비 확장 요구를 해결할 수 있는 구체적인 송전 설비 프로젝트를 제안하도록 한 후, 각 제안을 평가하여 그 제안이 다른 대안들보다 더 효율적인지의 여부를 결정한다. 
    제안이 효율적이라고 판단되면 해당 프로젝트는 region 비용 할당 대상으로 선택되며 제안한 송전 설비 개발자는 region 송전 비용 할당 방법을 사용할 자격이 생기게 된다. 
    이러한 후원 접근 방식에서는 송전 설비 개발 프로젝트와 그 프로젝트를 제안한 송전 설비 개발자가 하나의 제안으로 묶여 서로 경쟁하게 된다.

-   경쟁 입찰 접근법: 
    경쟁 입찰 방식은 region 송전 설비 필요 사항을 먼저 평가한 후, 필요한 필요 사항을 충족하는 효율적인 송전 개발 솔루션을 선택한다. 
    이렇게 사전 식별된 송전 개발 솔루션은 자격을 갖춘 송전 설비 개발자 모두에게 공개되고 최종 개발자는 경쟁 입찰 과정을 통하여 선택된다. 
    즉, 후원 접근법과는 달리 송전 개발 계획은 경쟁 입찰 이전에 결정되어 송전 설비 개발자 결정과는 별개로 진행된다.

이러한 두 가지 region 송전 설비 계획 절차 중 후원 접근 방식은 region 송전 관리 책임 단체가 구조 개편된 Independent System Operator (ISO) 혹은 Regional Transmission Operator (RTO)인지, 아니면 기존의 수직적으로 통합된 전력 회사들로 구성된 단체인지에 따라서 그 절차에 차이점을 보이고 있다. 
대부분의 비 ISO/RTO region은 후원 접근 방식을 사용하고 있다. 
이러한 비 ISO/RTO region에서는 region 송전 계획에 참여하는 송전 설비 소유자들이나 전력 회사들의 개별 송전 계획들을 취합하여 기본 region 송전 계획을 도출하는데 이러한 기본 region 송전 계획은 이해 관계자 및 예상 송전 개발자이 제안하는 region 송전 필요 사항 및 프로젝트를 평가하는 데 사용된다. 
이에 반해, ISO/RTO는 비 ISO/RTO region 내의 개별 전력 회사보다 훨씬 더 광범위한 송전 계획에 대한 책임이 있으며 local 송전 설비 소유자들이 각각 수립하는 local 송전 계획과는 별도로 송전 계획을 수립하게 된다. 

다음의 그림 2는 미국 내 후원 접근법과 경쟁 입찰 접근법을 사용하는 region들을 비 ISO/RTO region과 ISO/RTO region으로 구별하여 보여주고 있다.


![](/assets/images/RegionalTransmissionPlanningApproach.jpg)

그림 2. Region 별 송전 계획 접근법 
(출처: Joseph H. Eto and Giulia Gallo, “Regional Transmission Planning”, Lawrence Berkeley National Laboratory, Nov. 2017)

이러한 region 송전 설비 계획 수립에 있어서 매우 중요한 절차 중 하나가 region 송전 필요 사항과 후보 프로젝트들의 편익을 평가하는 것이다. 
이러한 필요 사항과 편익은 크게 신뢰도, 정책적 필요, 경제성의 세가지 요소로 나누어 볼 수 있는데, 기존의 많은 송전 설비 계획들은 이러한 요소들 중 하나씩만을 고려하여 수립되었다. 
이는 친환경 청정 에너지로의 장기적 리소스 전환을 미리 대비하여 앞서 나가는 송전 설비 계획을 수립할 수 없게 하였고 미국 대부분의 지역에서 긴 발전기 계통 연결 대기열, 송전 혼잡, 빈번한 발전기 출력 제한 등의 결과를 초래하였다. 
이에 Midcontinent Independent System Operator (MISO), California Independent System Operator (CAISO) 등을 포함한 region 송전 계획 책임 단체들은 여러 편익 요소들을 동시에 고려하는 다중 가치 프로젝트 (Multi-Value Projects, MVPs) 접근법을 사용하여 보다 성공적인 송전 설비 계획을 도출하고 있다.

### 송전 설비 확충 사례

본 포스팅에서는 다중 가치 송전 설비 프로젝트의 사례로 2022년 7월에 승인된 MISO의 Long Range Transmission Plan (LRTP) Tranche 1 포트폴리오를 살펴보고자 한다. 
이 포트폴리오는 장래 닥쳐올 신재생 에너지원의 증가에 미리 대비하는 것을 주목적으로 하여 장기간 준비하여 수립된 계획이다. 

MISO는 2019년 MISO Forward 보고서를 통한 전반적인 산업 추세와 발전 설비와 기술 발전 등으로 인한 리소스 유연성 및 가용성 등에 대한 문제점들의 조사를 시초로 하여 좀 더 장기적이고 예방적인 송전 설비 계획의 필요성을 인지하게 되었다. 
이에 MISO는 관련 연구의 범위와 접근법을 논의하기 위해 2020년 6월 이해관계자들에게 LRTP의 개념적 로드맵을 소개하였고 2020년 8월에는 일련의 기술적 논의를 시작하여 이해관계자들로부터 연구 방법과 가정들에 대한 의견들을 구하며 진행 중인 일의 정기적인 업데이트와 분석 결과를 제공하였다. 
또한, 2021년 2월에는 Regional Expansion Criteria and Benefits Working Group과 함께 비용 할당 메카니즘에 대한 논의를 개시하였고 2021년 10월 LRTP 워크샵에서 편익 요소들과 편익을 정량화할 척도를 파악하기 위하여 개발된 Business Case를 선보였다. 
뒤이어 2022년 봄에 MISO는 LRTP Tranche 1 계획을 발표하였고 그 해 7월에 이사회에서 만장일치로 승인되었다. 
MISO는 이렇게 장기간을 걸쳐 송전 설비 계획을 세움으로써 최대한 많은 이해당사자들의 합의와 송전 설비 계획의 편익을 다각도로 검토, 확인할 수 있었고 이는 좀더 성공적인 송전 설비 확장을 가져올 수 있을 것으로 예상하고 있다. 
그림 3은 LRTP Tranche 1 송전 설비 계획을 세우기 위한 워크샵들과 Planning Advisory Committee (PAC)를 통한 이해관계자들의 의견 사정을 시간대별로 보여주고 있다.


![](/assets/images/MisoLrtpTranche1WorkshopTimeline.jpg)

그림 3. MISO의 LRTP Tranche 1 송전 설비 계획을 위한 시간대별 워크샵과 PAC
(출처: MISO, [“LRTP Tranche 1 Portfolio Detailed Business Case”](https://cdn.misoenergy.org/20220329%20LRTP%20Workshop%20Item%2002%20Detailed%20Business%20Case623671.pdf), June 25, 2022)

MISO의 LRTP Tranche 1 송전 설비 포트폴리오는 총 18개의 개별 프로젝트들로 구성되어 있는데 그림 4는 이러한 프로젝트들의 위치와 구성을, 표 1은 2022년 7월 25일 당시의 각 프로젝트들의 비용을 보여주고 있다. LRTP Tranche 1 송전 설비 포트폴리오의 총 비용은 103억 달러이다. 

![](/assets/images/MisoLrtpTranche1Portfolio.jpg)

그림 4. MISO의 LRTP Tranche 1 송전 설비 포트폴리오 구성
(출처: Rob Gramlich, “Enabling Low-Cost Clean Energy and Reliable Service Through Better Transmission Benefits Analysis - A Case Study of MISO’s Long Range Transmission Planning”, Grid Strategies LLC, August 9, 2022)


표 1. 2022년 7월 25일 당시 MISO의 LRTP Tranche 1 송전 설비 계획의 각 프로젝트별 비용
(출처: MISO, [“LRTP Tranche 1 Portfolio Detailed Business Case”](https://cdn.misoenergy.org/20220329%20LRTP%20Workshop%20Item%2002%20Detailed%20Business%20Case623671.pdf), June 25, 2022)

![](/assets/images/MisoLrtpTranche1Cost.jpg)


2022년 달러 가치로 환산한 20년과 40년 동안의 수익 요구 조건의 현재 가치를 6.9%와 3.0%의 할인율을 가정하여 예측한 결과가 그림 5에 나타나 있다. 
이에 따르면 할인율이 6.9%일 때 총 송전 설비 포트폴리오에 요구되는 수익은 141억 달러에서 168억 달러, 할인율을 3.0%로 가정하면 186억 달러에서 261억 달러의 수준을 갖는다.

![](/assets/images/MisoLrtpTranche1Revenue.jpg)

그림 5. MISO의 LRTP Tranche 1 송전 설비 계획 기대 수익
(출처: MISO, [“LRTP Tranche 1 Portfolio Detailed Business Case”](https://cdn.misoenergy.org/20220329%20LRTP%20Workshop%20Item%2002%20Detailed%20Business%20Case623671.pdf), June 25, 2022)

MISO의 편익 분석 과정은 Regional Expansion Cost and Benefits Working Group을 통한 광범위한 이해관계자들의 논의를 포함하고 있으며 이는 MISO의 송전 계획 개발에 매우 중요한 과정이다. 
LRTP Tranche 1 편익-비용 분석을 위해 MISO가 사용한 편익 범주들은 아래의 목록을 포함하고 있다. 
목록 중 항목 1에서 4까지는 기존의 MISO 다중 가치 프로젝트에 포함된 항목들이며 항목 5와 6는 다중 가치 프로젝트 방법에서 새롭게 추가된 범주들이다.

1.   혼잡 및 연료 절약
1.   Local 자원 투자의 회피를 통한 자본 비용 절감
1.   송전 투자 회피
1.   자원 적정성 (Resource Adequacy) 요건 감소
1.   부하 차단 위험 방지
1.   탈탄소화

그림 6은 각 항목별 편익과 총 투자 비용을 보여주고 있는데, 총 편익은 373억 달러에서 691억 달러로, 141억 달러에서 168억 달러 사이인 총 비용을 제하면 순 편익이 232억 달러에서 525억 달러에 달한다.

![](/assets/images/MisoLrtpTranche1CostBenefitAnalysis.jpg)

그림 6. MISO의 LRTP Tranche 1 편익 분석 결과
(출처: Rob Gramlich, “Enabling Low-Cost Clean Energy and Reliable Service Through Better Transmission Benefits Analysis - A Case Study of MISO’s Long Range Transmission Planning”, Grid Strategies LLC, August 9, 2022)

## 전망

안정적이고 건강한 송전 시스템은 국가의 경제, 에너지 및 안보에 매우 중요하다. 
미국의 송전 시스템은 노후화된 인프라와 불충분한 송전 용량으로 인해 지속적으로 문제에 직면하고 있는데 급증하고 있는 신재생, 청정 에너지원은 이러한 문제들을 가속화하고 있다. 
이러한 송전 설비 문제의 가장 큰 요인으로 기존의 단기적이고 단편적인 송전 설비 확장이 미국의 장기적인 에너지원 전환을 해결하기에는 역부족이었다는 지적이 나오고 있다.

MISO의 LRTP Tranche 1 사례와 같은 다중 가치 프로젝트 접근법은 이러한 문제에 대한 해결책 중 하나로 볼 수 있다. 
또한 좀 더 근본적인 해결책으로 규제 정책의 개선이 논의되고 있다. 
FERC는 기존의 오더 890번과 1000번이 이러한 문제점을 야기하였다는 우려를 가지고 있다. 
이에 FERC는 2022년 4월 21일 region 송전 계획 수립과 비용 할당 조건들을 전반적으로 개선할 목적으로 Notice of Proposed Rulemaking (NORP)을 발표하였다. 
이러한 정책 변화는 region 송전 계획을 수립할 때 장기적인 부하와 전원 믹스의 변화, 기후 변화 등을 고려하는 미래 지향적 접근법을 활용할 수 있도록 할 것이다. 
 

## 참고문헌
1.  Joseph H. Eto and Giulia Gallo, “Regional Transmission Planning”, Lawrence Berkeley National Laboratory, Nov. 2017
1.  Rob Gramlich, “Enabling Low-Cost Clean Energy and Reliable Service Through Better Transmission Benefits Analysis - A Case Study of MISO’s Long Range Transmission Planning”, Grid Strategies LLC, August 9, 2022
1.  MISO, [“LRTP Tranche 1 Portfolio Detailed Business Case”](https://cdn.misoenergy.org/20220329%20LRTP%20Workshop%20Item%2002%20Detailed%20Business%20Case623671.pdf), June 25, 2022
1.  United States Department of Energy, “National Transmission Needs Study”, February 2023




