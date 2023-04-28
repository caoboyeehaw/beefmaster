### beefmaster
This will Be a Tauri Desktop Web Application that controls automated spreads under certain tuned parameters. 
Features will include Backtesting and training models on certain tickers, then outputting fine tune parameters with highest sharpe ratios.
The ultimate goal is to juice the market with option spreads, either buy selling bullish vertical credit spreads and hedging theta, or buying bullish vertical credit spreads for flat out limited gain.

# Notes
- Some first Objectives will be getting real time data from alpaca, or other sources, and TA-lib for technical indicators.
- The front end will include typesccript scripts, and native web componenets.
- The back end will be using Tauri thats all coded in RUST.

The first iterations will only be able to trade paper money for stocks, then move on to real money, then move onto options.
The application will NEVER trade anything that has to do with margins, and if which, will be covered by opposite leg straddles, or, spreads.
The end vision is a functional web desktop application that uses brokerage apis to trade options, and ultimately, log data as well.

Tauri Documentation: https://tauri.app/v1/guides/
Rust Documentation: https://doc.rust-lang.org/std/index.html
