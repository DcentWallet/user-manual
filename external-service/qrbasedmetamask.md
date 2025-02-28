# Connect with MetaMask (QR-based)

![D'CENT Wallet - MetaMask integration](<../.gitbook/assets/image (255).png>)

MetaMask supports **EVM-compatible blockchains** (those that run **smart contracts**) and is widely used across various **DApp platforms**. In addition to its built-in accounts, MetaMask also supports a **QR-based protocol** for integrating with **hardware wallets**.

The **D'CENT app** utilizes this **QR-based protocol** to enable seamless integration between **D'CENT accounts (EVM-compatible)** and **MetaMask**.

## Download and Install MetaMask

First, download the MetaMask Chrome extension from ([https://metamask.io/download/](https://metamask.io/download/)) and follow its instructions to install.

<div align="left"><figure><img src="../.gitbook/assets/메타마스크-01.png" alt="" width="375"><figcaption></figcaption></figure></div>

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

### \[Step 1] Preparing to connect with MetaMask in the D’CENT App

<div align="left"><figure><img src="../.gitbook/assets/메타마스크-02.png" alt=""><figcaption></figcaption></figure></div>

**1.** After running the D’CENT App, enter the **Discovery** tab.

{% hint style="info" %}
_If you do not have an EVM account, please refer to user guide_ [_‘How to create a coin account’_](https://userguide.dcentwallet.com/mobile-app/create-account) _to create an account and use it._
{% endhint %}

**2.** Select MetaMask Integration from the list.

**3.** Tap on **Go** button.

<div align="left"><figure><img src="../.gitbook/assets/메타마스크-03.png" alt=""><figcaption></figcaption></figure></div>

**4.** On the MetaMask integration screen, click on **Connect Metamask account** button.

**5.** Select the account to be linked from the account selection list and click on **Connect** button.

**6.** After confirming that the QR code is generated, Proceed to **\[Step 2]**.

{% hint style="danger" %}
**DO NOT** disclose QR code to others.
{% endhint %}

### \[Step 2] Connect the D'CENT Wallet by scanning the QR code on your computer

<div align="left"><figure><img src="../.gitbook/assets/메타마스크-04.png" alt=""><figcaption></figcaption></figure></div>

**1.** On the **MetaMask main screen**, click the **Account** button at the top center.

**2.** Select **Add Account or Hardware Wallet**, then click **Add Hardware Wallet**.

<div align="left"><figure><img src="../.gitbook/assets/메타마스크-05.png" alt=""><figcaption></figcaption></figure></div>

**3.** After selecting **QR-based**, click the **Continue** button at the bottom.

**4.** It switches to the QR code scanning page.

<div align="left"><figure><img src="../.gitbook/assets/메타마스크-06.png" alt=""><figcaption></figcaption></figure></div>

**5.** Scan the QR code prepared in **\[Step 1]** using the camera on your computer.

**6.** When the QR code scan is completed normally, it will be converted to the account selection page.

<figure><img src="../.gitbook/assets/그림5 (3) (1).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
If the camera on your computer is having difficulty reading the QR code, **please try again after adjusting the screen brightness to max on your phone.**
{% endhint %}

<div align="left"><figure><img src="../.gitbook/assets/메타마스크-07.png" alt=""><figcaption></figcaption></figure></div>

**7.** On the account selection page, select **First account** and click **Unlock**.

_(In the case of a D’CENT account, it doesn’t matter which account you choose because all the accounts shown in the QR scan list are the same.)_

**8.** You can check the page where the account of the D’CENT wallet and the MetaMask are linked.

## Example of how to send ETH using MetaMask

{% embed url="https://www.youtube.com/watch?v=9iFz4mGvAyk" %}

### \[Step 1] Create ETH transaction with MetaMask

<div align="left"><figure><img src="../.gitbook/assets/메타마스크-08.png" alt=""><figcaption></figcaption></figure></div>

**1.** On the **MetaMask main screen**, click the **Send** button.

**2.** Enter the recipient’s **wallet address**, then click **Continue** button.

<figure><img src="../.gitbook/assets/메타마스크-09.png" alt=""><figcaption></figcaption></figure>

**3.** Input the **amount** you wish to send, then click **Continue** button and review the transaction details. Click **Confirm** to proceed. _(You can adjust the transaction fee limit by selecting the "Edit" option.)_

**4.** The screen will switch to a **QR code format** for the **signature request**.



### \[Step 2] Create a signature for the transaction using the D’CENT App

<div align="left"><figure><img src="../.gitbook/assets/메타마스크-10.png" alt=""><figcaption></figcaption></figure></div>

There are **two ways** to scan the **signature request QR code**:

**1.** From D'CENT App, go to the **Discovery tab** and Click on **Metamask QR Scan** button.

**2.** Alternatively, tap the **QR Scan** button in the **top left corner** of the **Discovery** tab.

<div align="left"><figure><img src="../.gitbook/assets/메타마스크-11.png" alt=""><figcaption></figcaption></figure></div>

**3.** When the **QR scanning screen** appears, scan the **signature request QR code** generated in **\[Step 1]**.

**4.** Verify the **recipient address**, then tap **Continue**.

**5.** Check if the transaction details match the request from **MetaMask**, then tap **Sign**.

<div align="left"><figure><img src="../.gitbook/assets/메타마스크-12.png" alt=""><figcaption></figcaption></figure></div>

**6.** If you are using a **biometric cold wallet**, carefully review the displayed information once more. If everything is correct, press **OK**, then enter your **fingerprint or PIN**.

**7.** If you are using an **app wallet**, enter the **6-digit password** you set when you first launched the app.

<div align="left"><figure><img src="../.gitbook/assets/메타마스크-13.png" alt="" width="389"><figcaption></figcaption></figure></div>

**8.** After signing, you can check the signature in QR code format.

### \[Step 3] Sending signed data to MetaMask

<div align="left"><figure><img src="../.gitbook/assets/메타마스크-14.png" alt=""><figcaption></figcaption></figure></div>

**1.** Click the **Get Signature** button on the signature request page completed in **\[Step 1]**.

**2.** Scan the QR code prepared in **\[Step 2]** using the camera on your computer.

<div align="left"><figure><img src="../.gitbook/assets/메타마스크-15.png" alt="" width="375"><figcaption></figcaption></figure></div>

**3.** Once the **QR code scan** is completed, go to the **Activity** tab in **MetaMask** to view the transaction details.
