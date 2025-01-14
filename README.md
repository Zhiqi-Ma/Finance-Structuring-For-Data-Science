# Finance-Structuring-For-Data-Science

Final Project for IEOR 4571 during Fall 2024 at Columbia University.

We developed and evaluated a long-only day trading strategy for NYSEARCA: GDX, an ETF designed to replicate the NYSE Arca Gold Miners Index (GDMNTR). The investment plan is constructed using a machine learning approach, in which the model generates buy signals based on the data and pre-defined take-profit and stop-loss conditions. To design the plan with optimal profitability, we evaluate the effectiveness of various machine learning models in generating buy signals.

● The data used for this project included daily open, close, high, and low prices of NYSEARCA: GDX.
● Three strategies are explored for generating buy signals to optimize trading decisions: 1. Take Profit Or Stop Loss Strategy; 2. Daily P&L-based Strategy; 3. If Not Stop Loss Strategy.
● Four machine learning models—Logistic Regression, KNN, Random Forest, and XGBoost—are employed and rigorously evaluated using key metrics such as AUC and total P&L.
● An ensemble method is implemented to combine outputs from individual models, leveraging their strength to further improve performance.
● The key challenges of developing the strategy are defining reliable buy signals, optimizing model-specific hyperparameters, and ensuring robust out-of-sample performance to effectively simulate real-world trading scenarios.
