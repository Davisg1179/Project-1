# Project-1
Disney Company Analysis

API Keys that will be needed in order to run the code:
Financial Modeling Prep: https://financialmodelingprep.com/developer
Alpha Advantage: https://www.alphavantage.co/


Questions to be answered:
Does the current stock price of Disney represent an under-valuation or over-valuation of the company? 
Do the financial metrics (PE ratio, price to sales , price to book, net profit margin current ratio, debt to equity, debt to assests, gross profit,  and ROE) support the current or projected stock price of Disney?
What does the valuation of the company look like doing a 5 year discounted cash flow (DCF) model of the company look like considering pessimistic, neutral, and optimistic scenarios? 
Does the Monte Carlo simulation of the 5 year outlook for the stock price support the conclusions gained from the DCF model? 
 
 Current Ratio- Liquidity ratio that measures whether a firm has enough resources to meet its short-term obligations between 1.5 & 3%. The likely hood a company will pay the investor back.


Debt to Assets Ratio - It can be interpreted as the proportion of a company’s assets that are financed by debt. Anything higher than 1 shows that a most of the assets that are financed by debt.


Debt to Equity Ratio- Indicates the relative proportion of shareholders’ equity and debt used to finance a company’s assets. The average is about 1.5%.

Gross Profit Margin Ratio- Shows the percentage of sales revenue a company keeps after it covers all direct costs associated with running the business. A higher gross profit margin, means the company has more cash to pay for indirect and other costs such as interest and one-time expenses. 65% is healthy. For every dollar generated means that is the percentage retained while the rest is used for cost.

Return On Equity Ratio - the rate of return that the owners of common stock of a company receive on their shareholdings. Return on equity signifies how good the company is in generating returns on the investment it received from its shareholders. 15-20% is considered good.

Price To Sales Ratio – Compares the company’s stock price to revenue. A ratio less than 1.0 means it is a better investment.

Price To Earnings Ratio - Valuing a company that measures its current share price relative to its per-share earnings. High P/E ratio means a company is overvalued. Average is 12-15.

Price To Book Ratio- Any value under 1.0 is considered a good P/B value, indicating a potentially undervalued stock. Average is under 3.0.

Net Profit Margin Ratio - How much net income is generated as a percentage of revenues received. Net profit margin helps investors assess if a company's management is generating enough profit from its sales and overhead costs are being contained. 10% is average

Monte Carlo Simulation - Performs risk analysis by building models of possible results by substituting a range of values—a probability distribution—for any factor that has inherent uncertainty. It then calculates results over and over, each time using a different set of random values from the probability functions.

We looked at the Bollinger Bands for the last five years of the Disney stock performance. Bollinger Bands are a type of price envelopes define upper and lower price range levels. Bollinger Bands are envelopes plotted at a standard deviation level above and below a simple moving average of the price. Because the distance of the bands is based on standard deviation, they adjust to volatility swings in the underlying price.​  For this project, we looked at Bolliger bands with an upper and lower limit based on two times plus and minuse the rolling 30-day standard deviation. Some analysts say that when the closing stock price approaches the uppper limit, it's good time to sell, however it the stock closing price approaches the lower limit, it's a good time to sell.  However, as a lagging indicator it's not necessarily something to follow.

We also performed two additional valuation methods, a discounted cash flow (DCF) and an enterprise value divided by EBITDA (earnings before interest, taxes, depreciation & amoritization) valuation.  The DCF valuation is used to estimate the value of an investment based on its expected future cash flows. DCF analysis attempts to figure out the value of an investment today, based on projections of how much money it will generate in the future.  In order to complete it, the three major financial statesments have to be forecasted (income statement, balance sheet, and statement of cash flows). In our analysis, we decided to do the DCF starting at 2019 instead of 2020, because Disney had a negative income in 2020 due to COVID.  We did however, calculate the stock price using 2020 as year one and found that the stock price based on the DCF should be $-0.65, so we abandoned those number and made year one 2019. Several assumptions need to be made during a DCF analysis including the year over year growth, the discount rate, and the time period we are looking at. Our assumptions for the growth are –2% growth for pessimistic outlook and 5% growth for optimistic outlook.​ We used the weighted average cost of capital (wacc) as the discount rate (see commented code), and assumed a five year outlook (until 2024).  The free cash flow results from the "pessimistic" and "optimistic" growth rates were then used to calculate the range of stock prices. EV/EBITDA calculations were not shown in code because they fall out of the DCF model and somewhat escape the scope of the project.  If required, the calculations can be shown.

We have shown the "Football" chart that displays the range of stock prices based on the DCF model, EV/EBITDA calculation, the Monte Carlo simulation and the min and max stock price for the last five years.  The black line in the center of the graph represents the current stock price as of last week.


Conclusion- Based on the analysis of the financial ratios and the various valuation methods, we think the current stock price of Disney is neither under- or over-valued.  Market and economic conditions will change going forward, but at this time we think it's a sound investment for the long-term.

Future improvements and/or additions:
-make the code dynamic for inputting various growth rates.
-add code for calculation of EV/EBITDA.
-do an additional comparables analysis of competitors to add to the final outcome.

