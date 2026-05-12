# DN Company ERP MVP

Technology Sales • Repair • Inventory Management

## Included
- Email + Password login UI
- Role-based dashboard: Admin, Manager, Sales, Technician, Cashier
- Inventory CRUD
- Sales POS
- KRW + LKR pricing
- Korean + English UI toggle
- Low stock alerts
- Local demo mode
- Firebase-ready structure

## Default Admin
Email: admin@dncompany.kr  
Password: DN@2026Admin

## Run locally
```bash
npm install
npm run dev
```

## Firebase setup
1. Create Firebase project
2. Enable Authentication > Email/Password
3. Create Firestore Database
4. Add your Firebase config in `src/firebaseConfig.js`
5. Run:
```bash
npm run build
firebase deploy
```

Note: This package uses local demo storage by default so you can test immediately. Firebase connection placeholders are included for deployment.
