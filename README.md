# IAA
Interactive Asset Allocation - yfinance

## What does this program do?

IAA is a optimizer tool -- its true meaning is (I)nteractive (A)sset (A)llocator. The intention is to aid the user in portfolio development with assets of their own choice. 

IAA reads from the standard input: it takes in the number of assets to be invested, followed by the previous day's date & a list of tickers the user wishes to purchase. For example, today is May 25th, 2024, so a valid input example would be:

5 2024-05-24 AAPL AMZN MSFT GOGL META

or: 8 2024-05-24 WMT NFLX IBM W SBUX BKC KRW SHOP

The IAA only accepts valid tickers and stocks denominated in CAD/USD. It will reject anything that does not follow this. Its ultimate goal is to return a distribution of asset allocation that optimizes for the greatest possible return. 

Keep in mind that it will not necessarily produce a portfolio that is highly profitable. 

Instead, it provides the user with the MOST profitable portfolio distribution given assets THEY choose.
