# stock_proving_ground
A web app that will run an arbitrary set of checks against a list of stock tickers

# TODOs

1. sign up to get Core Financial Data from: https://www.quandl.com/
2. flesh out basic app, without caching/performance concerns that:
  1. accepts a list of tickers and a list of analysis/checks
  2. downloads the necessary information about each ticker
  3. runs through the analysis/checks
  4. if a ticker RXs a 90% or better, simulate trading activity (buy, hold, sell)
  5. analyze performance of checks, and calculate ROI
  6. store trading activity into a database


# the goal here is to detect imminent movements / maximize short term gains.