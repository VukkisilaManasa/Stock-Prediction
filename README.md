
The stock market is a focus for investors to maximize their potential
profits and consequently, the interest shown from the technical
and financial sides in stock market prediction is always on the rise.

However, stock market prediction is a problem known for its challenging
nature due to its dependency on diverse factors that affect 
the market, these factors are unpredictable and cannot be taken into
consideration such as political variables, and social media effects
such as twitter on the stock market.

> To identify the values of AR and MA parameters we use ACF and PACF plots. Or by using grid search to go over all the combinations of parameters and chose the one that achieves the least loss according to a defined loss function such as Akaike Information Criterion (AIC) and Bayesian Information Criterion (BIC) as both are penalized-likelihood information criteria.
And to identify the integrated parameters, they use a statistical test called the “Augmented Dickey-Fuller test”
> - Note: Due to the headache of identifying the model and its parameters, the python community has developed an automated library called “Auto Arima” that chooses the best model suitable for your dataset and identifies the best parameters to achieve the lowest loss.

As Shown at the above figure, our project has nine stages:
- Stock Data Scraping
- Twitter Data Scraping
- Twitter Data Preprocessing and Sentiment analysis
- Modeling Using Two approaches
  - ARIMA as Baseline
  - Deep learning architecture using 1D-CNN and BiCudaLSTM layers as our new approach
- Compare and evaluate our approach vs ARIMA
- Evaluate our approach against new data in real-time


 
