# 🔐 SecurePay – Browser Extension for Seamless Blockchain Connectivity

Modern blockchain applications demand reliable, secure, and seamless wallet integration. Yet, developers face challenges like inconsistent APIs, complex authentication flows, and multi-network compatibility issues. **SecurePay** solves this with a developer-first browser extension that makes it easy to connect with React apps and blockchain networks.

## 🚀 Problem Statement – *Pedals Up Challenge*

> "Enable seamless wallet connectivity for React-based blockchain applications with support for multiple networks, secure key management, and standardized APIs."

## 🧩 Key Features

- ✅ Standardized Interface — Easily integrates with any React application.  
- ✅ Multi-Blockchain Support — Built with Ethereum and Solana support.  
- ✅ Secure Transaction Signing — Manages private keys securely and signs transactions effortlessly.  
- ✅ Minimal Configuration — Simple API and installation for developers.  
- ✅ Clean UI/UX — Lightweight, intuitive user interface.  
- ✅ Cross-Browser Compatible — Works with Chrome and Chromium-based browsers.

## 📦 Tech Stack

- React (Vite + JSX)  
- Chrome Extension APIs  
- Blockchain Libraries:  
  - ethers.js  
  - solana/web3.js

## 🛠️ Installation & Setup Instructions

### 🔁 Clone the Repository

```bash
git clone https://github.com/anshul755/MyWallet.git
cd MyWallet
```

### 📦 Install Dependencies

```bash
npm install
```

### 🏗️ Build the Extension

```bash
npm run build
```

> This will generate a `dist` folder containing the production-ready files.

## 🧩 Load the Extension into Chrome

1. Open **Google Chrome**.  
2. Go to `chrome://extensions/`.  
3. Enable **Developer mode** (toggle in the top right).  
4. Click **“Load unpacked”**.  
5. Select the `dist` folder inside the project directory.  
6. You’ll now see the **SecurePay** extension in your browser.

## 🧪 Demo Application

A demo React app is included to show how easily developers can connect to the wallet, initiate transactions, and switch networks using the provided APIs.

## 🔐 Security Considerations

- Uses secure browser storage for key management.  
- Enforces strong transaction signing workflows.  
- Isolated background script architecture prevents front-end data leaks.

## 🌱 Future Enhancements

- Add support for additional blockchain networks (e.g., Polygon, BSC).  
- Implement biometric authentication (WebAuthn).  
- UI/UX improvements with theme customization.  
- Real-time gas fee estimation.  
- Notifications and balance syncing.  
- **Database Integration**: Replace local storage with NoSQL database for enhanced scalability, performance, and data management.

## 👨‍💻 Team: Divine Dhyana

- Anshul Patel  
- Chaitya Shah  
- Het Shah  
- Ruksh Dakhara