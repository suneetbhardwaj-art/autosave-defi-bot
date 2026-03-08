# AutoSave Bot – Smart DeFi Savings

## Problem
Many people forget to save money regularly. In decentralized finance (DeFi), users also struggle to build a habit of saving small amounts consistently.

## Solution
"AutoSave Bot" is a simple web app that helps users automatically save a small percentage of their income into a DeFi savings pool. 

## Features
- **AutoSave Simulator**: Input your income, savings percentage, and risk level. The app calculates your estimated monthly and yearly savings and suggests an optimal DeFi strategy based on your risk tolerance.
- **DeFi Strategies**:
  - Low Risk: Safe Pool (e.g., Aave USDC)
  - Medium Risk: Balanced Pool
  - High Risk: Growth Pool (e.g., Yield Farming)
- **Simple Dashboard**: Track and view past calculations and savings estimates with a visual progress indicator showing savings growth over the year.
- **Beginner Friendly**: Clean, well-commented code designed to help newcomers understand the intersection of basic frontend development, full-stack application structure, and DeFi concepts.

## Technologies Used
- Frontend: React, Tailwind CSS, Recharts for visualizations, wouter for routing.
- Backend: Node.js, Express, PostgreSQL with Drizzle ORM.
- Design: Modern dark fintech theme with deep blue accents.

## How to run
1. Ensure you have Node.js and PostgreSQL installed.
2. Clone the repository.
3. Install dependencies: `npm install`
4. Set up your `.env` file with `DATABASE_URL`.
5. Run the app: `npm run dev`

This project was built for a hackathon focusing on "Smart DeFi Savings".
