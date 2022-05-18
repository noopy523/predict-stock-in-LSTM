"# predict-stock-in-LSTM" 
"# predict-stock-in-LSTM" 
# Predict stock in LSTM
1.LSTM由四個unit組成: Input Gate、Output Gate、Memory Cell、Forget Gate
2.資料集:台灣加權指數(TSEC)
3.訓練集: 2014~2018年（共 1231 天）測試集 : 2019~2020

# 結果
實作(滾動法+LSTM) : 將觀測資料固定10天、20天、60天進行預測，使用滾動法求得預測結果
![image](https://github.com/noopy523/predict-stock-in-LSTM/blob/main/TSMC_year.png)

# 詳細內容
https://medium.com/21-century-girl/predicting-stock-price-using-lstm-1-4265c69f6659
