# Connect with Android phone

## Mobile App Download <a href="#download-app" id="download-app"></a>

You can download the D'CENT Mobile App by clicking on this [**link**](https://play.google.com/store/apps/details?id=com.kr.iotrust.dcent.wallet).

<div align="left"><figure><img src="../../.gitbook/assets/image (270).png" alt="" width="278"><figcaption></figcaption></figure></div>

## Mobile App basic setting <a href="#basic-setup-for-mobile-app" id="basic-setup-for-mobile-app"></a>

### Select Wallet mode <a href="#select-wallet-mode" id="select-wallet-mode"></a>

If you are launching the mobile app for the first time, you will need to configure the basic settings and select a wallet mode. Select **"Create Wallet"**, then choose **"Biometric Wallet"**.

<div align="left"><figure><img src="../../.gitbook/assets/초기설정-eng.png" alt="" width="563"><figcaption></figcaption></figure></div>

You can change the **wallet mode** at any time from the **Settings** tab in the mobile app.\
If you are using a **biometric cold wallet**, make sure to set the wallet mode to **"Biometric"** in the mobile app.

{% hint style="info" %}
**How to Change Wallet Mode**

Go to **Settings** tab > Select **Change Wallet Mode >** Choose **Biometric**
{% endhint %}

### **App Password Registration**

To protect your **D'CENT mobile app**, you must set a **6-digit password**. This **app password** will be required **every time you launch the D'CENT mobile app**, so be sure to remember it.

<div align="left"><figure><img src="../../.gitbook/assets/2 (7).jpg" alt=""><figcaption></figcaption></figure></div>

{% hint style="info" %}
You can change your **app password** later through the app [**Settings menu**](../../mobile-app/mobile-app-setting-menu/)**.**

In addition to the app password, you can also **enable fingerprint recognition** for added security.
{% endhint %}

### **Mobile App Permission Settings**

A **permission request popup** will appear when connecting with the **D'CENT Biometric Wallet**. Tap **"Allow"** to enable synchronization with your **cold wallet**.

If you **do not grant permissions**, the app **will not be able to sync with the cold wallet**, restricting its functionality. Please make sure to **allow the required permissions** for proper use.

<div align="left"><figure><img src="../../.gitbook/assets/권한설정-eng (1).png" alt="" width="386"><figcaption></figcaption></figure></div>

If the **permission popup does not appear**, you can manually enable app permissions by following the steps shown in the image below.

<div align="left"><figure><img src="../../.gitbook/assets/4 (3).jpg" alt=""><figcaption></figcaption></figure></div>

## Bluetooth pairing with Cold Wallet

To use the **cold wallet** with the **mobile app**, **Bluetooth pairing** is required. This pairing process **only needs to be done once during the initial setup**.

{% hint style="info" %}
If you prefer **not to use Bluetooth**, you can also connect your **cold wallet to an Android phone** using an **OTG cable**. For detailed instructions, **please refer to** [**this guide**](android-otg.md).
{% endhint %}

### Step 1 : Preparing for Cold Wallet Pairing

<div align="left"><figure><img src="../../.gitbook/assets/그림1 (9).png" alt="" width="375"><figcaption></figcaption></figure></div>

**1) Turn on the cold wallet**, authenticate using your **fingerprint or PIN**, then navigate to the **"Settings"** menu and press **"OK"** button.

**2) Select the "Bluetooth" menu** and press  **"OK"** button.

<div align="left"><figure><img src="../../.gitbook/assets/그림2 (10).png" alt="" width="375"><figcaption></figcaption></figure></div>

**3)** Choose **"Android**" menu and press  **"OK"** button.

**4)** On the **cold wallet screen**, the message **"Connecting..."** will be displayed along with the **Device ID** and **Bluetooth password**.

The **D'CENT Device ID** is displayed in the format **D'CENT-iD-\<numbers or letters>**. The **Bluetooth password** is shown as a **6-digit number**.

If the **blue light blinks** at the **top-right corner** of the cold wallet, it indicates that the device is functioning properly.

Once the cold wallet enters **pairing mode**, you can connect it to your phone via **Bluetooth**.

### Step 2 : Connecting with the D'CENT mobile app

{% hint style="warning" %}
This guide is based on the **D'CENT mobile app version v7.5.1.**
{% endhint %}

<div align="left"><figure><img src="../../.gitbook/assets/지갑연결-eng.png" alt=""><figcaption></figcaption></figure></div>

**1)** Open the **D'CENT mobile app** and select **"Bluetooth icon"** at the top of the **"My Wallet"** tab.

**2)** A permission request popup will appear to access device's location for the D'CENT mobile app. Select the **"While using the app".**&#x20;

If you **do not grant permissions**, the app **will not be able to sync with the cold wallet.** Please make sure to **allow the required permissions** for proper use.

**3)** A **"Search Device"** popup will appear, displaying the **device name** that matches the **Device ID(D'CENT-iD-\<numbers or letters>)** shown on your cold wallet screen.

{% hint style="warning" %}
If the device ID of your cold wallet does not appear in the **"Search Device"** popup, please make sure that **Bluetooth is enabled** in your Android phone’s settings. If you're unsure how to access the Bluetooth menu, please refer to [**this guide**](./#android-phone-bluetooth-settings).
{% endhint %}

<div align="left"><figure><img src="../../.gitbook/assets/지갑연결-eng02 (1).png" alt=""><figcaption></figcaption></figure></div>

**4)** When you tap the device ID, a **"Bluetooth pairing request"** popup will appear. Enter the **6-digit Bluetooth password** shown on the cold wallet screen.

{% hint style="warning" %}
When prompted to enter a PIN for Bluetooth pairing, **do not enter "0000" or "1234"** as shown in some examples. You must enter the **6-digit password displayed on your cold wallet screen**.
{% endhint %}

**5)** Once you enter the **Bluetooth password** and the connection is complete, the **D'CENT mobile app** will automatically **synchronize** with your **cold wallet**. The app will **automatically start syncing** with the cold wallet, which may take a few seconds.

**6)** When synchronization is complete:

* A **connection indicator** will appear in the **top** of the **mobile app**.
* A **blue Bluetooth connection light** will stay turned on in the **top right corner** of the **cold wallet**.



Now, you can tap the **"Add Account"** button to add the necessary **coin accounts**. For detailed instructions on **adding coin accounts**, click [**here**](../../mobile-app/create-account/).



If you're having trouble connecting the cold wallet, please refer to the **Troubleshooting Guide** below.

{% content-ref url="troubleshooting-guide-android-bluetooth-error.md" %}
[troubleshooting-guide-android-bluetooth-error.md](troubleshooting-guide-android-bluetooth-error.md)
{% endcontent-ref %}
