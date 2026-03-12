# BorageTech

Welcome to the official repository for **BorageTech**, a collection of simple, privacy-focused software tools designed to solve everyday problems.

## 🚀 Projects Included

- **BT SplitBill**: The fairest way to split bills and manage group debts.
- **BT QR Generator**: Create beautiful, customizable QR codes instantly.
- **BorageTech Landing Page**: The main portal for all our digital tools.

## 🛠️ How to Run Locally

This project is a static website built with **HTML**, **Tailwind CSS** (via CDN), and **Alpine.js**. No complex build steps or installations are required.

### 1. Using a Local Server (Recommended)
To prevent cross-origin (CORS) issues and ensure all features work correctly, it is best to run the project using a simple local server.

#### Option A: Live Server (VS Code Extension)
If you are using VS Code:
1. Install the **Live Server** extension.
2. Right-click on `index.html`.
3. Select **Open with Live Server**.

#### Option B: Python (Simple & Fast)
If you have Python installed, run this command in the project root:
```bash
# For Python 3
python3 -m http.server 8000
```
Then visit `http://localhost:8000` in your browser.

#### Option C: Node.js (Serve)
If you have Node.js installed:
```bash
npx serve .
```

### 2. Direct Opening
You can also simply double-click `index.html` to open it in your browser, though some browser security features might limit certain functionalities.

## 📁 Project Structure

- `index.html`: Main landing page.
- `bt_splitbill.html`: Product page for BT SplitBill.
- `icons/`: Logo and graphical assets.
- `privacy_policy.html`: Legal documentation.

---
Built with ❤️ by [Vikas Borage](https://boragetech.in) in Pune, India.
