# Wagmi Token Analyzer – Chrome Extension

**Wagmi Token Analyzer** is a Chrome extension built to help users analyze token data and assess risks in real time. Powered by the WAGMI Court community, it provides an intuitive interface and detailed insights to protect traders from potential scams and rug pulls.

---

## 🔧 Installation (Load Unpacked from GitHub)

Follow these steps to install the extension manually from this repository:

1. **Download or clone this repository**  
   - Option 1: Click the green **`Code`** button above, then select **Download ZIP**. Extract the contents.  
   - Option 2: Run the following command in your terminal:  
     ```bash
     git clone https://github.com/your-username/wagmi-token-analyzer.git
     ```

2. **Open Google Chrome**

3. Navigate to `chrome://extensions/`

4. **Enable Developer Mode** (toggle in the top right corner)

5. Click **“Load unpacked”**

6. Select the `token_checker` folder (the one containing `manifest.json`)

7. The extension should now appear in your Chrome toolbar

---

## 🚀 How to Use

1. Click the **Token Checker** icon in your Chrome toolbar  
2. Enter a token address in the input field  
3. Click **“Check Token”**  
4. Wait for the scan to complete  
5. Review the results  
6. Click **“Back”** to analyze another token or **“Try again?”** to restart

---

## 🔍 Features

### 🧠 Token Analysis
- Token address validation
- Multi-stage analysis including:
  - Dev holdings percentage
  - Sniper bot detection
  - Top 10 holders breakdown
  - Wallet activity monitoring
  - Insider wallet detection
  - Bot user identification

### 📊 Information Display
- Contract address (CA)
- X (Twitter) profile link
- Project website
- Telegram link (if available)

### 💡 User Interface
- Clean, modern three-stage workflow:
  1. Input Page
  2. Loading Screen with status updates
  3. Detailed Results Page

---

## 📁 File Structure

token_checker/
├── manifest.json # Extension configuration
├── popup.html # Token input UI
├── popup.js # Token input logic
├── loading.html # Scanning progress UI
├── loading.js # Scanning logic
├── token_info.html # Results display UI
├── token_info.js # Results logic
├── styles.css # Shared styling
└── README.md # Project documentation

---

## ⚠️ Disclaimer

This extension is for educational and analytical purposes only.  
**Always conduct your own research (DYOR)** before making any investment decisions.

---

## 🛠️ Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss your ideas.

---

## 📬 License

[MIT](LICENSE)
