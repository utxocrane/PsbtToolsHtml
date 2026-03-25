# 🛠️ PSBT tools for Bitcoin/Litecoin

Lightweight HTML tools for manually creating and signing Bitcoin transactions — no server, no runtime, just your browser.

tools:
- [creator.html](https://utxocrane.github.io/PsbtToolsHtml/creator.html) (Unsigned PSBT creator)
- [feeRateChart.html](https://utxocrane.github.io/PsbtToolsHtml/feeRateChart.html)Mempool feerate histogram chart)

---

## 🚀 Features

- 🔍 Fetch UTXO data from [blockstream.info](https://blockstream.info/)
- 🧱 Construct unsigned transaction hex manually
- 🔐 Sign with your cold wallet or hardware device
- 📤 Preview and broadcast via blockstream.info or any other service
- 🎯 Precisely control transaction fee to **1 sat/tx** (not 1 sat/vB like most wallets)
-    Simple RBF TX creating.
---

## 📦 How It Works

1. **Fetch TX data**  
   Query UTXOs using blockstream.info's public API.

2. **Create unsigned TX**  
   Build a raw transaction hex manually in the browser.

3. **Sign the TX**  
   Use your cold wallet or hardware wallet to sign the hex offline.

4. **Broadcast**  
   Paste the signed hex into blockstream.info or use sendrawtransaction@any core wallet.

---

## ✅ Why This Tool?

- Runs entirely in your browser, static html code
- Can download and double-click the HTML file — no install, no dependencies
- Ideal for cold wallet workflows, air-gapped setups, and fee precision control

---

## 📁 Usage

1. Clone or download this repository.
2. Open `creator.html` in Chrome.
3. Follow the instructions in the UI to build and sign your transaction.
4. Use [qrSegsHtml](https://github.com/utxocrane/qrSegsHtml)  to support long tx script.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 🤝 Contributions
If you find bugs or want to suggest improvements, feel free to open an issue.
Appreciate for your BTC donation if this tool helps: bc1qsmqv2rffqh5fkmzjn8pymrhp8f5xwwlk53zjsr
