________________________________________
Trader Behaviour vs Market Sentiment Analysis
Candidate: Harpreet Kaur
Platform: Google Colab / Github
Submission Folder: ds_HarpreetKaur/
________________________________________
1. Project Overview
This project investigates the relationship between trader behaviour and Bitcoin market sentiment (Fear vs. Greed).
It analyses how factors like profitability, risk exposure, and trading volume vary across different sentiment phases.
The key goal is to uncover hidden behavioural patterns that can guide smarter trading strategies.
________________________________________
2. Datasets Used
1.	Bitcoin Market Sentiment Dataset
	Columns: date, value, classification
	Captures daily market sentiment as Fear or Greed.
2.	Hyperliquid Trader Dataset
	Columns: Account, Coin, Execution Price, Size USD, Side, Closed PnL, etc.
	Contains detailed trading activity from multiple accounts.
Both datasets were cleaned and merged on the Date field for analysis.
3. Folder Structure
ds_Harpreetkaur/
├── notebook_1.ipynb              # Data cleaning, preprocessing
├── notebook_2.ipynb              # Analysis, visualizations, and insights
├── csv_files/
│   ├── cleaned_sentiment.csv
│   ├── cleaned_trader_data.csv
│   ├── fear_greed_index.csv
│   ├── hostorical_data.csv
├── outputs/
│  Notebook_1_outputs/
       │   ├── sentiment_distribution.png
       │   ├── sentiment_trend.png
       │   ├── trade_side_distribution.png
│  Notebook_2_outputs/
      │   ├── avgpnl_by_sentiment.png
      │   ├── volume_by_sentiment.png
      │   └── correlation_heatmap.png
├── ds_report.pdf                 # Final report with analysis and conclusions
└── README.md                     # Project summary (this file)
4. Key Insights
•	Profitability is higher during Fear phases and lower during Greed.
•	Trading Volume increases with positive sentiment, reflecting higher market confidence.
•	Trader Behavior aligns with emotion cycles — optimism drives risk-taking.
•	Correlation Analysis shows positive links between profit, trade volume, and sentiment intensity.
________________________________________
5. Tools and Libraries
•	Environment: Google Colab
•	Libraries: pandas, numpy, matplotlib, seaborn
•	Data Source: Public datasets (Bitcoin Sentiment Index & Hyperliquid Trade Data)
6. Results Summary
Sentiment Phase	Avg. Profitability	Trading Volume	Market Behavior
Fear	High	High	Aggressive / Optimistic
Greed	Low / Negative	Low	Defensive / Cautious
			
________________________________________
7. How to Reproduce
1.	Open notebooks in Google Colab.
2.	Upload the datasets in /csv_files/.
3.	Run notebook_1.ipynb → cleaning and saving CSVs.
4.	Run notebook_2.ipynb → analysis, visualizations, and merge.
5.	Review outputs in /outputs/ and final report (ds_report.pdf).
8. Author
Harpreet Kaur
Data Science Candidate
