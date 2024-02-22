# Trade-Ahead
Unsupervised Learning - Clustering methods

### Context

The stock market has consistently proven to be a good place to invest in and save for the future. There are a lot of compelling reasons to invest in stocks. It can help in fighting inflation, create wealth, and also provides some tax benefits. Good steady returns on investments over a long period of time can also grow a lot more than seems possible. Also, thanks to the power of compound interest, the earlier one starts investing, the larger the corpus one can have for retirement. Overall, investing in stocks can help meet life's financial aspirations.

It is important to maintain a diversified portfolio when investing in stocks in order to maximise earnings under any market condition. Having a diversified portfolio tends to yield higher returns and face lower risk by tempering potential losses when the market is down. It is often easy to get lost in a sea of financial metrics to analyze while determining the worth of a stock, and doing the same for a multitude of stocks to identify the right picks for an individual can be a tedious task. By doing a cluster analysis, one can identify stocks that exhibit similar characteristics and ones which exhibit minimum correlation. This will help investors better analyze stocks across different market segments and help protect against risks that could make the portfolio vulnerable to losses.


### Objective

Trade&Ahead is a financial consultancy firm who provide their customers with personalized investment strategies. They have hired you as a Data Scientist and provided you with data comprising stock price and some financial indicators for a few companies listed under the New York Stock Exchange. They have assigned you the tasks of analyzing the data, grouping the stocks based on the attributes provided, and sharing insights about the characteristics of each group.

### Data Dictionary

- Ticker Symbol: An abbreviation used to uniquely identify publicly traded shares of a particular stock on a particular stock market
- Company: Name of the company
- GICS Sector: The specific economic sector assigned to a company by the Global Industry Classification Standard (GICS) that best defines its business operations
- GICS Sub Industry: The specific sub-industry group assigned to a company by the Global Industry Classification Standard (GICS) that best defines its business operations
- Current Price: Current stock price in dollars
- Price Change: Percentage change in the stock price in 13 weeks
- Volatility: Standard deviation of the stock price over the past 13 weeks
- ROE: A measure of financial performance calculated by dividing net income by shareholders' equity (shareholders' equity is equal to a company's assets minus its debt)
- Cash Ratio: The ratio of a  company's total reserves of cash and cash equivalents to its total current liabilities
- Net Cash Flow: The difference between a company's cash inflows and outflows (in dollars)
- Net Income: Revenues minus expenses, interest, and taxes (in dollars)
- Earnings Per Share: Company's net profit divided by the number of common shares it has outstanding (in dollars)
- Estimated Shares Outstanding: Company's stock currently held by all its shareholders
- P/E Ratio: Ratio of the company's current stock price to the earnings per share
- P/B Ratio: Ratio of the company's stock price per share by its book value per share (book value of a company is the net difference between that company's total assets and total liabilities)

## Actionable Insights and Recommendations

### Actionable Insights:

 1. **Sector-Based Investment Strategy:**
   - Leverage the identified clusters to tailor sector-based investment strategies. For instance:
     - **Cluster 0 (Consumer Discretionary, Industrials, Financials):**
       - Consider diversified investments across these sectors.
     - **Cluster 1 (Healthcare and Consumer Discretionary):**
       - Explore opportunities in Healthcare and Consumer Discretionary markets.
     - **Cluster 2 (Financials, Industrials, Information Technology):**
       - Focus on sectors showing strengths in Financials, Industrials, and Information Technology.
     - **Cluster 3 (Energy):**
       - Evaluate energy sector investments carefully, given its distinct characteristics.

2. **Risk Mitigation:**
   - Diversify across clusters to mitigate risks. Each cluster represents a different risk profile, and diversification can help balance the portfolio.

3. **Stock Selection within Clusters:**
   - Within each cluster, further analyze individual stocks to identify potential opportunities and risks. Pay attention to metrics like Price Change, Volatility, and Earnings Per Share.

 4. **Market Segment Analysis:**
   - Utilize clusters for market segment analysis, helping to identify stocks with similar characteristics and minimal correlation. This can aid in protecting the portfolio against risks.

 5. **Comparison of Clustering Techniques:**
   - Since both k-means and hierarchical clustering provided similar results, consider the interpretability and ease of use for each method. Select the one that aligns better with your analysis goals.

### Recommendations:

 1. **Diversification Strategy:**
   - Implement a diversified investment strategy that considers exposure across different sectors and clusters. This will help spread risk and capture opportunities in multiple market segments.

 2. **Regular Portfolio Review:**
   - Conduct regular portfolio reviews based on the evolving market conditions. Reassess the clusters and make adjustments as needed to align with market trends.

 3. **Continuous Monitoring:**
   - Keep a watchful eye on individual stocks within each cluster. Monitor key financial metrics and market trends to make informed decisions.

 4. **Consider Both Clustering Techniques:**
   - Given the similarity in results, periodically consider applying both k-means and hierarchical clustering techniques to validate and cross-reference findings.

 5. **Adapt to Changing Market Dynamics:**
   - Stay adaptable to changing market dynamics. Regularly reassess and adjust your investment strategy based on emerging trends and economic conditions.

 6. **Explore Other Data Sources:**
   - Consider incorporating additional relevant data sources to enhance the clustering analysis. This could provide a more comprehensive view of market dynamics.

