# 모바일 앱과 콜드월렛 동기화

모바일 앱과 콜드월렛이 연결되면 동기화가 자동으로 진행됩니다.&#x20;

모바일 앱과 콜드월렛의 연결 방법이 궁금하다면 다음 항목을 참고하세요.

{% content-ref url="android-connect/" %}
[android-connect](android-connect/)
{% endcontent-ref %}

{% content-ref url="iphone-connect.md" %}
[iphone-connect.md](iphone-connect.md)
{% endcontent-ref %}

## 동기화 절차 <a href="#synchronization-process" id="synchronization-process"></a>

동기화는 콜드월렛의 정보와 모바일 앱의 정보를 일치시키기 위한 작업입니다. 콜드월렛에 저장된 계정 정보를 조회하여 모바일 앱 계정 정보에 반영합니다. 동기화는 다음의 절차를 따라 진행됩니다.

### 기존 동기화 정보 확인 <a href="#verify-previously-synchronized-information" id="verify-previously-synchronized-information"></a>

이미 콜드월렛과 동기화한 이력이 있는지 여부를 확인합니다. 연결된 콜드월렛과 동기화한 이력이 없다면 계정 정보 동기화 과정에서 콜드월렛의 주소를 조회하여 모바일 앱에 자동으로 계정이 추가됩니다.

### 계정 정보 동기화 <a href="#synchronize-account-information" id="synchronize-account-information"></a>

1\) 콜드월렛의 계정 정보를 조회하여 모바일 앱에 등록되어 있는 계정 정보와 비교합니다.

2\) 콜드월렛의 계정 정보 중 모바일 앱에 등록되지 않은 계정을 생성합니다.

3\) 콜드월렛에 계정 정보가 있다면 모바일 앱을 삭제 후 새로 설치하더라도 기존에 사용하던 계정 정보를 복구할 수 있습니다.
