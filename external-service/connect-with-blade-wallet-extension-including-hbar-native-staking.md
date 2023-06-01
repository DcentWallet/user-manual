# 블레이드 지갑 연결하기 (HBAR 스테이킹 가이드)

이 문서는 사용자 친화적인 블레이드 지갑과 디센트 지문인증형 하드웨어 지갑을 함께 사용하는 방법에 대한 종합적인 가이드입니다. 연결 시 블레이드 지갑은 헤데라 에코시스템에 액세스할 수 있는 사용자 인터페이스를 제공하며, 디센트 지문인증형 지갑은 오프라인에서 개인 키를 보호하는 최고의 보안을 제공합니다.

## 요구 사항 <a href="#4bd6" id="4bd6"></a>

**1. 블레이드 지갑 확장 프로그램 설치**

블레이드 지갑과의 연동을 통해 블레이드 확장 대시보드 및 인터페이스를 사용하여 HBAR 자산을 관리하게 됩니다. 이를 위해 블레이드 [웹사이트](https://www.bladewallet.io/)에 접속하여 ‘Connect Blade Wallet’ 버튼을 누르면 블레이드 지갑의 확장 프로그램 설치를 위해 공식 크롬 앱 스토어 페이지로 이동되며 여기에서 설치할 수 있습니다.

**2. 디센트 생체인식 지갑 보유하기**\
현재 블레이드 지갑은 디센트 지문인증형 지갑과 연동이 가능합니다. 이미 디센트 지문인증형 지갑이 없는 경우 아래 링크를 통하여 구매가 가능합니다:

[지문인증형 지갑간편결제 지원 지문인증형 지갑은 EAL5+ 인증을 받은 보안 칩에 블록체인 개인키를 저장합니다. 탑재된 지문센서를 통해 입력되는 개인 지문도 보안 칩에 안전하게 저장합니다. 블루투스 인터페이스를 통해서 모바일 앱과…store-kr.dcentwallet.com](https://store-kr.dcentwallet.com/collections/frontpage/products/%EC%A7%80%EB%AC%B8%EC%9D%B8%EC%A6%9D%ED%98%95-%EC%A7%80%EA%B0%91)

**3. 디센트 브릿지 프로그램 설치**

디센트 브릿지는 디센트에서 개발한 소프트웨어로 지문인증형 지갑을 컴퓨터에 연결하여 펌웨어를 업데이트 하거나 또는 지문이증형 지갑과 블레이드 지갑과 연결하여 서로 통신이 가능하게 만드는 프로그램입니다.

## 디센트 월렛과 블레이드 월렛 연결하기 <a href="#9d18" id="9d18"></a>

위의 모든 작업을 완료하였다면 블레이드 지갑 확장 프로그램과 디센트 브리지가 컴퓨터에 올바르게 설치되있을것 입니다. 이제 디센트 지문인증형 지갑을 컴퓨터에 연결하기 위해 디센트 지갑 구매시 박스에 동봉된 USB 케이블이 필요합니다.

### 디센트 지문인증형 지갑에서 <a href="#f1d2" id="f1d2"></a>

1\. HBAR 계정 생성하기\
계정 생성 방법은 아래 튜토리얼을 참조하세요:\
[https://userguide.dcentwallet.com/v/kr/mobile-app/create-account](https://userguide.dcentwallet.com/v/kr/mobile-app/create-account)

2\. USB 케이블을 사용하여 디센트 지문인증형 지갑을 컴퓨터에 연결합니다.

### 블레이드 지갑에서 <a href="#c31a" id="c31a"></a>

1\. 브라우저에서 블레이드 지갑 확장 프로그램을 클릭합니다.

<figure><img src="https://miro.medium.com/v2/resize:fit:700/1*uM0RB1EGnpKbaL9msFcLuw.png" alt="" height="373" width="700"><figcaption></figcaption></figure>

2\. 원하는 언어를 선택하여 설정을 시작합니다.

<figure><img src="https://miro.medium.com/v2/resize:fit:700/1*zF_rpBX8zeFU64YlY7wmHA.png" alt="" height="370" width="700"><figcaption></figcaption></figure>

3\. 비밀번호를 설정해야 합니다. 안전상의 이유로 다른 플랫폼에서 사용하는 비밀번호를 사용하지 마시고 대문자, 숫자, 기호를 포함한 8자 이상의 비밀번호를 만드세요. 완료되면 ‘Advanced setup’을 클릭합니다.

<figure><img src="https://miro.medium.com/v2/resize:fit:700/1*GLLcJpzur2fjNMN_AMU8hA.png" alt="" height="375" width="700"><figcaption></figcaption></figure>

4\. 디센트 지문인증형 지갑과 연동하기 위해 ‘Hardware wallet’을 클릭합니다.

<figure><img src="https://miro.medium.com/v2/resize:fit:700/1*5cnFmfi5ApDqIwpLShv0fQ.png" alt="" height="372" width="700"><figcaption></figcaption></figure>

5\. 선택 옵션 중에 ‘D’CENT’를 클릭합니다.

<figure><img src="https://miro.medium.com/v2/resize:fit:700/1*gXYzA71bIlnjp_Z5bZbE5Q.png" alt="" height="370" width="700"><figcaption></figcaption></figure>

6\. 디센트 지갑의 HBAR 계정 정보를 읽어오기 위해 ‘Import a wallet’을 클릭합니다.

<figure><img src="https://miro.medium.com/v2/resize:fit:700/1*hg0phr7Ta1J42R1uY53SQA.png" alt="" height="376" width="700"><figcaption></figcaption></figure>

7\. 새 탭이 열리며 디센트 지문인증형 지갑을 컴퓨터에 연결하라는 메시지가 표시됩니다. ‘Next’를 클릭합니다.

<figure><img src="https://miro.medium.com/v2/resize:fit:700/1*nNES_pK3liJUEO1466ERPg.png" alt="" height="371" width="700"><figcaption></figcaption></figure>

8\. 잠시 기다리면 ‘import account’ 버튼이 활성화되며 클릭할 수 있습니다.

<figure><img src="https://miro.medium.com/v2/resize:fit:700/1*adsyQUa8i66d1_ru5KsyVA.png" alt="" height="387" width="700"><figcaption></figcaption></figure>

9\. 사용할 준비가 되었습니다! 이제 ‘Close’를 클릭하여 탭을 닫습니다.

<figure><img src="https://miro.medium.com/v2/resize:fit:700/1*z71KGjtuv26rUgO2SNB8lQ.png" alt="" height="392" width="700"><figcaption></figcaption></figure>

10\. 블레이드 지갑 확장 프로그램을 열면 디센트 지문인증형 지갑에서 읽어온 HBAR 계정을 볼 수 있습니다. 아래 이미지의 경우 이미 일부 자산을 보유하고 있습니다. 금액이 정확한지, 공개 주소가 정확한지 쉽게 다시 확인할 수 있습니다.

<figure><img src="https://miro.medium.com/v2/resize:fit:700/1*wX6QskQ0KCFuZx9pr-2PBw.png" alt="" height="391" width="700"><figcaption></figcaption></figure>

## 디센트 지갑의 HBAR을 스테이킹하는 방법 <a href="#ba2a" id="ba2a"></a>

스테이킹은 헤데라 네트워크 합의에 참여하기 위해 사용자가 보유한 HBAR을 잠그는 과정이 포함됩니다. HBAR을 스테이킹함으로써 사용자는 보상을 받고 네트워크 보안에 기여할 수 있습니다.

이를 위해서는 몇 가지 요구 사항이 있습니다:

* 디센트 지문인증형 지갑이 컴퓨터에 연결되어 있어야 합니다.
* 이전에 설명한 방식으로 블리에드에 연결한 디센트 지문인증형 지갑의 HBAR 계정이 이미 import된 상태이어야 합니다.
* 스테이킹을 시작하려면 계정에 자산이 있어야 합니다.

스테이킹하는 과정은 HBAR 계정에 보유한 전체 자산을 스테이킹하게되며 일부만 스테이킹할 수 없다는 점에 유의하시기 바랍니다. 자산의 일부만 스테이킹하려면 두 번째 HBAR계정을 디센트 지문인증형 지갑에서 생성하고 스테이킹하고자 하는 금액에 따라 HBAR을 두 개로 나눠야 합니다.

스테이킹을 시작하기 위한 최소 HBAR 금액은 없습니다. 스테이킹은 자정부터 24시간 단위로 이루어집니다. HBAR 자산은 스테이킹하는 동안에는 스테이킹을 해제할 때까지 자산을 전송할 수 없습니다.

공식 문서를 통해 HBAR 스테이킹에 대해 자세히 알아보세요: [https://docs.hedera.com/hedera/core-concepts/staking/staking](https://docs.hedera.com/hedera/core-concepts/staking/staking)

1\. 블레이드 앱을 열어보면 ‘Stake’ 버튼이 표시됩니다. (자산이 있는 경우)

<figure><img src="https://miro.medium.com/v2/resize:fit:700/1*CvfYbnntjOFIKIDZ2B7WSA.png" alt="" height="388" width="700"><figcaption></figcaption></figure>

2\. 이를 클릭하면 스테이킹할 노드를 선택하거나 기본 제안을 그대로 사용할 수 있습니다. 이는 개인적인 선택이므로 특정 노드를 권장하지 않습니다.

<figure><img src="https://miro.medium.com/v2/resize:fit:700/1*7o1NAyfH7ID5QOj_R2pglw.png" alt="" height="392" width="700"><figcaption></figcaption></figure>

3\. ‘Sign’을 클릭합니다.

<figure><img src="https://miro.medium.com/v2/resize:fit:700/1*C1t1GjeRwoildZg7kZgG_g.png" alt="" height="373" width="700"><figcaption></figcaption></figure>

4\. 최종 승인을 위해 지문인증형 지갑에 세부 정보가 표시됩니다. ‘OK’ 버튼을 클릭하면 지문을 통해 본인 인증을 할 수 있습니다.

<figure><img src="https://miro.medium.com/v2/resize:fit:633/1*XBX1y5O8agCiiXH1jiN7rQ.png" alt="" height="662" width="633"><figcaption></figcaption></figure>

5\. 거래가 완료되면 실제로 토큰이 스테이킹되고 있는지 확인할 수 있습니다.

<figure><img src="https://miro.medium.com/v2/resize:fit:700/1*4-OGQMNYNqz_oB35T_LY1Q.png" alt="" height="391" width="700"><figcaption></figcaption></figure>
