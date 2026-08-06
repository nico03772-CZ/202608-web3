# Bitget邀請碼 BTC9149｜Bitget Wallet 拆解：130+ 鏈的非託管入口，不是「交易所附屬錢包」那麼簡單（手續費最高優惠 20%）

把 Bitget Wallet 看成「Bitget 交易所送的副產品」是 2023 年以前的老印象。  
2026 年的它（前身 BitKeep，2018 年起家，2023-08 更名）是獨立產品線：**9000 萬+ 用戶、130+ 公鏈、Super DEX 聚 78 協議 16 橋、MPC 無助記詞可選、GetGas 用 USDT 付油費、6500 BTC 鏈上保護基金**。  
先綁交易所碼：用 **BTC9149** 註冊 Bitget 交易所（https://partner.bitget.com/bg/8cp8dcqu ），現貨與合約手續費最高可享 20% 比例回饋；錢包本身不靠這碼運作，但同 UID 日後把鏈上幣劃回 Bitget 賣時，加密側成本直接降一截。

---

## 它跟「Bitget 交易所」是兩件貨

| 維度 | Bitget 交易所（CEX） | Bitget Wallet（自託管） |
|---|---|---|
| 私鑰歸屬 | 平台託管 | **你本機生成，伺服器不存明文** |
| 資產位置 | 平台帳本 | 各鏈上合約 |
| 登入方式 | 帳號密碼＋2FA | 助記詞 / MPC 社交登入 / 硬體錢包 |
| KYC | 必須 | 基礎錢包功能免 KYC，法幣通道依第三方要求 |
| 關係 | 鄰居 | 可內部劃轉，但崩一邊不拖另一邊 |

> 客服要你交助記詞＝釣魚；錢包丟了且無備份，Bitget 公司救不回，這點跟交易所凍結可申訴完全不同。

---

## 鏈覆蓋：130+ 條，自動辨識不手動加 RPC

實用面涵蓋：
- **EVM**：Ethereum、BSC、Polygon、Arbitrum、Optimism、Base、Avalanche C-Chain、Linea、Scroll、Blast
- **非 EVM**：Bitcoin（含 Ordinals 檢視）、Solana、Tron、Sui、Aptos、TON、Monad、Morph
- **自定義鏈/RPC**：手動加也行，但多數場景不用

連 DApp 時錢包**自動切對應鏈**，不像早期 MetaMask 要複製 RPC 填 ID。資產頁多鏈同幣（如各鏈 USDT）可折疊成一條看總覽。

---

## 交易引擎：Super DEX 不是普通 Swap 按鈕

內建 **Super DEX（聚合路由）**：
- 聚 **78 個 Swap 協議**（Uniswap / Pancake / Curve / Sushi 等）＋ **16 座跨鏈橋**
- 拆單路由：源鏈兌 → 橋 → 目標鏈兌，自動選最優價格與滑點
- **MEV 保護**：內建防三明治/前端跑單
- **GetGas**：沒有目標鏈原生幣也能付油費，用 **USDT / USDC / ETH / BGB** 扣
- 合約風險掃描：交互前彈「代幣權限/貔貅/無法賣」警示

這塊是 Bitget Wallet 跟「純儲存型錢包」的分界線——它幹了部分 DEX 聚合器的活。

---

## 帳號模型：助記詞 / MPC / 硬體 三選一

### 標準助記詞錢包
創建 → 設本機 PIN（確認交易用，忘記要重匯入） → 系統給 **12/24 字助記詞** → 紙本離線抄。  
PIN 跟助記詞是兩回事，PIN 鎖了可重匯入解，助記詞丟了沒人能幫。

### MPC 無助記詞（Keyless）
選「社交登入」用 Google/Apple 開 → 私鑰分片在 TEE/雲端託管層，不給明文助記詞，體驗接近 Web2 帳號。  
重度自託管用戶仍建議走標準助記詞，MPC 方便但信任邊界不同。

### 硬體錢包
支援 Ledger 等連接，大額冷存簽名。

---

## 鏈上衛生：授權管理是核心差

錢包內建 **Approval / 授權管理**：
- 列出每個代幣對每個合約的 approve 額度
- 一鍵撤銷惡意/棄用授權，或調回 0
- 連 DApp 前看「這合約要無限授權還是限額授權」

這功能決定你玩完土狗後資產還在不在，比「收發幣」重要十倍。

---

## 理財與延伸：不止於轉帳

- **Earn / Vault**：接 Aave V3、穩定幣金庫，USDC 在 Base 上隨存隨取（年化隨市場浮動）
- **Staking**：SOL/ETH/BGB 等鏈上質押入口
- **NFT**：多鏈展示、掛單、跨鏈轉移
- **Bitget Onchain**：App 內用現貨帳戶 USDT 直接換鏈上幣（ETH/SOL/BSC/Base/Morph/Monad），不走錢包切換；這是交易所側功能，但跟 Wallet 的 DEX 互補
- **保護基金**：6500 BTC 鏈上可查儲備，覆蓋平台起源安全事故，非鏈上合約 Rug 兜底

---

## 邀請碼在這篇的位置

錢包功能**不依賴 BTC9149**。碼綁的是你的 Bitget 交易所 UID：  
鏈上賺幣 → 劃回 Bitget 現貨賣 → 偶爾跑合約，這時 **20% 手續費優惠（BTC9149）** 落在加密側。漏填＝這 UID 永久少吃 20% 返點。

```
Bitget邀請碼：BTC9149
註冊連結：https://partner.bitget.com/bg/8cp8dcqu
```

---

## 建立與備份順序（別跳步）

1. App / Chrome 插件裝 Bitget Wallet → 【Create Wallet】
2. 選「助記詞」或「MPC 社交」→ 設本機 PIN
3. 助記詞**手抄紙本離線**，不截圖不雲端不傳通訊軟體
4. 驗證順序後進首頁 → 收 0.0001 某幣測試 → 發回去測試
5. 連一個 DApp（如 Uniswap）→ 簽名 → 回授權管理撤掉測試 approve
6. 交易所那邊順手用 https://partner.bitget.com/bg/8cp8dcqu 綁 BTC9149

---

## 風險提示

區塊鏈交易不可逆，轉錯鏈/地址可能永久損失；智能合約有漏洞與 Rug 風險，授權前必看範圍。  
MPC 依賴分片託管層，助記詞模式依賴紙本備份紀律；兩者信任邊界不同。  
支援鏈數、Super DEX 協議清單、GetGas 幣種以官網 https://web3.bitget.com 當期為準。  
本文僅教操作，不構成投資建議；**Bitget邀請碼 BTC9149** 與連結僅供參考。

---

## 總結

Bitget Wallet = **130+ 鏈非託管＋Super DEX 聚合 78 協議 16 橋＋MPC/助記詞雙模＋GetGas 代付油＋授權撤銷＋6500 BTC 保護基金**的獨立 Web3 入口，不是交易所的小配件。  
創建 → 離線抄助記詞 → 收發測試 → 連 DApp 清授權，新手閉環就跑完；交易所那側用 BTC9149 綁碼，日後鏈上幣回賣時手續費最高省 20%。
