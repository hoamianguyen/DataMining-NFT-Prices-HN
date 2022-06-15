# DataMining Predicting NFTs Prices
## Project Proposal and Goal
In 2021, NFTs become a controversial topic when some of the art pieces were sold for millions and p.eople are skeptical of the tremendous valuations of NFTs over the last 2 years. 
Our goal: To help people decide if they should invest in NFTs by identifying what affects it’s pricing
## Dataset
The main dataset
* Name: Non fungible tokens transactions dataset
* Source: [Open Sea](https://osf.io/wsnzr/?view_only=319a53cf1bf542bbbe538aba37916537)
* Dataset original shape: ~6M rows and 24 columns 

The supporting dataset

* Name: ETH/USD Historical Trade Price
* Source: [Gemini](https://www.cryptodatadownload.com/data/gemini/)
* Dataset original shape: ~1.5M rows and 7 Columns  
## Model Selection
Regression: Multi-linear regression 
```
Strength: 
Simple to implement
Easy to interpret output ( coefficient, correlation)
Weakness:
Sensitive to outliers
Can perform poorly when there are a non-linear relationships
```
Time Series Analysis: Long-short term memory
```
Strength:
Help identify autocorrelation, seasonality, stationarity, patterns 
Weakness:
Poor performance with long-term forecasting, Random Walks and the Non Independence of Observations, Impact of Single Events
Models could be over-fitting, which may leads to inaccurate results
```

