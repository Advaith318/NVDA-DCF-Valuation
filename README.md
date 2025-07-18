# NVDA-DCF-Valuation
Built a conservative DCF model for NVDA using free public resources for data and Excel for modeling.

## Summary
-Obtained historical data from the SEC Edgar and Yahoo Finance (2021-2025)

-Forecasted  financials for the next 5 years (2026-2030)

-Calculated the FCF, WACC, and terminal value

-Discounted values to the present

-Estimated the implied share price ($46.97/share) compared to the market price ($173.60/share) as of 07/17/2025

-Concluded that under conservative assumptions and tapering trends, NVDA is overvalued by 27.06%

## Methodology
-Set TGR at 3% based on conservative long-term growth

-Tapered EBIT margins from 62.42% in 2025 because of unsustainability

-Increased projected tax rates from 14% to 16% as NVDA's tax credits decline

-The reduction in CapEx and D&A shows NVDA's shift from purchasing hardware and infrastructure to a chips/software focus

-Tapered the percentage of sales of NVDA's NWC to follow trends and assume they become more efficient with their capital (could have kept the constant percentage to be more conservative)

## File
- `NVDA DCF.xlsb` — The model that contains all calculations, assumptions, and final valuation

## Tools Used
- Microsoft Excel
- Yahoo Finance
- SEC EDGAR

## Notes
- Educational project for financial modeling practice
- No proprietary data used
- WACC estimated manually from industry sources
