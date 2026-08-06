# Bybit Referral Code BTC9149｜Bybit Registration & Funding Guide: From Account Setup to UTA Margin Allocation (Up to 33% Fee Discount)

Many users treat "Registration" and "Funding" as two separate chores. On Bybit’s Unified Trading Account (UTA) architecture, however, they are part of a single chain: **Register with code → KYC unlocks fiat rails → Select the correct funding route → Funds land in the Funding Account → Transfer into UTA to serve as cross-asset collateral.** If any step is out of order, you’ll later hit "Insufficient Balance" errors or fail to understand the liquidation logic.
Lock in your code first: Register with **BTC9149** (https://partner.bybit.com/b/BTC9149) to unlock **up to 33% off trading fees**. Every entry and exit within the UTA utilizes this fee structure, compounding into significant savings over time.

---

## Account Setup: The Code is Written to Your UID Only Once

1.  Visit the referral link 👉 https://partner.bybit.com/b/BTC9149
2.  Select **Email or Mobile** (Email is most reliable for verification codes; one email per account).
3.  **Confirm the Referral Code field shows BTC9149** (Auto-filled via link; type manually if blank. **Permanent once set.**).
4.  Set a strong password (≥8 chars, mix of upper/lower, numbers, symbols).
5.  Enter the 6-digit code to activate.
6.  **Select your accurate Country/Region of Residence** (Impacts KYC flow and compliant funding channels; changing later requires reverification).

> **Compliance Note:** Bybit does not service certain excluded jurisdictions (including US IPs). Selecting the wrong nationality will grey out fiat funding options later.

---

## KYC: Two Tiers Determine Your Funding Ceiling

*   **Lv.1 (Basic):** ID document (front/back) + Facial Verification. Takes 5–60 mins. Unlocks P2P, Express Buy, and basic fiat rails. Limits approx. **$200/day, $5,000/month**.
*   **Lv.2 (Address Proof):** Add utility bill/bank statement (within last 3 months). Limits raised to **$10,000/day, $100,000/month**. Full withdrawal and SWIFT capabilities unlocked.
*   **Security:** Immediately enable Google Authenticator, set an Anti-Phishing Code, and configure a Withdrawal Whitelist.

*Without KYC, only "Crypto Deposits" are permitted. All fiat purchase channels remain locked.*

---

## Funding Routes: Four Paths (Choose by Scenario, Not Habit)

Bybit’s [Assets] → [Deposit/Buy Crypto] aggregates four distinct routes with vastly different costs:

### A. Crypto Deposit (For Existing Holders, 0 Fees on Bybit's End)
*   **Path:** [Assets] → [Deposit] → Select Coin (USDT/BTC/ETH) → Select Network.
*   **Network MUST Match Sender:**
    *   **USDT-TRC20 (Tron):** Near-zero gas. **Top choice for small amounts.**
    *   **USDT-BEP20 (BSC):** Low gas.
    *   **USDT-ERC20 (Ethereum):** On-chain fees $5–$30. Only for large sums. *Note: Bybit does not support BEP2 for certain assets.*
*   Copy the Deposit Address → Withdraw from external wallet/exchange → 1–30 mins confirmation → Funds hit **Funding Account**.
*   **Minimums:** Below threshold (e.g., 0.000006 BTC), funds are lost and unrecoverable.

### B. P2P Trading (Best for Local Currency, 0 Platform Fee)
*   **Path:** [Buy Crypto] → [P2P Trading] → Buy USDT.
*   Select Fiat (TWD/HKD/CNY/EUR...) → Filter: Completion Rate >95% / 100+ trades / Avg. Release <30 mins / Supported Payment Method.
*   Place Order → **Strictly transfer to the Merchant's account listed on the order page.** Do not write "USDT/Crypto" in the bank reference to avoid freezes.
*   Click [I Have Paid] → Merchant releases coins → USDT enters Funding Account.
*   **Cost:** 0% Bybit fee. Spread is baked into the merchant's price (typically 0.5%–2%).

### C. Express Buy / Card (Best for Urgent Small Sums)
*   **Path:** [Buy Crypto] → [Express Buy] → Bind Visa/Mastercard or Apple/Google Pay.
*   Select Fiat → Select Coin → 3D Secure Verification → Funds arrive in 5–10 mins.
*   **Cost:** 0% Bybit fee. Third-party processors charge **2%–4%**. Most expensive but instant. Some domestic banks block crypto transactions.

### D. Bank Wire / Swift (Best for Large Sums)
*   **Path:** [Buy Crypto] → [Fiat Deposit] → Select SWIFT/SEPA/FPS based on currency.
*   Copy Beneficiary/IBAN/Reference (Must include your UID or Pinyin name) → Initiate transfer via Online Banking.
*   **Remitter Name MUST match KYC name** exactly, or funds are returned.
*   Arrival: 1–6 Business Days. Ideal for sums > $10k USD to avoid 3.5% card fees.

---

## Post-Funding: Funding → UTA Transfer (The Most Missed Step)

Bybit operates on a dual-ledger system:
*   **Funding Account:** The entry/exit point for deposits/withdrawals. Funds land here first.
*   **Unified Trading Account (UTA):** Shared margin pool for Spot, Leverage, USDT Perps, USDC Perps, Inverse Contracts, and Options.

**Transfer Path:** [Assets] → [Unified Trading Account] → [Transfer] → Move USDT from Funding to UTA.
Once inside UTA:
*   USDT (and BTC/ETH) act as cross-product collateral (subject to haircut/discount rates).
*   Opening contracts does not require a separate "Futures Account"; simply select BTCUSDT Perpetual within UTA.
*   In Cross Mode, profits/losses offset across products (MMR calculated at account level); Isolated Mode contains risk per position.

> **Common Snag:** Funds sitting in the Funding Account while trying to open a contract results in an "Insufficient Balance" error. The transfer to UTA is mandatory.

---

## Verifying Rebates (Confirm BTC9149 is Active)

After registering, navigate to: [Account] → [Referral/Rebates] to ensure a referrer is linked.
Standard Contract Fees: Maker 0.01% / Taker 0.055%. Registering with **BTC9149** grants **up to 33% fee rebates** (subject to current official campaigns).

| Scenario | USDT Perpetual Taker Fee |
|---|---|
| No Referral Code | 0.055% |
| With BTC9149 (Max 33%) | ~0.0369% |

*Rebates are calculated on actual fees paid. Unrealized PnL cannot be withdrawn. If IMR hits 100%, UTA transfers out are suspended.*

---

## Common Funding Pitfalls

*   **Wrong Network:** Sending ERC20 to a TRC20 address = Permanent loss. Always test with $1 USDT first.
*   **P2P Memo:** Writing "Buy Crypto" triggers bank freezes. Leave blank or use "Goods Payment."
*   **Wire Name Mismatch:** Incorrect spelling leads to returned wires (3–6 business day delay).
*   **Missing Referral Code:** UID lock-in is permanent.
*   **Funds in Funding, not UTA:** Thinking funding is complete when it hasn't been allocated to the trading wallet.
*   **Lv.1 Limit Breach:** Attempting large deposits exceeding monthly caps without Lv.2.

---

## Risk Warning

Digital assets are volatile; leveraged products risk total capital loss. Use P2P strictly via the in-app order system; beware of phishing scams. Selecting the wrong blockchain network may result in permanent loss. Services are unavailable in restricted jurisdictions (e.g., US IPs).
KYC limits, Wire availability, and rebate tiers are subject to regulatory changes. Actual benefits are subject to the official Bybit website.
The **Bybit Referral Code BTC9149** and links are provided for reference only and do not constitute financial advice.

---

## Summary

```
Bybit Referral Code: BTC9149
Registration Link: https://partner.bybit.com/b/BTC9149
```

Register with BTC9149 → Select accurate residency → Complete Lv.1/Lv.2 KYC → Choose Funding Route (Crypto/P2P/Card/Wire) → Funds hit Funding Account → **Transfer to UTA** → Confirm Rebate Status → Switch to Isolated/3x before trading.
**Pro Tip:** First time? Buy $100 USDT via P2P → Transfer to UTA → Market buy 0.0001 BTC. Running this full loop is more valuable than reading ten guides.
