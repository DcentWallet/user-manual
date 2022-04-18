# How to use Stellar Lumens (XLM) account

## Check the Firmware version

Stellar (XLM) coin is supported on the hardware wallet installed with firmware version v2.1.0 or higher. Please refer to the link below for instructions on how to update the firmware.

{% content-ref url="../../biometric-wallet/firmware-update-from-computer/" %}
[firmware-update-from-computer](../../biometric-wallet/firmware-update-from-computer/)
{% endcontent-ref %}

## How to create a Stellar Lumen (XLM) account

If you don't have a Stellar Lumen account, create a new account. The coin name for Stellar Lumen is "Stellar (XLM)".

For more details on how to create an account, click the link below.

{% content-ref url="../../mobile-app/create-account/" %}
[create-account](../../mobile-app/create-account/)
{% endcontent-ref %}

## If you can't create a Stellar account

{% hint style="info" %}
There is a case where the Stellar account cannot be created even though the current firmware version is v2.1.0 or higher. This is because the new algorithm used by Stellar cannot be used if the firmware version installed in the product was lower than v2.0.1 when it was originally purchased.
{% endhint %}

In the event when trying to create a Stellar account from the mobile app, the search result will not display Stellar coin as an account that can be added. See the picture below.

![](../../.gitbook/assets/unable-to-create-stellar-account\_en.png)

### Solution:

You can create a Stellar wallet account after recovering the wallet using the recovery words. But first, you must perform the **device wipe** from the settings menu of the hardware wallet.&#x20;

1\) Click [here](https://userguide.dcentwallet.com/biometric-wallet/setting-menu#device-wipe) for instructions on how to initialize(device wipe) the hardware wallet.&#x20;

2\) Click [here](https://userguide.dcentwallet.com/biometric-wallet/recovery) for instructions on how to recover your wallet.

{% hint style="danger" %}
Warning! You MUST not reset(device wipe) your device if you do not have your recovery words!
{% endhint %}

## Stellar (XLM) wallet activation

After adding a Stellar (XLM) wallet from your mobile app, it will be in the **disabled** (not created on the Stellar network) state. \
\
Due to Stellar's policy, **a minimum of 1XLM must be transferred to the Stellar address to activate the account on the Stellar network**. Depending on the exchange services, transferring fund to an inactive XLM account address may be restricted. \
\
In addition, **1XLM in the account will be permanently locked-up**. For example, if you have 100XLM in your account after creating your wallet, you can only transfer 99XLM (including fee). As shown in the figure, the remaining balance of 1XLM cannot be sent to another account even when if you try to send the maximum amount.

![](../../.gitbook/assets/xlm-send-all\_en.jpg)

{% hint style="info" %}
In some cases, the lock-up amount may be different. See the link below for more details. [https://www.stellar.org/developers/guides/concepts/fees.html#minimum-account-balance](https://www.stellar.org/developers/guides/concepts/fees.html#minimum-account-balance)
{% endhint %}

Currently, D'CENT Wallet is running an event to support the cost of activating the XLM account that is created. Please refer to the section below "**Receive Stellar coin**".

## Stellar Memo

The Stellar wallet used by an exchange service uses a single address. In other words, all users of the exchange have the same address. To distinguish each user's account, the exchange service manages the user accounts by assigning a unique identification character (Memo) to each user.&#x20;

**Therefore, when sending XLM to a recipient wallet address created from the Exchange, you MUST enter the Memo so that the Exchange will complete the deposit to the recipient's wallet account**.

## Receive Stellar coin

From your XLM account, click "Receive" to view your account address.

![](../../.gitbook/assets/stellar-receive\_en.jpg)

If your XLM account is inactive, please activate your account by clicking on the (**Event**) link.

## Sending Stellar coin

If you are sending Stellar coins to your exchange account, you **MUST** enter the Memo.&#x20;

If you are sending Stellar coins to a personal wallet such as D'CENT Wallet, entering Memo is optional. You can enter any notes in the Memo field or choose to change the Memo options.

![](../../.gitbook/assets/stellar-send-option\_en.jpg)

When sending money, check the address and memo once again before making the final confirmation.

![](../../.gitbook/assets/stellar-send-confirm\_en.jpg)
