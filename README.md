![gif](https://gifdb.com/images/high/homer-simpson-thinking-crypto-smoking-7p7heynntbo4zahz.webp)

# Crypto Portfolio Tracker

## Overview
Crypto Portfolio Tracker is a web application that allows users to track their cryptocurrency investments. It provides real-time price updates, calculates total portfolio value, and displays detailed asset information.

## Features
- Display of total portfolio value
- Real-time cryptocurrency price updates
- Asset management (adding and tracking assets)
- Visual representation of portfolio data
- Hotkey navigation (press `/` to open search)

## Technologies Used
- **Frontend:** React, Ant Design
- **State Management:** React Context API
- **Backend Data Simulation:** Local API calls (mock data instead of real API requests)

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/tteemma/cryptoWalletApp.git
   cd cryptoWalletApp
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the development server:
   ```sh
   npm run dev
   ```

## Project Structure
```
/src
├── components
│   ├── layout
│   │   ├── AppHeader.jsx
│   │   ├── AppSider.jsx
│   │   ├── AppContent.jsx
│   │   └── AppLayout.jsx
│   ├── canvas
│   │   ├── PortfolioCanvas.jsx
│   │   └── AssetsTable.jsx
│   ├── coinInfoModal
│   │   └── CoinInfoModal.jsx
│   ├── coinInfoDrawer
│   │   └── CoinInfoDrawer.jsx
│   ├── data
│   │   ├── api.js
│   │   └── data.js
├── context
│   ├── CryptoContext.jsx
├── utils
│   └── utils.js
├── App.jsx
├── index.js
└── styles.css
```

## Usage
- **View Portfolio:** The total portfolio value is displayed at the top.
- **Search Cryptocurrencies:** Press `/` to open the search dropdown.
- **Add New Assets:** Click "Add Crypto" to open the drawer and add new assets.
- **View Asset Details:** Click on an asset to open a modal with more details.

## Future Improvements
- Integration with a real API for live cryptocurrency prices
- User authentication for personalized portfolio tracking
- Additional visualization tools for better analysis

![gif](https://static.news.bitcoin.com/wp-content/uploads/2019/01/UEEFPpIt-ezgif-2-c649e6fcd746.gif)
