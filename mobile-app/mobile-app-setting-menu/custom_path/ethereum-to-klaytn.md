# 클레이튼 주소로 오전송된 이더리움 기반 자산 복구하는 방법

{% hint style="danger" %}
**\[사용자 정의 경로 계정\] 기능을 사용하는 경우 이에 따른 모든 결과의 책임은 사용자에게 있습니다. 이 기능을 사용하시기 전에 관련된 내용을 충분히 이해하시고 사용하시기 바랍니다. 잘못사용하는 경우 오송금한 자산을 영구적으로 찾지 못할 수 있습니다.**
{% endhint %}

{% hint style="warning" %}
**아래 설명은 이더리움의 오르빗체인\(ORC\)를 클레이튼의 \(KORC\) 주소로 오전송 하였을 때를 가정하여 작성된 가이드입니다.** 
{% endhint %}

**Step 1\)** 클레이튼 주소 복사

클레이튼 계정에서 ‘**받기**’ 버튼을 누르고 ‘**주소 복사**’를 눌러줍니다.

![](https://cdn-images-1.medium.com/max/800/1*czMiNHCS56-nrWFh30xX4Q.png)

**Step 2\)** 복사한 클레이튼 주소를 이더스캔\([https://etherscan.io](https://etherscan.io)\)에서 검색

![](https://cdn-images-1.medium.com/max/800/1*TE9WkxWHAxhkGekB5dMVig.png)

위에 처럼 **\[Token\] 탭**에서 오전송된 자산이 보인다면, 해당 자산은 본래 이더리움 주소로 복원 할 수 있습니다.

**Step 3\)** \[사용자 정의 경로 계정\] 옵션 활성화

![](https://cdn-images-1.medium.com/max/800/1*HYmxDf23e44kq9OO55Napg.png)

**Step 4\)** 토큰 계정 숨기기

우선 기존 이더리움 계정과 연결된 ORC 토큰 계정이 이미 존재한다면 **'숨기기'**를 합니다. 생성된 계정이 없으면, 안 숨기셔도 됩니다.

![](https://cdn-images-1.medium.com/max/800/1*gaWKmhX2xPCZFJF9nco33A.png)

**Step 5\)** \[사용자 정의 경로 계정\] **코인 계정** 추가 하기

검색란에 ‘**custom**’을 입력하고 **이더리움**을 선택합니다.

![](https://cdn-images-1.medium.com/max/800/1*DedoXirW21DLQ9br6yuErw.png)

정상적으로 \[사용자 정의 경로 계정\] 이더리움 계정이 추가되면 아래와 같이 Account탭에 이더리움 계정이 하나 더 추가된것을 확인할 수 있습니다.

![](https://cdn-images-1.medium.com/max/800/1*27GKxqYKkB35lwMLJMiQ5A.png)

**Step 6\)** \[사용자 정의 경로 계정\] **토큰 계정** 추가 하기

검색란에 ‘**orc**’ 검색하고 이더리움 블록체인 기반의 토큰 계정 \(ERC20\) 규격을 선택합니다. 연결되는 수수료 계정은 ‘**ETH-CUSTOM-01’**을 선택합니다.

![](https://cdn-images-1.medium.com/max/800/1*buTm1Dl-tPUOGrs4xlzCPw.png)

**Step 7\)** \[사용자 정의 경로 계정\] 계정으로 수수료 목적 코인 전송

이더리움 블록체인의 \(ERC20 규격\) 토큰을 전송하기 위해서는 이더리움\(ETH\)이 수수료로 사용됩니다.

안정적인 전송을 위해서 0.05 ETH 이상의 이더리움을 \[사용자 정의 경로 계정\]에 받습니다.

이더리움을 받았다면 다음 단계로 넘어 갑니다.

**Step 8\)** 오전송한 토큰을 본래의 주소로 전송

아래와 같이 본래 주소를 복사 합니다.

![](https://cdn-images-1.medium.com/max/800/1*zXZpJ6QeVvkajJeK9NX__w.png)

ORC 토큰 계정에서 ‘**보내기**’를 누르고 복사한 주소를 ‘**붙여넣기’** 합니다.

![](https://cdn-images-1.medium.com/max/800/1*A0qhA0iFZ7nw3807Jn1NSg.png)

**‘전액’**을 눌러 복원할 토큰을 모두 전송 합니다.

![](https://cdn-images-1.medium.com/max/800/1*H8DLw5jFQ_DEstlQ7g-sag.png)

복원할 토큰을 전송 후, 해당 거래가 완료 될 때까지 기다립니다. 거래가 완료 되면 다음 단계로 넘어갑니다.

**Step 9\)** \[사용자 정의 경로 계정\]의 수수료로 사용하고 남은 이더리움을 본래 계정으로 전송

아래와 같이 본래 주소를 ‘**붙여넣기**’ 하고 전액을 전송합니다.

![](https://cdn-images-1.medium.com/max/800/1*cxoFh8fXyL0KRtBxFx_z-g.png)

이더리움 전송 거래가 완료될 때까지 기다립니다. 거래가 완료되면 다음으로 넘어갑니다.

**Step 10\)** \[사용자 정의 경로 계정\] 계정 숨기기

복원을 목적으로 만든 \[사용자 정의 경로 계정\] 계정을 모두 삭제 합니다. 

![](https://cdn-images-1.medium.com/max/800/1*1hsMREm591WM57Lbhpr5EQ.png)

**Step 11\)** 복원된 토큰 계정 만들기

![](https://cdn-images-1.medium.com/max/800/1*6yzLp0MSvceaBBdNXr-tRg.png)

**Step 12\)** 복원 마무리

복원이 끝나면, 반드시 사용자 정의 경로 계정 옵션을 비활성화 해주세요.

![](https://cdn-images-1.medium.com/max/800/1*pGt0yyeEYxIN-tjTJeD0wg.png)

{% hint style="info" %}
추가로 블록체인은 한번 거래가 성사 되면, 이를 되돌릴 방법이 없습니다.

디센트 처럼 탈중앙화가 아닌 중앙화 되어있는 지갑이나, 스마트컨트랙트로 구성된 지갑에 오전송 했을 경우에는 오전송 된 자산을 영영 찾을 방법이 없을 수 있습니다. 암호화폐 자산을 전송 시에는 블록체인 네트워크 선택에 각별한 주의 부탁 드립니다.
{% endhint %}

