# Connect with MetaMask (QR-based)

![D'CENT Wallet - MetaMask integration](<../.gitbook/assets/image (255).png>)

The MetaMask is a wallet used in various DApp sites by supporting EVM blockchains. In addition to its own account, the MetaMask supports a QR-based protocol for linking with accounts in hardware wallets.

The D’CENT App provides a function to link D’CENT accounts (EVM) with Metamask using the QR-based protocol.

## Download and Install MetaMask

First, download the [MetaMask Chrome extension](https://metamask.io/download/) from ([https://metamask.io/download/](https://metamask.io/download/)) and follow its instructions to install.

<img src="../.gitbook/assets/image (246).png" alt="" data-size="original">

## How to connect D’CENT Wallet with MetaMask

{% hint style="danger" %}
This function is supported only in **Biometric Wallet** and **App Wallet(Software)** mode. Minimum supported version

* **Biometric Wallet** firmware version: **2.19.7 or higher**
* **D’CENT App** version: **Android (5.16.1 or higher) / iOS (5.16.2 or higher)**&#x20;
{% endhint %}

{% hint style="danger" %}
The QR-based protocol supported by the MetaMask can only be used when a camera(webcam) is installed on the computer.

If you use an external camera device, please check if the camera supports the **auto focuing and QR code scanning function.**
{% endhint %}

{% embed url="https://youtu.be/JaUyBXWZ8Pw" %}

### \[Step 1] Preparing to connect with MetaMask in the D’CENT App

![](<../.gitbook/assets/image (247).png>)



**a)** After running the D’CENT App, enter the **Discovery** tab.

{% hint style="info" %}
_If you do not have an EVM account, please refer to user guide_ [_‘How to create a coin account’_](https://userguide.dcentwallet.com/mobile-app/create-account) _to create an account and use it._
{% endhint %}

**b)** Select MetaMask Integration from the list or type ([https://qrbase.dcentwallet.com](https://qrbase.dcentwallet.com)).

**c)** Click on **Go** button.

![](<../.gitbook/assets/image (243).png>)



**d)** On the MetaMask integration screen, click on **Connect Metamask account** button.

**e)** Select the account to be linked from the account selection list and click on **Connect** button.

**f)** After confirming that the QR code is generated, Proceed to **\[Step 2]**.

{% hint style="danger" %}
**DO NOT** disclose QR code to others.
{% endhint %}

### \[Step 2] Connect the D'CENT Wallet by scanning the QR code on your computer

![](<../.gitbook/assets/image (248).png>)

**a)** Click on the **Account icon** at the top right of the MetaMask main page.

**b)** Click on **Connect Hardware Wallet** button.

![](<../.gitbook/assets/image (242).png>)

**c)** After selecting **QR-based**, click the **Continue** button at the bottom.

**d)** It switches to the QR code scanning page.

![](<../.gitbook/assets/image (244).png>)

**e)** Scan the QR code prepared in **\[Step 1]** using the camera on your computer.

**f)** When the QR code scan is completed normally, it will be converted to the account selection page.

<figure><img src="../.gitbook/assets/그림5 (3) (1).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
If the camera on your computer is having difficulty reading the QR code, **please try again after adjusting the screen brightness to max on your phone.**
{% endhint %}



![](<../.gitbook/assets/image (257).png>)

**g)** On the account selection page, select **First account** and click **Unlock**.

_(In the case of a D’CENT account, it doesn’t matter which account you choose because all the accounts shown in the QR scan list are the same.)_

**h)** You can check the page where the account of the D’CENT wallet and the MetaMask are linked.

## Example of how to send ETH using MetaMask

{% embed url="https://www.youtube.com/watch?v=9iFz4mGvAyk" %}

### \[Step 1] Create ETH transaction with MetaMask

![](<../.gitbook/assets/image (251).png>)

**a)** On the main page of MetaMask, click the button in the upper right corner.

**b)** Select the D'CENT Wallet account(**DCENT1**) linked to the MetaMask.

![](<../.gitbook/assets/그림1 (2).png>)

**c)** Click the **Send** button in the center of the page.

**d)** Enter the sending address, set the desired amount, and click **Next**.

<figure><img src="../.gitbook/assets/그림1 (1) (2).png" alt=""><figcaption></figcaption></figure>

**e)** After checking the transaction details, click the **Confirm** button.

(_You can adjust the transaction fee to the desired limit by selecting **Advanced→Edit** Options_)

**f)** It switches to the signature request page in QR code format.

### \[Step 2] Create a signature for the transaction using the D’CENT App

![](<../.gitbook/assets/image (254).png>)

**a)** Access the Metamask link ([https://qrbase.dcentwallet.com](https://qrbase.dcentwallet.com)). (There are two ways to scan the signature request QR.)

**a-i)** From D'CENT App, go to the **Discovery tab** and Click on **Metamask QR Scan** button.

**a-ii)** Or, click the **QR Scan** button at the top left of the Discovery tab.

<figure><img src="../.gitbook/assets/그림2 (5).png" alt=""><figcaption></figcaption></figure>

**b)** Scan the signature request QR code generated in **\[Step 1]**.

**c)** After confirming that the transaction information requested by MetaMask is the same, click the **Signing** button.

![](<../.gitbook/assets/image (252).png>)



**d)** Proceed to sign using your password or fingerprint.

**d-i)** In the case of a biometric wallet, check the information displayed on the screen once more, and if the information is correct, press the **OK** button and enter your **fingerprint** or **PIN**.

**d-ii)** In the case of App Wallet, enter the **password (6 digits)** registered at the first launch.

![](<../.gitbook/assets/그림3 (1) (2).png>)

**e)** After signing, you can check the signature in QR code format.

### \[Step 3] Sending signed data to MetaMask

<figure><img src="../.gitbook/assets/그림4 (5) (1).png" alt=""><figcaption></figcaption></figure>

**a)** Click the **Get Signature** button on the signature request page completed in **\[Step 1]**.

**b)** Scan the QR code prepared in **\[Step 2]** using the camera on your computer.

![](<../.gitbook/assets/그림4 (2) (1).png>)

**c)** After scanning the QR code, you can check the transaction history in the Activity tab.
