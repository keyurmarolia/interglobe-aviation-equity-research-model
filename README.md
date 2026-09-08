# InterGlobe Aviation Equity Research Model

Excel-based equity research and valuation model for InterGlobe Aviation (IndiGo). The project combines reported financial statements, airline operating drivers, management outlook, industry context, operating forecasts, and valuation analysis.

## Model coverage

- Historical income statement, balance sheet, cash flow, and operating KPIs from FY2016 to FY2026
- ASK, RPK, load factor, passengers, yield, PRASK, fuel CASK, and ex-fuel CASK analysis
- Base operating forecast for FY2027–FY2031, with a separate FY2027 bear/base/bull operating comparison
- Income statement forecast, supporting fleet, lease, asset and working-capital schedules, and unlevered free cash flow
- DCF valuation, sensitivity analysis, and reverse DCF

## Approach

Reported financial data is linked to the forecast through operating and cost drivers. Management commentary is identified separately from model assumptions. Industry traffic and market-share data provide context for the reasonableness of growth assumptions; they are not direct valuation inputs.

The forecast is an operating and valuation model. Historical balance sheets and cash-flow statements are included, but the forecast does not contain a complete assets/liabilities/equity balance sheet or a financing cash-flow statement. The Balance Sheet tab contains the supporting schedules.

DCF excludes all other income from operating profit as a simplifying assumption; operating compensation within other income is not separately forecast. Lease liabilities are treated as debt. Forecast reinvestment is estimated as depreciation plus the change in net PPE and right-of-use assets, assuming no disposals, impairments or FX revaluations. Historical UFCF uses cash capex only and is not directly comparable with that forecast measure. These simplifications require judgment when interpreting the valuation.

The DCF uses a 31 March 2026 valuation basis and year-end discounting. The market comparison uses the 7 September 2026 closing price and March balance-sheet debt/cash; it is not a valuation rolled forward to September. Equity value is floored at zero when enterprise value is below net debt; the unfloored difference remains visible. Reverse DCF scales all forecast cash flows and terminal cash flow uniformly, with WACC and terminal growth held constant.

## Worksheet order

00 Cover, 01 Sources, 02 Raw Financials, 03 Raw Operating KPIs, 04 Industry Data, 05 Historical Analysis, 06 Operating Model, 07 Income Statement, 08 Balance Sheet, 09 Cash Flow, 10 Scenarios, 11 DCF, 12 Reverse DCF.

The workbook follows standard financial-modelling conventions:

- Blue font: hard-coded inputs and assumptions
- Green font: links to other worksheets
- Black font: formulas and calculated values
- Negative values: shown in brackets

## Workbook

The completed model is available at [`model/InterGlobe_Aviation_Equity_Research.xlsx`](model/InterGlobe_Aviation_Equity_Research.xlsx).

Primary sources include InterGlobe Aviation annual reports, investor presentations, earnings-call transcripts, regulatory disclosures, DGCA and Ministry of Civil Aviation publications, and Screener. Source document names are listed within the workbook.

## Disclaimer

This is an independent research project prepared for demonstration purposes and is not investment advice.
