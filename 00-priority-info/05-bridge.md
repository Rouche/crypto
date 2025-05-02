# 🧱 What is Bridging?
Bridging is the process of moving tokens from one blockchain network to another — like from Ethereum (Layer 1) to Arbitrum (Layer 2).

* It does not swap tokens (USDC stays USDC)

* It changes the chain it's on

* Purpose: to use faster & cheaper chains like Arbitrum, Optimism, etc.

### 🧾 Why It Saves on Fees (Even if ATM uses ERC-20)
You’re right:
#### ➡️ If an ATM sends USDC using Ethereum (ERC-20), that initial send uses L1 gas — no way around that.

BUT… once you bridge it to Arbitrum, you benefit going forward:

#### ✨ Here's How Bridging Saves Fees:

Action|Ethereum (L1)|Arbitrum (L2)
:---|:---|:---
Swap USDC → WBTC|~$15–40 gas|~$0.15–0.50 gas
Interact with dApps|High gas|Low gas
Claim rewards/yield|High gas|Low gas
Approve contracts|$10+ each|~$0.05
So if you do anything besides holding — you’re saving $$ long-term by moving to L2.

### 🔁 Example Flow (Bridge)
Let’s say you received 100 USDC on Ethereum (L1) in Ctrl Wallet via ATM.

#### Step-by-step:
1. Go to: https://www.orbiter.finance

2. Connect Ctrl Wallet

3. Select:

    * From: Ethereum

    * To: Arbitrum

    * Token: USDC

4. Bridge 100 USDC

5. Confirm → You'll pay one last high gas fee (maybe ~$15)

6. Done! Now your 100 USDC is on Arbitrum — forever cheap

>You now spend < $1 on every future swap, interaction, or dApp move

### 🧠 Key Tradeoff:
* Pay once high gas to escape Ethereum

* Save on every future move (Arbitrum gas is super cheap)

### TL;DR
✔️ Ctrl can receive USDC via Ethereum
✔️ Bridging is optional, but very worth it if you want to:
→ Swap USDC → WBTC
→ Use DeFi
→ Send tokens often
→ Interact with L2 apps

# 🧭 Guide: Bridge from Polygon to Arbitrum One
## ✅ Prerequisites
* ✅ Wallet: Rabby Wallet or MetaMask, connected to both Polygon and Arbitrum One

* ✅ Assets: Have ETH, USDC, or tokens on Polygon

* ✅ Small amount of MATIC for gas on Polygon

### 🔁 Step 1: Choose a Trusted Bridge
Here are 3 safe bridges that support Polygon → Arbitrum:


Bridge|Link|Notes
:---|:---|:---
Rango Exchange|https://app.rango.exchange|Aggregates multiple bridges (easy and flexible)
Jumper Exchange|https://jumper.exchange|Powered by Socket, safe and fast
Orbiter Finance|https://www.orbiter.finance|Low fees, simple UI (ETH only)
>🔐 Always verify links from trusted sources before connecting your wallet.

### 🔁 Step 2: Bridge Your Assets
1. Go to the bridge website (e.g., Rango or Jumper)

2. Connect your wallet.

3. Select:

    * From: Polygon

    * To: Arbitrum One

    * Asset: ETH or USDC (recommended)

4. Enter the amount you want to send.

5. Review the bridge fee and estimated time.

6. Click Swap / Bridge, confirm in your wallet.

>⏱️ Most transfers take 2–10 minutes depending on bridge.

### ✅ Step 3: Confirm Arrival on Arbitrum
* Switch your wallet to Arbitrum One.

* Check balances directly in Rabby or on https://arbiscan.io using your wallet address.

### 💡 Optional: Add Arbitrum to Your Wallet
If not already added:
```
Network Name: Arbitrum One  
RPC URL: https://arb1.arbitrum.io/rpc  
Chain ID: 42161  
Currency Symbol: ETH  
Block Explorer: https://arbiscan.io
```

### 🛑 Safety Tips
* Never bridge large amounts all at once — test with a small amount first.

* Use only official or audited bridges — beware of phishing links.

* For large transfers, consider bridging to ETH mainnet first, then to Arbitrum (more secure but higher fees).