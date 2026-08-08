# Bitget Referral Code BTC9149｜Bitget Copy Trading Walkthrough: From Funding the Sub-Account to High-Water Mark Profit Sharing (Up to 20% Fee Discount)

Copy trading is often misrepresented as "pick the top trader and relax." However, Bitget’s system doesn't merely forward signals—it spins up an **isolated Copy Trading Sub-Account** under your UID. Every entry and exit the lead trader makes is replayed within this sub-pool based on your parameters. If the lead trader uses Cross Margin to average down while you follow with a Fixed Amount in Isolated Margin, they might recover while you get liquidated. Thus, copy trading is essentially "semi-automated replay + your own welded risk controls," not delegating your capital blindly.
Lock in your code first: Register with **BTC9149** (https://partner.bitget.com/bg/8cp8dcqu) to unlock **up to 20% off trading fees**. Since every mirrored entry and exit incurs standard contract fees, these rebates compound significantly over time.

---

## The Accounting Reality: Funds Flow to the "Copy Account," Not the Main Wallet

Bitget's Futures Copy Trading follows a three-stage funding path:

1.  USDT resides in your Spot/Funding Wallet.
2.  Transfer funds into the **dedicated Copy Trading Sub-Account**, isolated from your Main Account.
3.  Within this sub-account, select a trader, configure parameters, and the system replays their actions.

*   **Minimum Transfer:** **50 USDT** (Lead traders may set higher thresholds, e.g., $500 or $5,000. You must meet this to follow).
*   **Balance Rules:** You can add funds or make partial withdrawals during copying, but the **total asset value in the sub-account must not fall below your initial investment**, or copying halts.
*   **Post-Stop:** Once you stop copying, remaining assets automatically return to your Spot/Funding Wallet.
*   **Privacy:** Lead traders cannot see your balance or touch your Main Account.

> **Common Snag:** Users often have USDT in their Spot Wallet thinking they can copy, only to see "Insufficient Balance" errors because funds weren't transferred to the Copy Sub-Account.

---

## Step 1: Accessing the Hub & Vetting (Focus on Copier PnL)

**App Path:** [Trade] → [Futures] → Tab [Copy Trading] → Enter "Futures Copy Center".
**Web Path:** Directly visit `bitget.com/copy-trading`.

Ignore the flashiest ROI. Vet traders using this specific set:

*   **Copier PnL (Followers' Profit):** This is paramount. If the trader's ROI is high but Copier PnL is negative, they are likely using dangerous averaging-down tactics to protect their own curve while followers get liquidated during volatility. **Skip these.**
*   **Max Drawdown:** Stick to **≤ 20%**. Immediately skip anyone with > 50% drawdown.
*   **Trading Days:** **≥ 90 days.** Performance under 30 days is statistical noise.
*   **Win Rate:** **40%–65%** is the healthy range. A 95%+ win rate is a red flag—usually indicating a "never close losers" (martingale) strategy that eventually crashes.
*   **AUM & Followers:** Look for stability in follower count and Assets Under Management (AUM), rather than just one-off massive gains.
*   **Equity Curve:** Click into the profile. Look for "stair-stepping" growth with minor dips. Avoid profiles showing a vertical line up followed by a sudden 50% crash.

---

## Step 2: Selecting the Copy Mode (Three Distinct Logics)

Bitget supports three modes. Do not confuse them:

| Mode | Logic | Best For |
|---|---|---|
| **Fixed Amount** | Each trade uses a fixed X USDT margin, regardless of the lead trader's position size. | **Beginners** wanting to cap absolute loss per trade. |
| **Smart Ratio** | Scales your position based on `(Your Net Equity / Trader's Net Equity)`. If they risk 10%, you risk 10%. | Users wanting proportional exposure without manual tuning. |
| **Multiplier** | Opens positions at a multiple of the trader's size (e.g., 1x = Mirror). | Users with capital similar to the trader; wants identical exposure. |

> **The Fixed Amount Trap:** If a trader uses Cross Margin to average down, but you follow with Fixed Amount in Isolated Margin, they might recover while you get liquidated. Bitget's official docs suggest **1x Multiplier** for synchronization, but beginners afraid of liquidation should stick to **Fixed Amount + Isolated + Low Leverage**.

---

## Step 3: Welding Down Risk Controls (Advanced Settings)

Click [Copy] → [Advanced Settings]. Do not leave these blank:

*   **Margin Mode:** Select **Isolated**. If one trade goes bad, only that specific margin is lost; it doesn't cascade to the rest of the sub-account.
*   **Leverage:** Select **Fixed Leverage (1x–3x)**. **Never** select "Follow Trader's Leverage" (if they open 50x, you open 50x—instant liquidation risk).
*   **Single Trade Stop-Loss:** Set at **20%–30%**. If the trader refuses to cut losses, you exit first.
*   **Single Trade Take-Profit:** Optional (10%–20%) to secure gains.
*   **Global Stop-Loss (Equity Guardian):** Set "Stop copying when net loss reaches X USDT or Net Value drops below Y USDT." Example: If copying with 200 USDT, stop if loss hits 40 USDT.
*   **Max Copy Amount / Pairs:** Set per-pair limits (e.g., max 30 USDT margin for BTC). **Deselect Altcoins**; stick to BTC/ETH/SOL.
*   **Max Slippage:** Default 0.5%. In extreme volatility, tighten to 0.3% to avoid unfavorable fills.
*   **Copy New Positions Only:** **Enable this.** Do not copy the trader's historical open positions (you'd be buying into their existing profit, effectively buying the top).
*   **Auto-Copy New Pairs:** **Disable this.** Manually control which pairs are traded.

---

## Step 4: Funding & Confirmation

*   **Copy Equity:** Input the USDT amount to transfer into the Copy Sub-Account (≥50). For your first attempt, allocate only **10%–20% of your total Futures balance** (e.g., if you have 500 USDT total, start with 50–100 USDT).
*   **Copy All Current Positions:** **Leave UNCHECKED** (to comply with "New Positions Only").
*   **Profit Sharing:** Lead traders typically take a **10%–20% High-Water Mark** cut of net profits. They do not take a cut of losses, and past settled profits are not clawed back.
*   Click **[Confirm Copy]** → System transfers USDT from Spot/Funding to Copy Sub-Account → Automation begins on the lead trader's next open position.

---

## Monitoring: Mid-Trade Operations

Navigate to [My Copy Trading] → Select the Trader:
*   **Monitor:** Check entry price, mark price, unrealized PnL, and distance to stop-loss for every mirrored position.
*   **Manual Close:** Unhappy with a specific trade? Close it manually without affecting other copied positions.
*   **Modify:** Add funds, adjust SL %, add/remove pairs, or change slippage—all without stopping the copy process.
*   **Stop Copying (3 Options):**
    1.  Stop copying but leave positions open (wait for trader to close).
    2.  Stop copying and Market Close all positions immediately.
    3.  Stop copying and keep positions open (manage them manually).
*   **Weekly Review:** If a trader's drawdown exceeds your tolerance for two consecutive weeks, switch traders. Don't get emotionally attached.

---

## The Role of the Referral Code in Copy Trading

There is no extra "copying fee," but every mirrored trade incurs standard Futures Taker fees (0.06%).
Registering with **BTC9149** reduces this Taker fee by up to 20% (to ~0.048%). While seemingly small (approx. $2.40 rebate on $20k monthly volume), these savings compound over months of automated trading.

```
Bitget Referral Code: BTC9149
Registration Link: https://partner.bitget.com/bg/8cp8dcqu
```

---

## The Four "Nevers" for Beginners

1.  **Never** follow a trader with high ROI but negative **Copier PnL**.
2.  **Never** enable "Follow Trader's Leverage."
3.  **Never** go "All-In" on one trader (diversify across 2–3 traders with different styles, allocating 10–20% each).
4.  **Never** disable the Equity Guardian (Traders can afford to hold bags; your Isolated Margin cannot).

---

## Risk Warning

Past performance does not guarantee future results. You will incur losses if the lead trader loses. Extreme volatility can still lead to Isolated Margin liquidation. Profit sharing applies only to net realized profits. Copying halts if sub-account assets fall below the initial investment threshold.
Profit-sharing mechanics, minimum copy amounts, and pair availability are subject to change per Bitget's official updates. CFD Copy Trading and rToken Copy Trading are separate modules.
The **Bitget Referral Code BTC9149** and links are provided for reference only and do not constitute financial advice.

