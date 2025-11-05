**Anomaly Detection on Stock Price High Volatility**

Analysis of Stock Price Fluctuation Prediction Results for PT Bank Jago Tbk (IDX: ARTO) Using Gated Recurrent Units (GRU) with the Isolation Forest (IF) Algorithm and Local Outlier Factor (LOF)

**RESULT**

<div style="text-align: justify;">
This research was conducted considering the high volatility in the stock
prices of PT Bank Jago Tbk. (IDX: ARTO), driven by strategic events
such as acquisitions, rebranding, and investments by major technology
companies, which caused price surges from IDR 2,272 to IDR 19,000
per share within a short time frame. This study aims to analyze stock
price fluctuation predictions for PT Bank Jago Tbk. (IDX: ARTO) using
a Gated Recurrent Unit (GRU) model with and without outlier detection
and handling. The data used consists of daily closing prices from
August 1, 2020, to August 1, 2024, obtained from Yahoo Finance using
the yfinance library. Outliers in the dataset were identified using
Isolation Forest (IF) and Local Outlier Factor (LOF) algorithms and
handled through a rolling average window method. The cleaned data
was processed using Min-Max Scaler before being split into training,
validation, and testing datasets. The GRU model was developed with
hyperparameters such as dropout, batch size, and units and evaluated
using the Mean Absolute Percentage Error (MAPE). The results show
that the GRU model with outlier detection achieved a MAPE of 2.67%,
outperforming the model without outlier detection, which had a MAPE
of 3.45%. This study demonstrates that considering and handling
outliers can improve the performance of stock prediction models
</div>

**RESEARCH SUBMISSION**
https://repo.itera.ac.id/depan/submission/SB2505020001
