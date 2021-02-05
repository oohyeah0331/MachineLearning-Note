# 模型錯誤的種類
要評估一個模型的好壞，首先要了解如何判斷錯誤的來源為何，才能對症下藥。  

## Bias
用來說明模型的預測結果有多糟糕，也就是跟實際值之間的差距。  
簡單來說，bias很大的時候，表示我們預測的結果與實際的結果相差較遠，代表我們模型的精確度很差。  
## Variance
用來說明模型的誤差的變異程度，也就是誤差之間的差異是否很大。  
variancec很大的時候，表示每一次預測的誤差變動很大，有可能這一次完美命中，誤差為零，下一次卻錯得離譜。  

# 評估方法  
#### 分類問題可以用下列方法來評估模型好壞：  
>> Precision-Recall  
>> Accuracy  
>> LogLoss
>> ROC-AUC
>> Cohen's(Quadratic weighted) Kappa  
#### Unsupervised Models:  
>> Rand Index
>> Mutual Information  
#### Others: 
>> CV error
>> Heuristic methods to find K
>> BLEU Score(NLP)  
