# SpendWise 💰

Personal finance management app built with React + TypeScript + Tailwind CSS.

## Tech Stack

- **React 18** (Functional Components + Hooks)
- **TypeScript** (strict interfaces & types)
- **Tailwind CSS** (responsive utility-first styling)
- **Lucide React** (icon library)

## Project Structure

```
src/
├── types/          # TypeScript interfaces & types
│   └── index.ts
├── data/           # Mock data
│   └── mockData.ts
├── components/     # Reusable UI components
│   ├── Sidebar.tsx
│   ├── StatCard.tsx
│   ├── StatusBadge.tsx
│   ├── ProgressBar.tsx
│   ├── Toggle.tsx
│   ├── DonutChart.tsx
│   ├── ExpenseTrendChart.tsx
│   └── QuickAddModal.tsx
├── pages/          # Page-level components
│   ├── Dashboard.tsx
│   ├── Transactions.tsx
│   ├── Analytics.tsx
│   └── MobilePreview.tsx
├── App.tsx
├── index.tsx
└── index.css
```

## Pages

| Page | Description |
|------|-------------|
| **Dashboard** | Stats cards, expense trend chart, budget status, recent transactions, Quick Add modal |
| **Transactions** | Filterable, paginated ledger table with status badges |
| **Analytics** | Donut chart, category utilization bars, Smart Insights |
| **Mobile Preview** | Interactive phone frame — Budgets, Profile, Settings, Notifications |

## Getting Started

```bash
npm install
npm start
```

Open [http://localhost:3000](http://localhost:3000) to view the app.

## Build for Production

```bash
npm run build
```

## Color Palette

| Color | Hex | Usage |
|-------|-----|-------|
| Brand Green | `#10B981` | Primary brand, income, positive indicators |
| Red | `#EF4444` | Expenses, alerts, over-budget warnings |
| Blue | `#3B82F6` | Housing category, info elements |
| Amber | `#F59E0B` | Pending status, warnings |
| Purple | `#8B5CF6` | Transport category |
