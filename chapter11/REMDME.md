#此代码是《Python数据分析与挖掘实战》的实战部分的第11章的完整代码

《应用系统负载分析与磁盘容量预测》

在原书中给出的内容中我另外补充的代码如下：
1)数据探索时【】画C盘/D盘已使用空间的时序图
2)模型构建【】
构建基于ARIMA或者ARMA的模型，采用AIC/BIC/HQ信息准则对模型进行定阶，确定p,q参数，从而选择最优模型；
根据自相关和偏相关图判定平稳性，确定了所用模型是采用ARMA或者ARIMA，而不是AR或者MA；