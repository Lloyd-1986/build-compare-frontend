# build-compare-frontend
front end repo fopr build compare
buildcompare-frontend/
│
├── index.html
├── package.json
├── vite.config.js
│
├── src/
│   ├── main.jsx
│   ├── App.jsx
│
│   ├── pages/
│   │   ├── Landing.jsx
│   │   ├── Login.jsx
│   │   ├── Dashboard.jsx
│   │   └── Pricing.jsx
│   │
│   ├── components/
│   │   ├── ProjectList.jsx
│   │   ├── MaterialTable.jsx
│   │   ├── PriceComparison.jsx
│   │   ├── AddMaterialModal.jsx
│   │   └── UpgradeBanner.jsx
│   │
│   ├── services/
│   │   ├── api.js            # Backend calls
│   │   └── billing.js        # Stripe checkout redirect
│   │
│   ├── styles/
│   │   └── main.css
│   │
│   └── utils/
│       └── formatCurrency.js
│
└── .env.example
