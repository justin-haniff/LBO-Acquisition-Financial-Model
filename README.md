# LBO-Acquisition-Financial-Model
Excel/VBA leveraged buyout model featuring financial forecasting, debt repayment, IRR, MOIC, and sensitivity analysis.
# Leveraged Buyout (LBO) Acquisition Financial Model

**Excel | VBA | Private Equity | Financial Modeling**

## Project Overview

Developed a five-year Leveraged Buyout (LBO) financial model in Microsoft Excel to evaluate the profitability and financial risks of a hypothetical private equity acquisition.

The model analyzes acquisition financing, projected operating performance, debt repayment, and exit valuation to determine whether an investment meets a required rate of return.

The workbook incorporates Excel financial formulas, scenario analysis, sensitivity testing, and VBA automation.

## Key Financial Results

| Financial Metric | Base Case |
|---|---:|
| Acquisition Enterprise Value | $120,000,000 |
| Initial Debt Financing | $72,000,000 |
| Initial Equity Investment | $48,000,000 |
| Exit Enterprise Value | $162,725,899 |
| Exit Equity Value | $125,838,294 |
| Multiple on Invested Capital (MOIC) | 2.62x |
| Annualized Internal Rate of Return (IRR) | 21.26% |
| Target IRR | 20.00% |
| Investment Recommendation | INVEST |

*Results are based on hypothetical assumptions rather than an actual acquisition.*

## Financial Model Components

**Deal Inputs:** User-adjustable acquisition assumptions, including purchase multiple, leverage, interest rate, revenue growth, and exit valuation.

**Operating Model:** Five-year forecasts of revenue, EBITDA, operating income, taxes, and unlevered free cash flow.

**Debt Schedule:** Annual interest expense, debt repayment, and outstanding debt calculations.

**Returns Analysis:** Exit enterprise value, investor equity proceeds, MOIC, and annualized IRR.

**Sensitivity Analysis:** Two-variable Excel Data Table measuring how purchase and exit EBITDA multiples affect investment returns.

**Dashboard:** Financial summary with projected revenue growth and debt repayment visualizations.

## VBA Automation

Developed three VBA macros with individual Excel buttons:

1. **Enter Deal Assumptions:** Uses four VBA InputBoxes to modify acquisition assumptions.
2. **Downside Scenario:** Automatically applies less favorable operating growth and exit valuation assumptions.
3. **Restore Base Case:** Returns assumptions to their original values.

These macros allow users to quickly compare investment outcomes without manually adjusting multiple spreadsheet inputs.

## Scenario Analysis

| Metric | Base Case | Downside Case |
|---|---:|---:|
| Revenue Growth | 5% | 1% |
| Exit EBITDA Multiple | 8.5x | 7.0x |
| Annualized IRR | 21.26% | 7.02% |
| Investment Decision | INVEST | REJECT |

The downside scenario demonstrates how reduced operating growth and lower exit valuations can significantly decrease investor returns.

## Technical Skills Demonstrated

Microsoft Excel, VBA, financial forecasting, leveraged buyout modeling, debt scheduling, cash flow analysis, investment valuation, IRR and MOIC calculations, scenario modeling, Excel Data Tables, IF formulas, and financial data visualization.

## How to Use

Download the `.xlsm` workbook and open it in Microsoft Excel Desktop.

Review the Deal Inputs sheet to understand the acquisition assumptions. Navigate between the Operating Model, Debt Schedule, and Returns Analysis sheets to examine the financial calculations.

The Dashboard provides a summary of the investment results and includes buttons for running the VBA macros.

VBA macros require a supported desktop version of Excel. Review the macro code and enable macros only when you trust the workbook.

## Project Purpose

Created as an individual graduate-level financial modeling project to demonstrate practical skills relevant to private equity, investment analysis, corporate finance, and financial analyst positions.


## Model Screenshots

### LBO Financial Dashboard

![LBO Dashboard](screenshots/dashboard.png)

### IRR Sensitivity Analysis

![IRR Sensitivity Analysis](screenshots/sensitivity-analysis.png)
