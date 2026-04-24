# UK Salary & Budget Planner

A comprehensive, high-precision financial planning tool designed for UK taxpayers. This platform combines a detailed take-home pay calculator with a strategic childcare benefit optimizer and a full monthly budget planner.

## 🚀 Purpose

The primary goal of this platform is to empower UK professionals with a "single pane of glass" view of their finances. It specifically addresses complex UK tax scenarios, such as:

- **The Childcare Cliff**: Helping parents navigate the £100,000 Adjusted Net Income (ANI) threshold to retain Tax-Free Childcare and 30 Free Hours.
- **Strategic Pension Planning**: Modeling how Salary Sacrifice can reduce your effective tax rate and reclaim lost benefits.
- **EV Salary Sacrifice**: Calculating the true net cost of electric vehicle schemes.
- **Comprehensive Budgeting**: Bridging the gap between "Net Pay" and "Real Disposable Income" by itemizing everything from mortgage payments to vehicle maintenance.

## ✨ Key Features

- **Precision Salary Calculator**: Handles Income Tax, National Insurance, Student Loans (all plans), and various pension methods.
- **Childcare Benefit Optimizer**: Side-by-side comparison of current vs. optimized pension strategies to beat the £100k tax trap.
- **Scenario Comparison (V2)**: A powerful multi-pane dashboard to model "what-if" scenarios side-by-side. The interface is split into three columns: **Current**, **Comparison**, and **Impact Summary**.

### Modes:
- **Prior Year**: Re-calculate your current income against a previous tax year to see how you are doing now vs then.
- **Comparison Scenario**: Model a future state (e.g., job offer, pay rise, or pension change) against your current setup.

### How to use:
- **Column 1 (Current)**: By default, this is synced to your main Calculator tab. Toggle the **"Sync"** button off if you want to model a different baseline independently.
- **Column 2 (Comparison)**: Adjust any input (Salary, Tax Year, Pension, etc.) to see how it differs from your baseline.
- **Column 3 (Summary)**: A wider results panel showing your "Better/Worse Off" status, gross growth, and a granular Δ (delta) impact table.

### Key Insights:
- **Net Change Indicator**: A clear header detailing exactly how much more (or less) cash hits your pocket every month, including a specific row for bonus impact.
- **Dynamic Delta Table**: A side-by-side comparison of Tax, NI, Pension, and BIK costs. Rows like Student Loans or Bonuses automatically hide if they aren't present in either scenario.
- **ANI Tracking**: Monitor the impact on your Adjusted Net Income (ANI) to ensure you aren't accidentally hitting a childcare benefit cliff.
- **Optimized Layout**: Modern 2-pane interface with inputs on the left and real-time results on the right for maximum efficiency.
- **Dynamic Budget Planner**:
  - Itemized Housing, Utilities, and Lifestyle tracking.
  - **Transport Manager**: Dynamic vehicle tracking (up to 4 cars) with granular cost breakdown.
  - Automatic "Saved %" and "Leftover Cash" calculations.
- **Professional Export**: One-click "Export to Excel" that generates a beautifully formatted report with the same brand colors and clean design as the website.
- **Data Privacy**: 100% client-side. Your data is saved locally in your browser and never leaves your machine.
- **Modern UI**: Fully responsive design with Dark Mode support and premium aesthetics.

## 🛠️ Technology Stack

- **Core**: React (via Babel standalone for ease of deployment).
- **Styling**: Vanilla CSS with a focus on modern glassmorphism and premium design language.
- **Calculations**: Custom high-precision JS logic covering UK Tax Years 2023/24–2026/27.
- **Export**: [ExcelJS](https://github.com/exceljs/exceljs) for spreadsheet generation.
- **Persistence**: Browser LocalStorage for seamless sessions.

## 📄 License

This project is intended for personal financial planning and educational purposes.
