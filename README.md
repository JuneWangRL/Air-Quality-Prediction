数据:北京市 35 个站点 2017 年全年空气质量检测数据
模型方法:利用空间插分及 Arima 时间序列模型填补缺失值，从大气数据，气候状况，时间差分及统计信息等 多个角度构建特征。结合 Arima 及树模型(Lightgbm)预测未来 48 小时的空气质量状况，smape 最终达到 0.37.
