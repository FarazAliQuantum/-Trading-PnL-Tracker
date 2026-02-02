🚀 Features
✅ Authentication

Login & Register pages

Context-based auth handling

Clean UI with AuthBackground, LoginForm, RegisterForm

📈 Dashboard

Daily PnL entry form (AddTradeForm)

Interactive charts:

Performance Line Chart

Win/Loss Ratio Chart

Monthly Bar Chart

Summary metrics including total PnL, average return, win rate, etc.

Sidebar + Header layout

Trade history table with sorting + pagination

🎨 Design & UI

Modern dashboard styling

Clean layout with TailwindCSS

Reusable UI elements powered by shadcn/ui

Light/Dark Theme (via ThemeContext)

Mobile responsive

🗄️ Data Handling

Mock data support

TradeContext for global trade state

Utils for formatting, calculations, and chart processing

📁 Project Structure
trading-pnl-tracker/
├── src/
│   ├── components/
│   │   ├── auth/
│   │   │   ├── AuthBackground.tsx
│   │   │   ├── LoginForm.tsx
│   │   │   └── RegisterForm.tsx
│   │   ├── charts/
│   │   │   ├── PerformanceChart.tsx
│   │   │   ├── WinLossChart.tsx
│   │   │   └── MonthlyBarChart.tsx
│   │   ├── dashboard/
│   │   │   ├── AddTradeForm.tsx
│   │   │   ├── Header.tsx
│   │   │   ├── Sidebar.tsx
│   │   │   ├── StatCard.tsx
│   │   │   ├── SummaryMetrics.tsx
│   │   │   └── TradeHistoryTable.tsx
│   │   └── ui/              # shadcn/ui components
│   ├── contexts/
│   │   ├── AuthContext.tsx
│   │   ├── ThemeContext.tsx
│   │   └── TradeContext.tsx
│   ├── data/
│   │   └── mockData.ts
│   ├── lib/
│   │   └── utils.ts
│   ├── pages/
│   │   ├── AuthPage.tsx
│   │   └── DashboardPage.tsx
│   ├── types/
│   │   └── index.ts
│   ├── App.tsx
│   ├── index.css
│   └── main.tsx
├── index.html
├── package.json
├── tailwind.config.js
├── tsconfig.json
└── vite.config.ts

🛠️ Tech Stack
Frontend

React + TypeScript

Vite

TailwindCSS

shadcn/ui

Recharts / Chart.js

State Management

Context API (Auth, Theme, Trade)

Other

LocalStorage / Mock Data

Utility functions for formatting and analytics

🧩 Getting Started
1️⃣ Install dependencies
npm install

2️⃣ Run the development server
npm run dev

3️⃣ Build for production
npm run build

4️⃣ Preview production build
npm run preview

📦 Deployment
Frontend (Recommended: Vercel)

Connect GitHub repo

Auto-build with Vite

No special config needed

Backend (Optional Future Upgrade)

Use any of these:

Render

Railway

Supabase

Firebase

📘 Future Enhancements

Real user authentication with JWT

Database integration (PostgreSQL / MongoDB)

Import/export trades as CSV

Automated analytics insights

Mobile app version using React Native

❤️ Contribution

Feel free to fork, modify, and improve.
Pull requests are welcome.
