# NVDA-DCF-Valuation
Built a conservative DCF model for NVDA using free public resources for data and Excel for modeling.

## Initial Assumptions
-NVDA has outperformed the S&P 500 for the past 5 years, indicating that it has grown exponentially compared to industry standards due to the growth in GPU sales, its infrastructure, and demand for AI.
-However, this growth raises concerns for how much further NVDA can grow, as its margins are not typically sustainable in the long term, and brings attention to whether its growth will plateau in the near future
-Nevertheless, with the advancement of artificial intelligence and machine learning throughout businesses and society, NVDA's forefront position in the sector means its AI services, infrastructure, GPU's, and technology are still in heavy demand, which leads me to predict that they are still undervalued and will continue to grow

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

## Conclusion
-My initial assumption regarding NVDA was off, as I failed to see just how hard it would be to maintain their current margins concerning the market and industry
-I found that NVDA was overvalued by around 27.06%, not undervalued as initially hypothesized, which aligned with my initial concerns with their rapid growth in the last half decade
-However, this DCF model was conducted with a relatively conservative ideology, which could have potentially overstated how difficult it would be to maintain their growth and margins
-Nevertheless, this project allowed me to explore more into NVDA and its position in the market as a whole, teaching me how to understand the financial data of a company and how to project its worth and forward growth

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
