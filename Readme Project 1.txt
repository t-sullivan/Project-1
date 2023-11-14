Readme: Project 1

Objective: Calculate and Determine if GBTC is trading at a discount or premium.

Inputs
-Price of Bitcoin
-Price of GBTC
-Bitcoin Holding
-Shares of GBTC

Outputs
-GBTC Assets/Shares = Value of asset per share
-Determine Discount or Premium vs the Funds NAV

Data selection
-In order to successfully accomplish this project, we needed to understand all of the components of Net Asset Value and how to calculate them.
-As result, we needed data which had the closing price of Bitcoin, GBTC, outstanding shares of GBTC, and the total physical holdings of Bitcoin owned by GBTC.
-We leveraged existing data from Yahoo Finance and Greyscale’s website to complete our data set of price, holdings, outstanding shares.  Once complete, we formatted the files into combined dataframes indexed around time date series.





Resources: Files include gbtc price, bitcoin price, and gbtc holding data

Results: Our results can be found in GBTC_price_vs_assets_per_share.png

Code:  Our source code can be found under: nav_trade.ipynb