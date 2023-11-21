@def title = "Git - Mambo IT"
@def tags = ["syntax", "code"]

# Git

Git is a distributed version control system created by Linus Torvalds in 2005. 
It allows multiple developers to work on a project simultaneously without overwriting each other's changes. 
Git tracks changes in snapshots called commits and allows for branching, where changes can be made without affecting the main code. 
It emphasizes on local operations, enabling offline work and reducing network latency. 
Git is efficient and can handle projects of any size.

\tableofcontents <!-- you can use \toc as well -->

## Using Git Without a Remote Server

Using Git locally without a remote server but with a central repository on your local machine can be beneficial in several ways:

-    **Offline Work**: You can work offline and not have to worry about network latency or connectivity issues. All your changes are stored locally.

-    **Fast and Efficient**: Local operations in Git are fast and efficient because they don't involve network communication. 

-    **Full Version Control**: You still get the full benefits of version control, including tracking changes, branching, and merging.

-    **Learning and Experimentation**: It's a great way to learn and experiment with Git without the fear of messing up a remote repository.

-    **Single User Projects**: For single user projects or for initial development stages, it might be easier to work locally before pushing changes to a remote server.

Remember, even though you're working locally, it's still important to regularly backup your work to prevent any loss of data.
 
**Workflow**

Follow these steps to set up a local Git repository:

-   Step 1: Create Central Repository

1.  Open your terminal.
2.  Create a new directory which will act as your central repository:
    ```
    mkdir /path/to/your/project
    ```
3.  Navigate into the new directory:
    ```
    cd /path/to/your/project
    ```
4.  Initialize the directory as a Git repository:
    ```
    git init --bare
    ```
    Your central repository is now set up at `/path/to/your/project`.

-   Step 2: Clone the Repository

1.  Navigate to the directory where you want your working copy:
    ```
    cd /path/to/your/working/directory
    ```
2.  Clone the central repository:
    ```
    git clone /path/to/your/project
    ```
    You now have a working copy of your Git repository. You can make changes, stage them, and commit them. When you're ready to share your commits with the central repository, use `git push`.

> **Note:** This setup is local to your machine. For collaboration with others, consider setting up a remote repository on a server accessible to all collaborators.



![](/assets/images/GridRenewableInvestmentTrend.jpg)

그림 1 연도별 송배전망과 재생 에너지 글로벌 투자금 추이
(출처: Fatih Birol, [Twitter](https://twitter.com/fbirol/status/1714144657439961591?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1714144757083959569%7Ctwgr%5E0c334052466a0f6d3b574bf5db7bceb271dfcdda%7Ctwcon%5Es2_&ref_url=https%3A%2F%2Fwww.cnbc.com%2F2023%2F10%2F17%2Fworld-must-add-or-replace-50-million-miles-of-transmission-lines-iea.html), IEA, Oct. 2023)


## 글로벌 송전망 현황

### 송배전망 확장 추이

지난 5개년 동안 연간 약 1백만 km씩의 확장을 포함여, 글로벌 송배전망은 지난 30년 동안거의 두 배의 거리로 증가했으며, 이는 주로 송배전망 전체 길이의 약 93%를 차지하는 배전망의 확장으로 인한 것이다. 송전망은 송배전망의 나머지 7%의 길이를 차지하고 있다. 그림 2는 1971년부터 2021년까지 10년 단위의 글로벌 송배전망 길이의 추이를 보여주고 있다. 그림에서 EMDE는 신흥 시장 및 개발 도상국 (emerging market and developing economies)을 의미한다.
그림에 나타난 바와 같이, 대부분의 송배전망의 확장은 신흥 시장 및 개발 도상국의 배전망 확장에서 비롯되었다. 이러한 현상은 신흥 시장 및 개발 도상국에서의 전력 접근성의 확장을 보여주고 있는 것이다. 구체적인 사례로, 인도에서는 Saubhagya 프로그램이 수백만 가정을 전력 시스템에 연결하는 데 중요한 역할을 했으며, 이로써 국가 전체의 전력 부족을 효과적으로 감소시키고 수많은 시민들의 삶의 질을 향상시켰다. 마찬가지로 중국은 2006년 국가전망공사의 프로그램을 비롯하여 여러 전기화 프로그램을 추진했으며, 이로써 2015년까지 190만 가구와 750만 명에게 전기를 제공했으며, 중국남방전력그룹의 프로그램은 2012년까지 230만 명에게 전기를 제공했다. 이로 인해 2015년 말까지 중국 14억 인구 중 거의 전체가 전력 에너지에 접근할 수 있었다.

![](/assets/images/GlobalGridLengthTrend.jpg)

그림 2 글로벌 송배전망 거리의 추이 
(출처: International Energy Agency, [“Electricity Grids and Secure Energy Transitions”](https://iea.blob.core.windows.net/assets/ea2ff609-8180-4312-8de9-494bcf21696d/ElectricityGridsandSecureEnergyTransitions.pdf), October. 2023)

송전망의 확장 역시 신흥 시장 및 개발 도상국에서의 확장이 큰 부분을 차지하고 있다. 지난 10년 동안 신흥 시장 및 개발도상국은 약 117만 km에 이르는 새로운 송전선을 건설했는데 이러한 송전망 확장의 주된 이유는 전기 수요의 증가로 인한 전기 접근성의 확대라고 볼 수 있다. 특히 중국은 지난 10년 동안 세계 송전망 확장의 약 1/3 이상을 차지하였는데, 대표적인 사례로 50만 km 이상의 송전선을 건설하여 풍부한 재생  에너지를 가지고 있는 북부 및 서부 지방과 동부 부하 중심지를 초고압 송전 선로를 통해 연결한 것을 들 수 있다. 중국 외에도 인도와 브라질 역시 송전망 확장에서 상당한 진전을 이루어냈다. 지난 10년 동안 인도는 거의 18만 km의 송전선을 추가하여 약 60%의 송전망 증가를 보였고, 마찬가지로 브라질은 동일 기간 동안 송전망을 9만 2천 km 이상 확장하여 50% 이상의 송전망 확장을 보였다.

반면에 선진국은 같은 기간 동안 상대적으로 적은 9%의 송전망 성장을 보였다. 이는 이미 높은 인구 밀도를 갖는 일본과 한국과 같은 국가에서 도시로의 이주가 증가함에 따라 시골 지역으로의 송전망 확장의 필요성이 감소한 것과 관련이 있다. 유럽 연합은 송전망이 12% 증가하였으며, 미국은 3% 증가했다. 

### 송전망의 노후화

각 국의 송전망은 투자 및 지속적인 현대화 노력과 같은 여러 요인들에 영향을 받아 그 노후화 정도가 다르다. 또한 송전망 설비의 수명은 특정 구성 요소, 과부하 및 용량 문제, 환경 요인, 유지보수 방법 및 기술적 발전에 따라 다양하다. 그림 3은 각종 송전망 설비들의 일반적인 수명을 보여주고 있다.

![](/assets/images/GridComponentTypicalLifespan.jpg)

그림 3 각종 송전 설비의 일반적인 수명 
(출처: International Energy Agency, [“Electricity Grids and Secure Energy Transitions”](https://iea.blob.core.windows.net/assets/ea2ff609-8180-4312-8de9-494bcf21696d/ElectricityGridsandSecureEnergyTransitions.pdf), October. 2023)

노후화된 송전망 설비들은 심각한 안전 및 신뢰성 위험을 야기할 수 있다. 예를 들어, 시간이 지남에 따라 변압기의 절연 특성은 감소하여 전기적 결함, 단락 및 화재의 발생 가능성이 높아진다. 송전망 설비의 신뢰도는 시간이 지남에 따라 점점 떨어지며, 특히 정격 수명을 초과하여 운영될 때 더욱 심해진다. 감소된 신뢰도는 정전을 야기시킬 수 있을 뿐만 아니라 설비의 보호 메커니즘이 제대로 작동하지 않을 경우 잠재적인 설비의 손상으로 이어질 수 있다.

선진국에서는 송배전망 설비들이 종종 오래되어 초기 설치 이후 50년 이상 운영 중인 경우가 많다. 따라서, 이러한 노후된 인프라를 향상시켜 효율성과 신뢰성을 높이고 새로운 에너지 자원을 수용할 필요성이 커지고 있다. 전체적으로 선진국에서는 송배전망 인프라의 약 23% 정도만이 10년 미만 된 것이며, 약 50% 이상이 20년 이상된 것이다.

이에 반해 신흥 시장 및 개발 도상국은 좀더 최근에 개발된 신형 송배전망 설비들을 가지고 있으며 전체 송배전망 인프라 중 약 40%가 10년 미만이고, 38% 미만이 20년 이상이다. 아프리카 대륙은 송배전망 인프라의 상태에 있어서 상당한 지역적 차이를 보이며, 일부 국가들은 송배전망의 현대화 및 확장에서 상당한 진전을 이루고 있는 반면, 다른 국가들은 송배전망을 개발하고 유지하는 데 큰 어려움을 겪고 있다. 인도는 송배전망 인프라가 오래된 구식과 최신형 설비들이 혼합되어 있는 형태를 갖고 있으며, 도시 중심부가 더 현대화된 송배전망 설비들을 갖추고 있다. 인도는 전기 접근성을 개선하고 재생 에너지원을 통합하기 위해 송배전망 설비들을 개선하고 확장하는 데 적극적으로 노력하고 있으며, 결과적으로 인도의 송배전 설비 중 약 45%가 10년 미만인 것이다. 중국은 전원이 부족한 지역에 송배전망을 확장하여 지역적 및 서비스 부족 지역에 전기를 공급하는 데 큰 진전을 이루었다. 예를 들어, 서부 지방에서 전력을 생산하여 동부 지역에 공급하는 서동 전기 전송 프로젝트와 같은 프로젝트들은 전력 계통 연결성을 향상시켰다. 중국은 또한 세계에서 가장 큰 재생 에너지 투자 국가이며, 풍력 및 태양광 발전을 전력 계통에 성공적으로 통합하고 있다. 초고압 송전선의 배치로 효율적인 장거리 전력 전송을 가능케 하여 재생 에너지 개발을 지원하고 있는 중국은 10년 동안 71만 km 이상의 송전선을 건설하여 10년 미만 된 송전선을 가장 많이 보유하고 있다. 그림 4는 2021년 현재 각 국가 및 지역별 송배전 설비의 노후화 비율을 보여주고 있으며, 그림 5는 송배전 설비의 연식을 비교하여 보여주고 있다.

![](/assets/images/GridAgeRatio.jpg)

그림 4 각 국가 및 지역별 송배전 설비의 노후화 비율 
(출처: International Energy Agency, [“Electricity Grids and Secure Energy Transitions”](https://iea.blob.core.windows.net/assets/ea2ff609-8180-4312-8de9-494bcf21696d/ElectricityGridsandSecureEnergyTransitions.pdf), October. 2023)


![](/assets/images/GridAgeComparison.jpg)

그림 5 각 국가 및 지역별 송배전 설비의 연식 비교 
(출처: International Energy Agency, [“Electricity Grids and Secure Energy Transitions”](https://iea.blob.core.windows.net/assets/ea2ff609-8180-4312-8de9-494bcf21696d/ElectricityGridsandSecureEnergyTransitions.pdf), October. 2023)


## 송전망 문제

### 전기화의 증가로 인한 전력 수요 증가

2000년 이후 전 세계적인 최종 전기 소비는 거의 두 배로 증가하고, 1990년 이후 매년 꾸준히 성장하였으며, 2009년 금융 위기와 2020년 코로나19 대유행을 제외하고는 수요가 감소한 적이 없었다. 2022년에는 전 세계적인 에너지 위기에도 불구하고 증가세를 이어갔는데, 이러한 증가세는 특히 신흥 시장 국가들의 수요 증가가 주도하였다.

전력의 글로벌 최종 에너지 소비에서의 비중은 2000년의 16%에서 2021년에는 21%로 증가하여 석유에 이어 두 번째로 높은 수준이 되었다. 이는 전력이 글로벌 에너지 믹스에서의 중요성이 높아지고 있는 추세를 반영하며, 이 추세는 계속될 것으로 예상된다. 이러한 전력 수요의 증가는 전기화 증가 및 전 세계적인 전력 접근률 증가에 의해 주도되고 있다. 

2021년 자료에 따르면 전 세계적으로 산업 부문이 전체 최종 전기 소비의 43%를 차지하며, 주거 부문이 27%, 서비스 부문이 20%를 차지했다. 건물에서 사용되는 전기 중 20%는 냉각을 위해 사용되며, 2000년 이후 건물 내 냉각 에너지 사용은 두 배 이상 증가했다. 뿐만 아니라, 고가격의 가스와 에너지 안전에 대한 우려로 인해 열 펌프의 수요가 증가하며 난방에 대한 전기화가 증가하고 있다. 교통 부문의 전기 소비는 현재 총 전기 소비의 일부에 불과하며, 2022년에는 글로벌 전기 자동차의 전력 소비가 총 전력 소비의 0.5% 미만을 차지했다. 그러나 교통 부분에서의 전기화는 지속적으로 진행 중이며, 매년 새로운 전기 자동차 판매 기록이 세워지고 있다. 전기 자동차가 높은 침투율을 보이는 곳에서는 이로 인하여 전력망 수용 능력에 대한 문제가 발생할 수 있는데, 구체적인 예를 들면, 네덜란드에서는 3,000여개의 지역에서 2025년까지새로운 충전소를 설치할 수 없을 것으로 예상된다.

이러한 각종 부분에서의 전기화는 과거 10년 동안 큰 진전이 이루어졌지만, 전 세계 인구의 10%는 여전히 전기에 접근할 수 없다는 사실은 앞으로 지속적인 전력 수요의 증가와 전력 계통 인프라의 확장이 예상된다는 점을 시사한다. 

### 재생 에너지 증가

미국, 스페인, 브라질, 이탈리아, 일본, 영국, 독일, 호주, 멕시코, 칠레, 인도, 그리고 콜롬비아는 현재 총 3TW의 태양광, 풍력, 수력, 그리고 바이오에너지 등의 재생에너지에 대한 전력 계통 연결이 요청되었다. 이 중 약 1,500GW는 태양광 및 풍력 프로젝트로, 연결 계약이 이미 체결되었거나 활발한 검토 중인 심화 단계에 해당하며, 이는 2022년의 태양광 및 풍력 추가 용량의 5배에 해당한다. 또한, 그 중 500GW는 연결 계약이 이미 체결되었거나 계통 연결 계약의 최종 단계에 도달해 있어 계발자들의 개발 중단이 있지 않으면 앞으로 5년 이내에 전력 계통에 연결될 높은 가능성을 가진 후반 단계에 도달한 프로젝트들이다.

이러한 새로운 재생 에너지 프로젝트들 중 많은 부분은 송전망 인프라에 상당한 투자가 필요하다. 한 예로, 스페인에서 현재 계통 연결 승인을 받은 모든 태양 및 풍력 프로젝트를 구축하면 현재 설치 용량이 거의 3배로 증가할 것으로 예상된다. 현재 후반 단계에 있는 태양 및 풍력 프로젝트를 고려하면 이탈리아에서는 2022년 말 설치 용량이 45% 이상 증가할 것으로 예상되며, 미국에서는 35% 이상, 영국에서는 거의 35%, 일본에서는 35%, 멕시코에서는 22%, 브라질에서는 16%, 오스트레일리아, 독일, 인도, 칠레에서는 각각 10%, 그리고 콜롬비아에서는 1% 증가할 것으로 예상된다. 이러한 후반 단계의 모든 프로젝트들의 계통 연결이 보장되어 있지는 않지만, 이로 인하여 최종적으로 계통에 연결될 새로운 용량의 규모는 전력 송배전망의 원활한 운영에 더 큰 부담을 가할 것이다. 그림 6은 계통 연결 대기 중인 재생 에너지 프로젝트들의 용량을 나라별, 발전 기술별로 보여주고 있다.

![](/assets/images/RenewableConnectionQueue.jpg)

그림 6 계통 연결 대기 중인 각 국가 및 발전 기술별 재생 에너지 용량 
(출처: International Energy Agency, [“Electricity Grids and Secure Energy Transitions”](https://iea.blob.core.windows.net/assets/ea2ff609-8180-4312-8de9-494bcf21696d/ElectricityGridsandSecureEnergyTransitions.pdf), October. 2023)

현재 발전 용량, 특히 재생 에너지의 급속한 개발은 필요한 송전망 확장 및 개선에 비해 훨씬 빠르게 진행되고 있으며, 이는 재생 에너지의 장기적인 확장에 영향을 미칠 수 있다. 일부 시장에서는 필요한 송전망의 부재로 인해 재생 에너지의 빠른 성장이 제약되고 있다. 네덜란드에서는 고용량의 태양광 및 풍력 용량 추가로 송전 혼잡이 발생하여 2021년에서 2029년 동안 일부 지역이 새로운 발전 용량을 수용하지 못하게 되었으며, 이를 해결할 수 있는 송전망 개발은 2026년부터 2029까지 이루어지도록 계획되어 있다. 하와이에서는 송배전망 문제로 인해 2013년에 지붕 태양광 설치가 사실상 중단되었지만, 이후 송배전망 개선으로 재개될 수 있었다. 남아프리카에서는 최근의 재생 에너지 경매에서 내륙 풍력용량을 할당하지 않았는데, 경매에 제안된 모든 프로젝트가 송전망 이용 가능 지역이 아니었기 때문이다. 미국에서는 PJM 지역의 접속 대기열로 인해 2026년까지 새로운 계통 연결 신청 검토를 중단한 상태이다.

## 전망

재생 에너지의 급격한 증가와 함께 지속적으로 진행 중인 전기화로 인한 전력 수요의 증가는 높은 신뢰도를 기반으로 한 안정적인 송전망 운영에 있어서 전세계적으로 근본적인 어려움을 가져오고 있다. 최근 발표된 국제 에너지 기구의 보고서에 따르면, 2040년까지 세계 각 국가들이 기후 목표를 달성하고 전력 수요를 충족시키기 위해 5천만 마일의 송전선 추가 또는 교체 작업이 필요하며, 2030년까지 연간 6000억 달러 이상의 송전망 투자가 필요하다. 전기화에 따라 증가할 미래 수요에 대한 안정적인 전력 공급과 재생 에너지의 광범위한 도입을 가능하게 하기 위해서는 송전망 투자 수준을 늘리고 관련 정책 및 기술적 변화를 통한 노력이 지속되어야 할 것이다. 

## 참고문헌
1. International Energy Agency, [“Electricity Grids and Secure Energy Transitions”](https://iea.blob.core.windows.net/assets/ea2ff609-8180-4312-8de9-494bcf21696d/ElectricityGridsandSecureEnergyTransitions.pdf), October 2023
2) United States Department of Energy, “National Transmission Needs Study”, February 2023
3) Eric Larson, et al., “Net-Zero America: Potential Pathways, Infrastructure, and Impacts”, October 2021



