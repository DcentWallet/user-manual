# 렛저 지갑의 복구 코드를 사용하여 디센트 지갑에서 복구하는 방법

렛저 지갑과 디센트 지갑 모두 지갑 복구 방식에 대해 동일한 BIP 표준을 따릅니다. 그러나 각 지갑 서비스는 현재 지원하는 디지털 자산 유형별로 개인 키를 생성하기 위해 사용되는 지갑 생성 경로가 동일하지 않을 수 있습니다.

아래는 렛저 지갑과 디센트 지갑의 계정 주소(예: BSC & ETH)를 비교한 스크린샷입니다. 이 예제에서는 렛저 지갑의 니모닉 코드(복구 단어)를 사용하여 디센트 지갑을 복구한  경우입니다. 이 두 지갑 서비스 간에 지갑 생성 경로가 동일하기 때문에 BSC 및 ETH 계정의 주소가 동일하게 생성되었습니다.

<figure><img src="../../.gitbook/assets/그림2 (1) (2).png" alt=""><figcaption></figcaption></figure>

## 복구 호환 자산 목록  <a href="#list-of-recovery-compatible-assets-mainnets" id="list-of-recovery-compatible-assets-mainnets"></a>

아래 암호화폐의 지갑 생성 경로는 렛저 지갑과 디센트 지갑에서 서로 **동일**합니다. **이는 렛저의 니모닉 코드 (복구 단어)를 이용하여 동일한 계정(개인 키)을 디센트 지갑에 생성할 수 있음을 의미합니다.**&#x20;

* 바이낸스 스마트체인 (BSC - BNB)
* 비트코인 캐시 (BCH)&#x20;
* 코스모스 (ATOM)&#x20;
* 대시 (DASH)&#x20;
* 도지코인 (DOGE)&#x20;
* 이더리움 (ETH)&#x20;
* 이더리움 클래식 (ETC) - 디센트 지갑에서 계정추가 시 '<mark style="background-color:blue;">Ethereum Classic - Legacy</mark>'를 선택하세요.&#x20;
* 호라이젠 (ZEN)&#x20;
* 폴리곤 (MATIC)&#x20;
* 솔라나 (SOL)&#x20;
* 스텔라 (XLM)&#x20;
* 리플 (XRP)&#x20;
* 지캐시 (ZEC)&#x20;
* 트론 (TRX)

### 토큰 자산 복구하기 (예: ERC20, BEP20, TRC10, 등) <a href="#how-to-recover-token-assets-ie-erc20-bep20-trc10-...etc" id="how-to-recover-token-assets-ie-erc20-bep20-trc10-...etc"></a>

렛저 지갑에서 토큰 자산도 보유했을 가능성이 있습니다. 토큰 자산이란 Ethereum, Binance Smart Chain, Tron, Polygon 등과 같은 EVM 호환 네트워크에 존재하는 스마트 컨트랙트를 통해 블록체인 프로젝트(서비스 제공자)가 직접발행한 디지털 자산입니다.

각 EVM 호환 네트워크에는 토큰 자산에 대한 표준이 있으며 토큰 표준명을 알고있다면 어떤 네트워크에서 발행된 토큰자산인지 쉽게 구별할 수 있습니다. 예를들자면 이더리움 네크워크에서 발행된 토큰의 경우 '**ERC20**'과 같이 표시되며 바이낸스 스마트 체인 네트워크에 있는 토큰은 '**BEP20**', 트론 네트워크의 토큰은 '**TRC10**' 및 '**TRC20**', 폴리곤 네트워크의 토큰은 '**Polygon-ERC20**'과 같이 표시되어 있습니다.

예를 들어 렛저 지갑에 **ETH** 코인과 **USDT** 토큰(ERC20)을 보관하고 있다고 가정해 보겠습니다. 이 자산을 복구하려면 디센트 지갑에 2개의 계정을 추가해야 합니다. 먼저 이더리움 계정을 추가하여 ETH 코인을 복구합니다. 다음으로 생성된 이더리움 계정과 연결되는 USDT(ERC20) 계정을 추가하면 해당 계정에서 보유한 USDT 토큰이 나타납니다. &#x20;

디센트 지갑에서 지원(나열)된 디지털 자산은 아래 링크를 통해 쉽게 검색하실 수 있습니다.

[https://www.dcentwallet.com/ko/supportedcoin](https://www.dcentwallet.com/ko/supportedcoin)

찾고 있는 토큰 자산이 목록에 표시되지 않는 경우 사용자는 직접 해당 계정을 커스텀 토큰 계정으로 수동으로 추가할 수도 있습니다. 자세한 지침은 아래 가이드를 참조하세요.

{% content-ref url="../../mobile-app/create-account/how-to-add-a-custom-token-account.md" %}
[how-to-add-a-custom-token-account.md](../../mobile-app/create-account/how-to-add-a-custom-token-account.md)
{% endcontent-ref %}
