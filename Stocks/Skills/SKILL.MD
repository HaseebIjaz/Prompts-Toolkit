Use the skill-creator skill to help me build a skill.

The skill prepares an Equity Research Report for any Publicly Traded Company listed on PSX.
Whenever I ask for an "Equity Research Report" or "Research Report" or "Company Research Report" or "Stock Research Report" or "Fundamental Analysis Report", it should:

- Ask explicitly if the user wants to conduct Fundamental Analysis on a PSX listed Company and wants a report for the same purpose.
- If User Says "No", no need to use this skill them.
- If User Says "Yes", ask user to enter the Company Name and Symbol as is listed on PSX.
- Check if the compay exists or not. If there is any descripency with name or symbol confirm with user. Confirm with the user anyway before moving further. This is Checkpoint 1.
- Once it is finalized that the company exists on PSX.
- I am specifying the default Research Plan below, Ask the user if the user wants to make any changes in the Research Plan. :

```
1. Find historical information about [Specified Company] ([Specifed Ticker Symbol]), including its founding, business model, major revenue streams, and key products or services. Also, identify its geographic markets and the percentage of revenue contribution from different segments.

2. Obtain the annual reports, financial statements, and other official filings for [Specifed Ticker Symbol] from the Pakistan Stock Exchange (PSX) for the past five fiscal years.

3. Research the current state and future outlook of the relevant industry in Pakistan, including market growth trends, key drivers, competitive dynamics, and relevant regulatory factors.

4. Identify the main competitors of The [Specifed Company] and find available data on their market share and overall competitive landscape.

5. Analyze the macroeconomic environment of Pakistan, specifically researching recent trends in GDP growth, inflation, interest rates, and currency exchange rates (PKR) and how these factors could impact a company in the export sector.

6. Gather data required for a Discounted Cash Flow (DCF) analysis and comparable company valuation, including analyst projections for future cash flows, growth rates, and relevant valuation multiples for peer companies.

7. Find any available analyst consensus target prices and ratings for [Specifed Ticker Symbol] from reputable financial data providers or brokerage firms to provide a reference point for valuation analysis.

8. Synthesize all the gathered information to formulate a comprehensive SWOT analysis for [Specifed Ticker Symbol], assess its competitive positioning, and identify key financial and operational risks facing the company.

```

- Execute the set of instruction that I am dictating below:

```
You are a CFA charterholder with 20+ years of equity research experience at top global investment banks such as Goldman Sachs and Morgan Stanley. Prepare a comprehensive equity research report on [Specified Company] listed on PSX , Ticker symbol [Specifed Ticker Symbol] as of today. The report must include:

1. Executive Summary 3–5 bullet points summarizing the investment thesis Recommendation: Buy / Hold / Sell with short reasoning.

 2. Company Overview History, business model, major revenue streams Geographic footprint and main markets Key products/services and % revenue contribution Top competitors and market share estimates

3. Historical Financial Analysis (Last 5 Years) Revenue, net income, EPS growth trends Valuation ratios: P/E, P/B, EV/EBITDA, P/S, Dividend Yield Profitability ratios: ROE, ROA, gross margin, operating margin, net margin Liquidity ratios: Current ratio, quick ratio Leverage ratios: Debt-to-Equity, interest coverage Include a table for all ratios

4. Industry & Macro Environment Industry growth trends and competitive landscape Regulatory environment and macroeconomic factors (GDP, interest rates, inflation, FX) affecting performance

5. Competitive Positioning SWOT analysis (Strengths, Weaknesses, Opportunities, Threats) Competitive moat analysis (cost advantage, brand, patents, network effects, switching costs)
6. Risks Financial risks (debt load, cash flow issues) Industry risks (competition, technological disruption) Macro risks (commodity prices, interest rates, FX volatility)

7. Valuation & Target Price Perform DCF valuation with clear assumptions Comparable company multiples analysis Bull case, base case, bear case scenarios with respective price targets

8. Final Recommendation Clear call: Buy / Hold / Sell Justification based on both quantitative and qualitative factors

9. Simple Investor Takeaways (For Layman Understanding) Present 10 easy-to-understand bullet points: 5 reasons to invest in this stock (e.g., strong brand, high dividends, growing industry, solid balance sheet, innovation pipeline) 5 reasons to be cautious if any(e.g., high debt, strong competition, regulatory risks, cyclical industry, valuation already expensive) Use simple, everyday language that a new investor can easily understand (avoid jargon).

Formatting
Requirements: Professional tone and clear section headings Tables, graphs for ratio analysis and valuation metrics. Clearly state all assumptions where actual data is unavailable Extra Instruction: Use the latest available financial statements and market data. If real-time data is unavailable, simulate using plausible, realistic numbers and flag them as estimates. and also give analyst's consensus for the stock target price if available. the report should not be more than 8 pages.

```
