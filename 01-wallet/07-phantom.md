# ➕ You Now Need: Solana Wallet

## ✅ Best Choice: Phantom Wallet
- Website: https://phantom.com/
- Platforms: Browser extension (Chrome, Brave, Firefox), iOS, Android
- Open-source, user-friendly, secure

### Alternatives:
- Solflare (https://solflare.com/)
- Backpack Wallet (https://www.backpack.app/)

🎯 Purpose: Receive bridged USDC and swap for RAY on Solana DEXs.

## 🧠 What Are the Accounts Phantom Is Showing You?
When you imported your 12-word Solana seed phrase into Phantom, it automatically derived standard Solana wallet addresses from it using a common derivation path (usually m/44'/501'/0'/0' for Solana).

Even if you never manually created accounts, the Solana CLI and Phantom both follow BIP44 rules to predictably generate wallet addresses from the seed.

These are deterministic wallets, meaning:

* From your 12 words, a series of accounts can always be generated in order.

* Phantom just shows you account #1 (and lets you create more in sequence).

### ✅ Why You Might See Existing Balances or Activity
If you're seeing balances or transactions:

* You may have already used that seed (from CLI or testing).

* Or someone else once had access to those same 12 words (unlikely if you just generated it offline).

If the accounts are empty:

* They're normal derived accounts — you’re just seeing default ones derived from your phrase.

### 🔐 Summary
* Your seed phrase = the master key.

* Wallet apps (CLI, Phantom, etc.) = tools that generate addresses/accounts from that key.

* Nothing was created on-chain until you send/receive funds.

## ✅ Verify Solana Address from Seed (Offline, CLI)
```
solana-keygen recover "prompt://?key=0/0" --outfile ~/my-solana-keypair.json
```
This does the following:

* Prompts you to enter your 12-word seed phrase.

* Uses derivation path m/44'/501'/0'/0' (this is what `"0/0"` means).

* Outputs your keypair file (my-solana-keypair.json), which includes your public address.

## 🔎 If you want to check different derivation paths:
You can change the `key=0/0` part:
```
key=0/1   # m/44'/501'/0'/1'
key=1/0   # m/44'/501'/1'/0'
```

## 🔐 View the Public Address
After recovery:
```
solana-keygen pubkey ~/my-solana-keypair.json
```

This will print the Solana address. You can now match it to what Phantom shows you.

