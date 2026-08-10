# MSX Referral Code jUTs61｜MSX Onboarding: Wallet-Native RWA Registration, From Signed Login to M-Credit Binding

Most CEX registration guides start with "Click Sign Up → Enter Email → SMS Verification → KYC." Applying that template to **MSX (MyStonks)** is completely wrong. MSX is a **decentralized RWA trading platform** (upgraded to the msx.com domain in September 2025). Your account isn't a "phone number"; it is your **wallet address**. Onboarding isn't "filling out a form"; it is **signing a message**. If you miss this distinction, you will lose track of which chain your assets are on, which address your referral code is bound to, and whether switching networks creates a new account.
**The only entry point (mandatory for first-time signature to ensure referral binding):**
**https://msx.com/register?code=jUTs61**
Binding referral code **jUTs61** grants access to current new-user benefits (M-Credit incentives, S-Season point multipliers, mutual referral surprises, etc., subject to the official campaign page).

---

## Why MSX "Registration" Requires a Dedicated Guide

Traditional Exchange: Person → Account → Bind Wallet.
MSX: Wallet Address = Account Identity. The person is merely the signing authority.

*   **Supported Networks:** **Solana / BNB Chain / Ethereum / Base**. Compatible with MetaMask, Phantom, OKX Wallet, Bitget Wallet, etc.
*   **One Address = One Account:** Switching networks with the same seed phrase creates a **new MSX account**. The referral relationship binds to the **first address that connects**, not the seed phrase.
*   **Optional Email:** You can trade without an email, but binding one post-login enables email security alerts (protection against malicious signature requests).
*   **Unified Interface:** Trade tokenized equities (AAPL.M/MSFT.M/NVDA.M/TSLA.M), ETFs (SPY.M/QQQ.M), Pre-IPO tokens (SpaceX/ByteDance), Spot Crypto, and up to 20x Perpetuals—all within the same wallet interface.

> Your first decision isn't "what to fill in," but "which wallet on which chain connects to MSX first." This determines asset custody and referral attribution forever. While the official domain is msx.com, **accessing the naked domain = no referral relationship**. Never sign in from a raw domain link.

---

## Step 0: Entry Point & Phishing Verification (Critical)

*   **The Only Entry Link:** https://msx.com/register?code=jUTs61
*   *Note: The official domain is msx.com (upgraded from MyStonks in 09/2025). This is for context only; do not click raw domains.*
*   **Signature Check:** When the wallet pop-up appears, verify the requesting origin is `msx.com`. Reject requests from `msx-com.xyz`, `msx-usdt.xyz`, or similar spoofs.
*   **No Third-Party APKs:** Download the App only via the official App Store/Google Play links found on the registration page. Do not scan QR codes from Telegram groups or Twitter DMs.

---

## Step 1: Network Selection & Wallet Connection (Account Genesis)

1.  Open **https://msx.com/register?code=jUTs61**.
2.  Click **[Connect Wallet]** (top right) → Select Solana / BNB Chain / Ethereum / Base.
3.  Choose your wallet (Phantom for Solana; MetaMask for EVM chains; OKX Wallet for multi-chain).
4.  **Sign to Login:** This is **not a transaction**. It is an **EIP-4361 (EVM) or Solana Sign-In** message. It consumes no gas beyond the network fee. (If the address has zero balance, the wallet will prompt you to fund it first).
5.  Upon successful signature, MSX provisions the account. The URL parameter `?code=jUTs61` writes the referral relationship to this specific address.
6.  The address abbreviation (e.g., `0xAbC…12` or `5xY…pQ`) appears top-left. Onboarding is complete.

> **Warning:** If you connect without a code first, then paste a code later, the referral **will not retroactively bind**. The first signature with the code is final.

---

## Step 2: Email Binding & Security Layer (Recommended)

*   **Path:** [Wallet Menu] → [Security Center] → [Bind Email].
*   **Purpose:** Enables email confirmation for withdrawals, network switching, and permission changes. Provides anomaly alerts.
*   **Recommended Order:** Connect Wallet → Bind Email → Backup Seed Phrase Offline → Fund Account.
*   **Never** paste your seed phrase into any "Account Recovery" field on the MSX website (the platform never asks for this).

---

## Step 3: Verify Referral Binding

MSX tracks referrals by "First Connection." To verify:
*   Web UI: Bottom Right → [Referral Program] → [My Referrer]. If it displays **jUTs61**, binding is successful.
*   If empty or showing a different code: The first signature occurred without `?code=jUTs61`. That address is permanently unaffiliated. Switching networks creates a new address which *can* be bound, but assets do not migrate.
*   **Mutual Benefits:** Referees receive new-user M-Credit/Season perks. Referrers earn L1 (10%) and L2 (5%) point rebates based on referee activity (subject to the official "Invitation Plan").

---

## Step 4: First Deposit & RWA Trade Loop (Verify Account Activity)

MSX does not support fiat on-ramps; stablecoins are the native currency.

1.  Transfer **USDT / USDC** from an external wallet to your **logged-in MSX address**. **Crucial:** Ensure the token standard matches the network you used to log in (BEP-20 for BNB Chain, SPL for Solana, ERC-20 for Ethereum, Native for Base). Sending to the wrong chain may result in permanent loss.
2.  Navigate to [Trade] → [RWA Spot] → Search for `AAPL.M`, `NVDA.M`, or `TSLA.M` (200+ RWA assets available).
3.  Select the `/USDT` pair → Place a **Limit Buy** for a small amount (e.g., 10 USDT).
4.  Upon execution, tokens arrive in your wallet (1:1 backed by institutional custodians like Fidelity, verified via Merkle Tree Proof of Reserves and Chainlink Oracles).
5.  Switch to [Perp] to open a AAPLB position (up to 20x leverage) to verify derivatives access.
6.  Switch to [Pre-IPO] to view SpaceX/ByteDance subscription portals (Partnered with Republic; Min. entry ~$10 equivalent).

Completing this loop confirms the account is "Live," not just connected.

---

## Step 5: M-Credit & Season Incentives (The Value of the Code)

The value of **jUTs61** lies in the incentive layer:

*   **M-Credit (M):** Earned via trading/holding. Tied to future MSX ecosystem token allocations.
*   **Season Multipliers:** Referral relationships influence S-Season (starting S1) point weightings (Team Boosts ranging 1.05×–1.5×).
*   **New User Tasks:** Completing first RWA trade, first perpetual trade, or email binding often triggers bonus M-Credit packages (subject to the official "New User Benefits" page).
*   **Utility:** M-Credit is non-withdrawable but can be used for ecosystem perks, IDO/Pre-IPO subscription weight, and specific fee offsets within the platform ecosystem.

> The code's value is ensuring your incentive footprint enters the correct referral tree from Day 1.

---

## Multi-Chain Account Pitfalls

| Action | Result |
|---|---|
| Same seed phrase, Phantom: Solana → EVM → Connect MSX | Two independent MSX accounts. jUTs61 binds only to the first. |
| Same wallet extension, different browser | Same address, same account. Normal. |
| MSX App on mobile connecting to same wallet | Same address, synchronized. |
| Receiving random tokens into MSX address | Potential phishing. Verify contract sources before approving. |
| Funding BNB Chain USDT but buying Solana AAPLB | Chain mismatch. Fails. Switch networks first. |
| Signing in from naked `msx.com` | No referral attribution. jUTs61 does not retroactively bind. |

---

## Risk Warning

Tokenized RWA prices track underlying assets but may deviate due to liquidity, oracle latency, or custody disclosures. Perpetual trading with up to 20x leverage carries a high risk of total capital loss. Pre-IPO shares feature lock-up periods and transfer restrictions. You are solely responsible for your private keys; lost seed phrases are unrecoverable. MSX holds a FinCEN MSB registration and STO filing but may restrict access based on IP/KYC (e.g., US retail users).
Asset availability, incentive rules, and M-Credit mechanics are subject to change per the official msx.com website. The **MSX Referral Code jUTs61** and links are for onboarding reference only and do not constitute financial advice.

---

## Summary

MSX Onboarding = **Select Network → Enter via https://msx.com/register?code=jUTs61 → Sign Message → Bind Email → Fund Matching Chain → Execute AAPL.M Test Trade → Verify Perp/Pre-IPO Access.**
Your account is your wallet address. Referral attribution binds to the first-signing address; switching chains creates a new account.
Bind **jUTs61** to access current new-user benefits. No fee discounts are implied or discussed; focus remains on ecosystem incentives.

---

```
MSX Referral Code: jUTs61
Registration Link: https://msx.com/register?code=jUTs61
