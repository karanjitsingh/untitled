# TrendML
Exploring various machine learning techniques that could potentially be used for algorithmic trading and analysis tools for price trend prediction that can provide essential market signals to traders. The project explores techniques such as Decision Trees, SVM, Reinforcement Learning to predict price trends of an asset.

-----------------------------

### Introduction/Background: 

Cryptocurrency is drawing more and more attention from investors as more people are interested in decentralized finance. Predicting the trend of assets plays an important role in traders’ decision to buy or sell. There have been many studies on using machine learning techniques to predict the prices of Bitcoin. For example, Mallqui & Fernandes found the Support Vector Machines (SVM) algorithm performed best in forecasting the Bitcoin exchange rates, while the combination of Recurrent Neural Networks and a Tree classifier performed best in predicting the Bitcoin price direction (2019). Another study also found that SVM algorithm is a reliable forecasting model for cryptocurrency (Hitam& Ismail, 2018). 

### Problem definition: 

There are several limitations in current literature. Firstly, most of them only predict price of assets, without any indication for traders whether to buy, sell or hold their investments. Also, cryptocurrency short-term predictability is difficult, thus day trading cryptocurrencies might be challenging (Liew, Li, Budavári, & Sharma, 2019). Hence, it can be argues that predicting trend is a better measure than predicting price.  

Secondly, no studies have employed technical indicators commonly used by stock traders in their cryptocurrency price prediction model. As Mallqui & Fernades (2019) pointed out, the technical indicators such as Relative Strength Index (RSI), Moving Average Convergence/Divergence (MACD), etc. could be used in addition to economic indicators to better predict Bitcoin price direction. Therefore, there is a potential for a model that incorporates the indicators and predicts trend to help traders decide when to sell, hold, or buy cryptocurrencies at a given moment. 

### Methods: 

Our data will is obtained from Binance using its API.   

Relevant methods include: 

- Unsupervised: A study used PCA technique to uncover the uncommon drivers of price 	  (Liew, Li, Budavári, & Sharma, 2019). 

- Reinforcement learning: A study used a combination of double Q-network unsupervised 	pre-training using Deep Boltzmann Machine (DBM) to generate and enhance the 		       optimal Q-function in cryptocurrency trading and achieved 599% more profit in       simulation compared to conventional model (Bu & Cho,2018).  

- Supervised: A study found that SVM performed best and gave consistent results in terms 	of predictive accuracy compared to the logistic regression, artificial neural networks and 	random forest classification algorithms (Akyildirim, Goncu & Sensoy, 2020) 

### Discussion: 

Such models could potentially be practical and useful for traders, especially amateur traders to easily decide whether to buy, hold or sell their cryptocurrencies.

Based on previous studies, This project explores dimensionality reduction technique, Q-learning and decision tree (reinforcement learning), and SVM algorithms for modeling. LSTMs in conjunction with reinforcement learning have also been proven to be useful in long-term prediction. 

______

#### References 

[Akyildirim, E., Goncu, A., & Sensoy, A. (2020). Prediction of cryptocurrency returns using machine learning. Annals of Operations Research, 297(1-2), 3-36. doi:10.1007/s10479-020-03575-y](https://www.researchgate.net/publication/340500312_Prediction_of_cryptocurrency_returns_using_machine_learning)

[Bu, S., & Cho, S. (2018). Learning optimal q-function using deep boltzmann machine for reliable trading of cryptocurrency. Intelligent Data Engineering and Automated Learning – IDEAL 2018, 468-480. doi:10.1007/978-3-030-03493-1_49](https://ouci.dntb.gov.ua/en/works/7P22RGxl/)

[Hitam, N. A., & Ismail, A. R. (2018). Comparative performance of machine learning algorithms for cryptocurrency forecasting. Indonesian Journal of Electrical Engineering and Computer Science, 11(3), 1121. doi:10.11591/ijeecs.v11.i3.pp1121-1128](https://www.researchgate.net/publication/326837070_Comparative_Performance_of_Machine_Learning_Algorithms_for_Cryptocurrency_Forecasting)

[Mallqui, D. C., & Fernandes, R. A. (2019). Predicting the DIRECTION, maximum, minimum and closing prices of daily Bitcoin exchange rate using machine learning techniques. Applied Soft Computing, 75, 596-606. doi:10.1016/j.asoc.2018.11.038](https://www.sciencedirect.com/science/article/pii/S1568494618306707)

[Liew, J., Li, R., Budavári, T., & Sharma, A. (2019). Cryptocurrency investing examined. The Journal of the British Blockchain Association, 2(2), 1-12. doi:10.31585/jbba-2-2-(2)2019](https://www.researchgate.net/publication/337011389_Cryptocurrency_Investing_Examined)

 
