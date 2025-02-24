# 소프트웨어 월렛

## 앱 월렛 백업 <a href="#app-wallet-backup" id="app-wallet-backup"></a>

앱 월렛을 처음 사용하면 앱 월렛의 백업(24개 니모닉 코드 백업) 필요하다는 문구가 표시됩니다. \
디센트 모바일 앱의 "My Wallet" 탭, 앱 월렛에서 계정을 추가할 때, 그리고 "Setting" 탭에서 앱 월렛 백업이 필요하다는 안내가 표시됩니다.

따라서 **반드시 앱 월렛의 24개 니모닉 코드를 백업하여 안전하게 보관하셔야 합니다.**

{% hint style="danger" %}
니모닉 코드를 백업해 놓지 않은 상태에서 디센트 모바일 앱을 삭제하거나 모바일 폰을 분실하신 경우, 소프트웨어 지갑에 있는 모든 코인을 잃게 됩니다.
{% endhint %}

**앱 월렛을 백업하는 방법은 다음과 같습니다.**

1\) My wallet 탭의 상단 배너에서 백업하기 버튼을 누르거나, Settings 탭에서 앱 월렛 백업 버튼을 눌러 백업화면으로 이동합니다.

<figure><img src="../../../.gitbook/assets/1 (31).jpg" alt=""><figcaption></figcaption></figure>

2\) 모바일 앱의 6자리 비밀번호를 입력해주세요.

3\) 백업 전 주의사항을 읽은 후 **"내용을 확인했습니다"** 를 체크한 뒤 **"백업 시작하기"**&#xB97C; 누릅니다.

4\) 민감 정보에 대한 경고 팝업을 확인한 후 **"내용을 확인했습니다"** 버튼을 누릅니다.

<figure><img src="../../../.gitbook/assets/2 (24).jpg" alt=""><figcaption></figcaption></figure>

5\) 화면에 표시된 **24개의 니모닉 코드를 정확하게 순서대로 적어주세요**. 또는 **"니모닉 공유"** 버튼을 눌러서 일시적으로 클립보드 등에 저장할 수있습니다. "**백업 완료하고 니모닉 검증하기"**&#xB97C; 누르고 다음으로 진행합니다.&#x20;

6\) 적어놓은 니모닉 코드를 확인하여 화면에 표시된 단어들을 선택해서 니모닉 코드를 순서대로 배열하세요.

7\) 24개 니모닉 코드를 올바르게 배열하였다면 **"완료"** 버튼을 선택합니다.

8\) 백업을 완료하였다면 **"지갑 사용하기"**&#xB97C; 눌러주세요.

<figure><img src="../../../.gitbook/assets/3 (19).jpg" alt=""><figcaption></figcaption></figure>

## 앱 월렛 복구 <a href="#recover_appwallet" id="recover_appwallet"></a>

백업했던 24개 니모닉 코드를 이용하여 기존에 사용하던 지갑을 복구할 수 있습니다.



**앱 월렛을 복구하는 방법은 다음과 같습니다.**

1\) D'CENT Manager 탭에서 "**앱 월렛 복구**"를 선택합니다.

2\) 모바일 앱의 6자리 비밀번호를 입력해주세요.

3\) 복구 전 주의사항을 읽은 후 **"내용을 확인했습니다"** 를 체크한 뒤 **"백업 시작하기"**&#xB97C; 누릅니다.

4\) 적어놓은 **24개의 니모닉 코드를 정확한 순서로 모두 입력**합니다. 또는 '**붙여넣기**' 버튼을 사용하여 클립보드에 일시적으로 저장한 정보를 붙여넣을 수 있습니다. '**복구하기**' 버튼을 누르면 복구가 진행됩니다.

<figure><img src="../../../.gitbook/assets/4 (11).jpg" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
백업해 놓은 니모닉 코드는 디센트 지문인증형 콜드월렛에서 복구할 수 있습니다. 지문인증형 콜드월렛 복구에 대한 자세한 내용은 [여기](../../../biometric-wallet/recovery/)를 참고하세요.
{% endhint %}

{% hint style="warning" %}
**지갑을 복구하였다면 기존에 사용하던 계정을 다시 추가해야 잔액을 확인할 수 있습니다.**&#x20;
{% endhint %}

### 레거시 주소 확인 <a href="#important-notes-after-recovering-your-wallet" id="important-notes-after-recovering-your-wallet"></a>

모바일 앱 버전 v5.3.1 업데이트에서 Klaytn(클레이튼), Ethereum Classic(이더리움 클래식), RSK(루트스탁)과 같이 이더리움과 같은 형식의 주소를 사용하는 자산은  계정을 생성시 이더리움 주소와 동일한 주소를 가진 계정이 생성되도록 변경되었습니다.&#x20;

자세한 내용은 아래 내용을 확인하세요.

{% content-ref url="../../../troubleshooting/notes-on-wallet-recovery.md" %}
[notes-on-wallet-recovery.md](../../../troubleshooting/notes-on-wallet-recovery.md)
{% endcontent-ref %}
