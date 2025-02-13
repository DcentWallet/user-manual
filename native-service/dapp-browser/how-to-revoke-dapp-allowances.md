# dApp 허용(권한) 철회하는 방법

암호화폐 세계의 모든 사용자에게는 “허용”(권한)의 개념을 이해하는 것이 중요합니다. 암호화폐 공간에서 허용이란 사용자를 대신하여 작업을 수행할 수 있도록 탈중앙화 애플리케이션(dApp)에 권한을 부여하는 것을 의미합니다. 그러나 관련 위험을 이해하고 이러한 권한을 효과적으로 관리하는 것이 중요합니다.

## 디앱 허용이란 무엇인가요? <a href="#what-are-dapp-allowances" id="what-are-dapp-allowances"></a>

암호화폐 영역에서 디앱 허용은 토큰을 사용하여 특정 작업을 실행할 수 있는 권한을 디앱에 부여하는 것을 의미합니다. 이 권한을 통해 토큰을 전송하거나, 새로운 토큰을 생성하거나, 사용자를 대신하여 다른 작업을 수행할 수 있습니다.

다음은 이더스캔에서 검색한 이더리움 지갑의 예시로, 허용 권한이 부여된 디앱을 보여줍니다:

<figure><img src="https://miro.medium.com/v2/resize:fit:700/1*CrUV2TZMoMSjkk5kX_00Kg.png" alt="" height="297" width="700"><figcaption></figcaption></figure>

### 확인되지 않은 허용의 위험성 인식하기 <a href="#recognizing-the-risks-of-unchecked-allowances" id="recognizing-the-risks-of-unchecked-allowances"></a>

디앱 허용 권한을 관리하지 않으면 사용자는 다양한 위험에 노출될 수 있습니다. 다음은 잠재적인 위험의 몇 가지 예입니다:

**a) 승인되지 않은 토큰 전송**: 디앱이 사용자의 허용 권한에 액세스하면 사용자의 동의 없이 토큰을 전송할 수 있으며, 이로 인해 자산이 손실되거나 도난당할 수 있습니다.

**b) 채굴 권한의 악용**: 악의적인 디앱은 허용 권한을 오용하여 사용자 명의로 새로운 토큰을 발행하여 기존 보유 자산의 가치를 떨어뜨릴 수 있습니다.

**c) 계정 취약성**: 제한 없는 디앱 액세스를 허용하면 계정의 보안이 손상되어 무단 제어 또는 조작에 취약해질 수 있습니다.

## 지갑 연결을 해제했다면 안전한가요? <a href="#am-i-safe-if-my-wallet-is-disconnected" id="am-i-safe-if-my-wallet-is-disconnected"></a>

디앱에서 지갑을 연결 해제하는 것과 승인 또는 허용을 취소하는 것의 차이점을 이해하는 것이 중요합니다. 두 프로세스는 비슷해 보이지만, 디앱에 부여된 액세스 권한과 제어 수준에 영향을 미치는 근본적인 차이점이 있습니다.

### 지갑 연결 해제와 허용 철회 비교 <a href="#disconnecting-wallet-vs-revoking-allowances" id="disconnecting-wallet-vs-revoking-allowances"></a>

지갑 연결을 디앱에서 해제하면 해당 디앱이 특정 정보에 액세스할 수 있는 권한을 취소하는 것으로, 일반적으로 공개 주소, 토큰 잔액, 과거 활동을 볼 수 있는 디앱의 권한이 취소됩니다. 지갑 연결을 해제하면 해당 디앱이 내 계정에 표시되고 상호 작용하는 것을 제한하는 데 도움이 됩니다.

승인 또는 허용을 철회하는 것은 지갑 연결을 해제하는 것 이상의 의미가 있습니다. 허용을 철회하면 기본적으로 지갑의 콘텐츠에 대한 디앱의 액세스를 완전히 차단하는 것입니다. 즉, 디앱이 더 이상 토큰을 검색하거나 조작할 수 없다는 뜻입니다. 허용을 철회하는 것은 더 엄격한 조치로, 디앱이 자산에 접근하고 이동하는 것을 완전히 금지합니다.

**지갑 연결을 해제하면 특정 권한과 가시성이 제한되지만, 허용 철회와 동일한 수준의 보안을 보장하지는 않는다는 점에 유의해야 합니다.**

### 효과적인 허용(권한) 관리를 위한 고려 사항 <a href="#considerations-for-effective-permission-management" id="considerations-for-effective-permission-management"></a>

**a) 무단 행위 방지**: 불필요한 권한을 정기적으로 검토하고 철회함으로써 사용자를 대신하여 작업을 수행할 수 있는 디앱의 기능을 제한하여 원치 않는 거래나 토큰 오용의 위험을 줄일 수 있습니다.

**b) 토큰 무결성 보호**: 사용하지 않거나 의심스러운 디앱의 허용을 취소하면 계정과 관련된 토큰을 조작하거나 생성할 수 없으므로 토큰 포트폴리오의 무결성을 유지할 수 있습니다.

**c) 계정 보안 강화**: 적절한 허용 관리는 악의적인 디앱이 계정을 장악할 가능성을 최소화하여 개인 정보 보호, 제어 및 전반적인 보안을 유지합니다.

## 디앱 허용(권한) 철회하는 방법 <a href="#how-to-revoke-dapp-approval" id="how-to-revoke-dapp-approval"></a>

경계하는 사용자들은 [Ethallowance](https://ethallowance.com/), [Etherscan](https://etherscan.io/tokenapprovalchecker), [Cointool](https://cointool.app/approve/eth), [Revoke](https://revoke.cash/), [Unrekt](https://app.unrekt.net/), 또는 [EverRevoke](https://everrise.com/everrevoke/)와 같은 신뢰할 수 있는 툴을 활용하여 디앱에 부여된 허용을 효율적으로 관리하고 철회할 수 있습니다.

**NOTE:** 디앱의 허용 철회는 블록체인 거래임으로 네트워크 수수료가 부과됩니다. 사용하는 철회 서비스에 따라 추가적인 수수료 비용이 부과될 가능성이 있습니다.

### 이더스캔(이더리움)을 사용한 허용 철회 예시: <a href="#example-of-revoking-allowance-using-etherscan" id="example-of-revoking-allowance-using-etherscan"></a>

<figure><img src="https://miro.medium.com/v2/resize:fit:700/1*fvSKkEXuSzVBI19yis1l9Q.png" alt="" height="404" width="700"><figcaption><p>이더스캔 플랫폼에서 디센트 지갑을 사용하여 디앱 허용 철회하기 (1)</p></figcaption></figure>

디센트 지갑의 디스커버리 탭(디앱 브라우저)에서 이더스캔([**https://etherscan.io**](https://etherscan.io/))으로 이동하여 서비스 하위 메뉴에서 ‘토큰 허용’(Token Approvals)을 클릭합니다.

<figure><img src="https://miro.medium.com/v2/resize:fit:700/1*zp9gQt6IZPrc_k0rqtD63A.png" alt="" height="399" width="700"><figcaption><p>이더스캔 플랫폼에서 디센트 지갑을 사용하여 디앱 허용 철회하기 (2)</p></figcaption></figure>

‘웹3.0에 연결’(Connect to Web3)을 클릭하고 ‘메타마스크’를 선택해 디센트 지갑에서 지갑 연결을 트리거합니다.

<figure><img src="https://miro.medium.com/v2/resize:fit:700/1*8fYWF-ihDeFeBPf5yVIBqg.png" alt="" height="404" width="700"><figcaption><p>이더스캔 플랫폼에서 디센트 지갑을 사용하여 디앱 허용 철회하기 (3)</p></figcaption></figure>

허용이 부여된 토큰과 디앱을 확인할 수 있습니다. 파란색 ‘철회’(Revoke) 버튼을 클릭하여 해당 디앱에 부여된 허용을 철회할 수 있습니다.

### ‘Revoke’서비스를 사용하여 허용을 철회하는 예시 (멀티체인): <a href="#example-of-revoking-allowance-using-revoke" id="example-of-revoking-allowance-using-revoke"></a>

**다중 네트워크**에서 디앱을 사용하는 사용자를 위한 또 다른 훌륭한 도구는 ‘**Revoke**’(**리보크**)라는 타사 플랫폼입니다.

<figure><img src="https://miro.medium.com/v2/resize:fit:700/1*1Iadqx2eT_1QvOPI0B9Dgg.png" alt="" height="404" width="700"><figcaption><p>리보크 캐시 플랫폼에서 디센트 지갑을 사용하여 디앱 허용 철회하기 (1)</p></figcaption></figure>

디센트 지갑의 디스커버리 탭(디앱 브라우저)에서 리보크([**https://revoke.cash**](https://revoke.cash/))로 이동합니다. 메인 메뉴를 클릭하고 ‘지갑 연결’을 클릭합니다.

<figure><img src="https://miro.medium.com/v2/resize:fit:700/1*1oGJhGJKiMzSZ0OKDPhVYA.png" alt="" height="404" width="700"><figcaption><p>리보크 캐시 플랫폼에서 디센트 지갑을 사용하여 디앱 허용 철회하기 (2)</p></figcaption></figure>

‘메타마스크’를 클릭하여 디센트 지갑에서 지갑 연결을 트리거합니다.

<figure><img src="https://miro.medium.com/v2/resize:fit:700/1*iTTHJrVu-0n73MG_L37QQg.png" alt="" height="404" width="700"><figcaption><p>리보크 캐시 플랫폼에서 디센트 지갑을 사용하여 디앱 허용 철회하기 (3)</p></figcaption></figure>

지갑 연결이 완료되면 과거에 상호작용한 스마트 컨트랙트(디앱)에 부여된 토큰 자산과 허용에 대한 세부 정보를 확인할 수 있습니다. 화면을 오른쪽으로 스크롤하면 작업(Actions) 메뉴에서 ‘철회’(Revoke) 버튼을 찾을 수 있습니다.
