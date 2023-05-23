---
description: 오입금한 자산이 이더리움 기반인지 클레이튼 기반인지 확인하는 방법
---

# 전송한 자산의 네트워크 확인

## 디센트 지갑 지원 코인 리스트에서 확인

디센트의 지원 코인 리스트에서 오전송한 자산을 검색하여 이더리움 기반의 자산인지 클레이튼 기반의 자산인지 확인할 수 있습니다.&#x20;

디센트 지원 코인 리스트 : [https://dcentwallet.com/SupportedCoin](https://dcentwallet.com/SupportedCoin)

* "ERC20"으로 표시된 경우 : 이더리움 기반 자산
* "KCT"로 표시된 경우 : 클레이튼 기반 자산

예를들어 "orbit chain"으로 검색한 경우 ORC와 KORC가 검색되는데, ERC20으로 표시된 "Orbit Chain (ORC)"는 이더리움 기반 자산이며, KCT로 표시된 "Orbit Bridge Klaytn Orbit Chain (KORC)"는 클레이튼 기반 자산입니다.

<div align="left">

<img src="../.gitbook/assets/image (226).png" alt="">

</div>

## 블록 익스플로러에서 트랜잭션 ID (TXID) 검색

좀더 정확하게 확인해볼 수 있는 방법으로는 블록 익스플로러에서 트랜잭션 ID를 검색해보는 방법이 있습니다. 블록 익스플로러는 블록체인에 기록된 정보를 조회할 수 있는 사이트입니다.

보낸 지갑의 송금 내역을 보면 트랜잭션 ID(혹은 TXID)를 확인하실 수 있습니다. 트랜잭션 ID를 블록 익스플로러에서 검색하여 오전송된 자산이 어느 블록체인 기반 자산인지 확인할 수 있습니다.

* 이더리움 블록 익스플로러 : [https://etherscan.io/](https://etherscan.io/)
* 클레이튼 블록 익스플로러 : [https://scope.klaytn.com/](https://scope.klaytn.com/)

트랜잭션 ID를 이더리움 블록 익스플로러에서 검색해서 조회가 되는 경우 오전송한 자산은 이더리움 기반 자산입니다. 반대로 트랜잭션 ID를 클레이튼 블록 익스플로러에서 검색하여 조회가 되는 경우에는 클레이튼 기반 자산입니다.

## 오전송된 자산 복구하기

이더리움 기반 자산을 오전송한 경우에는 다음 가이드를 참고하세요.

{% content-ref url="ethereum-to-klaytn.md" %}
[ethereum-to-klaytn.md](ethereum-to-klaytn.md)
{% endcontent-ref %}

클레이튼 기반 자산을 오전송한 경우에는 다음 가이드를 참고하세요.

{% content-ref url="klaytn-to-ethereum.md" %}
[klaytn-to-ethereum.md](klaytn-to-ethereum.md)
{% endcontent-ref %}

{% hint style="danger" %}
**오입금 문제를 해결하면서 발생할 수 있는모든 결과의 책임은 사용자에게 있습니다. 이 기능을 사용하시기 전에 관련된 내용을 충분히 이해하시고 사용하시기 바랍니다. 잘못 사용하는 경우 오송금한 자산을 영구적으로 찾지 못할 수 있습니다.**
{% endhint %}
