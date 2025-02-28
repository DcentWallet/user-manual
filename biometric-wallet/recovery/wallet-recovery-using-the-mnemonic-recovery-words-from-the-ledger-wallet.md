# Wallet recovery using the mnemonic (recovery words) from the Ledger wallet

Both the Ledger wallet and the D'CENT wallet follow the same BIP standards for wallet recovery. However, each wallet service may have used a **different wallet derivation path** to generate a private key for each type of digital asset that each wallet service currently supports.

Below is a screenshot that compares the account addresses (ie: BSC & ETH) between the Ledger wallet and D'CENT wallet. In this example, D'CENT wallet was recovered using the mnemonic code from the Ledger wallet. Notice how the addresses for the BSC and ETH accounts are the same because the wallet derivation paths are the same between these 2 wallet services.

<figure><img src="../../.gitbook/assets/그림2 (1) (3).png" alt=""><figcaption></figcaption></figure>

## List of recovery-compatible assets (mainnets)

The wallet derivation paths for the following cryptocurrencies are **the same** between the Ledger wallet and the D'CENT wallet. **This means that using the Ledger's mnemonic code, the same accounts(private keys) can be generated on the D'CENT wallet.**

* Binance Smart Chain (BSC - BNB)
* Bitcoin Cash (BCH)
* Cosmos (ATOM)
* DASH (DASH)
* Dogecoin (DOGE)
* Ethereum (ETH)
* Ethereum Classic (ETC) - select '<mark style="background-color:blue;">Ethereum Classic - Legacy</mark>' when adding to D'CENT wallet.
* Horizen (ZEN)
* Polygon (MATIC)
* Solana (SOL)
* Stellar (XLM)
* XRP (XRP)
* Zcash (ZEC)
* TRON (TRX)

### How to recover token assets (ie: ERC20, BEP20, TRC10, ...Etc.)

It is likely that you also held token assets in the Ledger wallet. Token assets are digital assets issued by blockchain projects (service providers) via smart contracts that exist on EVM-compatible networks such as Ethereum, Binance Smart Chain, Tron, Polygon, and more.&#x20;

Each EVM-compatible network has a name for its token standard which is represented or marked as '**ERC20**' for tokens on the Ethereum network, '**BEP20**' for tokens on the Binance Smart Chain network, '**TRC10'** and '**TRC20'** for tokens on the Tron network, '**Polygon-ERC20'** for tokens on the Polygon network, and so on. The token standards help identify easily which network(s) the token assets were issued on.

For example, let's say you held **ETH** coins and **USDT** tokens (ERC20) in the Ledger wallet. To recover these assets, you must add two accounts to the D'CENT wallet. First, add the Ethereum account to recover ETH coins. Next, add the USDT (ERC20) account linking it to your Ethereum account and your USDT tokens will be found.

You can easily search for which digital assets are supported (listed) in the D'CENT wallet by visiting the link below.

{% embed url="https://dcentwallet.com/SupportedCoin" %}

If the token asset that you are looking for is not displayed in the list, you can also manually add the account as a custom token account. For detailed instructions, please refer to the guide below.

{% content-ref url="../../mobile-app/create-account/how-to-add-a-custom-token-account.md" %}
[how-to-add-a-custom-token-account.md](../../mobile-app/create-account/how-to-add-a-custom-token-account.md)
{% endcontent-ref %}
