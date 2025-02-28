# How to use TRON account (TRX, TRC10, TRC20, TRC721)

## How to create a Tron (TRX) account

If you don't have a Tron account, create a new account. The coin symbol name for Tron is "TRX".

For more details on how to create an account, click the link below.

{% content-ref url="../../mobile-app/create-account/" %}
[create-account](../../mobile-app/create-account/)
{% endcontent-ref %}

When you have added a new Tron account in the D'CENT Wallet, this account do not exist on the Tron blockchain just yet. To use Tron account, you must first pay the account generation fee of 1 TRX as required by [TRON policy](https://developers.tron.network/docs/account#account-activation). Additionally, the Tron account **needs to be activated** before any information can be found via API queries or on blockchain explorer.

### Tron account creation

To make your Tron account exist (account creation) on the blockchain, simply send more than 1 TRX to your Tron address in the wallet.

<mark style="color:red;">**Tron account creation fee = 1 TRX**</mark>&#x20;

### Tron account activation

To keep your Tron account in the activated state, your Tron account must maintain more than 0.1 TRX in the balance. If the balance in the Tron account falls below 0.1 TRX, the account will become deactivated and will no longer read account information from the Tron blockchain.&#x20;

<mark style="color:red;">**Tron account activation fee = 0.1 TRX**</mark>&#x20;

<figure><img src="../../.gitbook/assets/45.png" alt=""><figcaption></figcaption></figure>

## Frequently asked question

**My USDT token (TRC20) in the Tron account does not show up, what do I do?**\
\
Remember, if the balance of TRX in your Tron account falls below 0.1 TRX, it will become deactivated. Having at least 0.1 TRX will keep your Tron account (including TRC10 and TRC20) in the activated state and will show the account information for Tron (TRX) and token accounts (TRC10 and TRC20).
