# Tabular-playground-series-competitions
Kaggle Machine learning competitions 
(This repository contains notebooks I used in competition)

1. **`TPS_APR`** - The dataset used for this competition is synthetic but based on a real dataset (in this case, the actual Titanic data!) 
      - `Binary classification`: Task is to predict whether or not a passenger survived the sinking of Titanic 
      - `Features`: survival, pclass, sex, Age, sibsp, parch, ticket, fare, cabin, embarked
      - `Metric` : **accuracy**
      - `Data Source` : [kaggle](https://www.kaggle.com/c/tabular-playground-series-apr-2021/data)

2.	**`TPS-MAY`** - The original dataset deals with predicting the category on an eCommerce product given various attributes about the listing. Although the features are anonymized, they have properties relating to real-world features.
      - `Multi-class classification`: 4-product categories
      - `Features`: anonymized
      - `Metric` : **log-loss**
      - `Data Source` : [kaggle](https://www.kaggle.com/c/tabular-playground-series-may-2021/data)


3.	**`TPS-JUN`** - The original dataset deals with predicting the category on an eCommerce product given various attributes about the listing. Although the features are anonymized, they have properties relating to real-world features.
      - `Multi-class classification`: 9-product categories
      - `Features`: anonymized
      - `Metric` : **log-loss**
      - `Data Source` : [kaggle](https://www.kaggle.com/c/tabular-playground-series-jun-2021/data)


4.  **`TPS-JULY`** - In this competition you are predicting the values of air pollution measurements over time, based on basic weather information (temperature and humidity) and the input values of 5 sensors.
      - `Time series analysis` : multi regression problem (3 target variables)
      - `Target`: target_carbon_monoxide, target_benzene, and target_nitrogen_oxides
      - `Features` : Various sensor data
      - `Metric` : **RMSLE**
      - `Data Source` : [kaggle](https://www.kaggle.com/c/tabular-playground-series-jul-2021/data)


5.	**`TPS-AUG`** - The original dataset deals with calculating the loss associated with a loan defaults
      - `Features` : Anonymized(102)
      - `Target` :  **loss**- associated with a loan defaults
      - `Metric` :  **RMSE**
      - `Data Source` : [kaggle](https://www.kaggle.com/c/tabular-playground-series-aug-2021/data)


6.	**`TPS-SEP`** - The original dataset deals with predicting whether a claim will be made on an insurance policy
      - `Features`: anonymized(120)
      - `Target` : **Claim**
      - `Metric` : **Roc-auc**
      - `Data Source` : [kaggle](https://www.kaggle.com/c/tabular-playground-series-sep-2021/data)


7.	**`TPS-OCT`** - The original dataset deals with predicting the biological response of molecules given various chemical properties.
      - `Features` : anonymized(287)
      - `Binary target`: based on biological response of molecules. 
      - `Metric` : **Roc-auc**
      - `Data Source` : [kaggle](https://www.kaggle.com/c/tabular-playground-series-oct-2021/data)
