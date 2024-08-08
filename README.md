#Portfolio-based on investor's risk-appetite

###This code presents the portfolio preparation and analysis for the investors' three levels of risk
###appetite: aggressive, moderate, and conservative. Each level of risk appetite requires its
###respective type of portfolio, i.e. high-risk, moderate-risk, and low-risk. Specific questions such as
###the source of income, investment objective, and others are asked to determine the investors' risk
###appetite. Accordingly, the required portfolio is prepared by narrowing down the selection of
###diversified stocks from the NIFTY Sectoral Indices based on fundamental and technical analysis.
###The risk score is calculated for each industry selected based on the financial ratios, relative
###strength index (RSI) signal, MACD signal, while also considering the mean return, and standard
###deviation of the past 5 years prices. These are used to create the user’s portfolio.

##The broad selection of investments
###The financial investments in this portfolio preparation are equities from diversified industries.
###From all the stocks in NIFTY Sectoral Indices, a random mix of stocks was prepared with
###different market capitalisations and from different sectors. A broad mix of stocks was selected
###randomly diversified with different industries and large-cap, mid-cap, and small-cap stocks.

##Risk Scores
###To make a suitable portfolio according to the different risk appetites of the investors, the stocks
###are distributed into bands according to their risks. For this, risk scores are allotted based on the
###selected financial ratios, RSI signal, MACD signal, mean return, and standard deviation for each
###stock.

##Assumptions:
###1. A predetermined set of companies is provided.
###2. Diversification of risk is done through the inclusion of various industries and sectors.
###3. Predetermined score bands will be assigned scores based on the risk compared with the
###industry average.
###4. The mean return and standard deviation of stocks are treated with the use of percentiles.
###5. Stock’s weightage in the created portfolios is based on the risk scores obtained for the
###company.
###6. In case of Technical Indicators - 
###(i) In RSI, we assumed the window size as 14, and 
###(ii) In MACD, the Fast moving average is 12, and the Slow Moving Average is 26.
###These assumptions were based on the commonly used terms as observed. For reference,
###this was confirmed with Trading View and Groww websites.
###7. The risk-free rate is assumed to be the 10-year Indian government bond yield.

##Portfolio Risk and Return
###To determine an investment’s risk-adjusted return, the Sharpe ratio and Treynor ratio of the
###portfolio are calculated. For both the ratios, the current risk-free rate (Rf) is 7.17%.
##Sharpe ratio:
###It compares the portfolio’s risk premium and returns. It includes total risk (i.e., both systematic
###and unsystematic risk).
##Treynor ratio:
###It compares the portfolio’s risk premium and return. It includes systematic risk (denoted by Beta)
###of the portfolio.
