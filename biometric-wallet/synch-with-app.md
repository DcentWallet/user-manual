# \[번역필요\] Synchronizing the Biometric Wallet with the Mobile App

When the Biometric Wallet and the Mobile App are connected, synchronization will start automatically. 

Please refer to the following sections on how to connect the Biometric Wallet with the Mobile App.

{% page-ref page="android-connect/" %}

{% page-ref page="iphone-connect.md" %}

## Synchronization process

The purpose of synchronization is to hold the same correct information between the Biometric Wallet and the mobile app. Following processes will occur during the synchronization:

### Verify previously synchronized information

이미 콜드월렛과 동기화한 이력이 있는지 여부를 확인합니다. 연결된 콜드월렛과 동기화한 이력이 없다면 계정 정보 동기화 과정에서 콜드월렛의 주소를 조회하여 계정을 생성하는 과정이 추가로 진행됩니다.

### Synchronize account information

1\) 콜드월렛의 계정 정보를 조회하여 모바일 앱에 등록되어 있는 계정 정보와 비교합니다.

2\) 콜드월렛의 계정 정보 중 모바일 앱에 등록되지 않은 계정을 생성합니다.

콜드월렛에 계정 정보가 있다면 모바일 앱을 삭제 후 새로 설치하더라도 기존에 사용하던 계정 정보를 복구할 수 있습니다.

3\) 계정의 잔액 정보를 확인해서 잔액이 업데이트되었다면 앱의 계정 정보와 콜드월렛의 계정 잔액 정보를 업데이트합니다.

