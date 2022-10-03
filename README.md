# 碩士論文-應用機器學習模型於食物設計之色彩辨識預測消費者偏好實務研究
# A Practical Study on Predicting Consumer Preference in Color Recognition Using Machine Learning Models in Food Design-Taking Google Map Evaluation as an Example</br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;食物設計是自1997年開始自設計界萌芽的新興領域，米蘭工業設計學院(Scuola Politecnica di Design)在2015年正式推出食物設計碩士學位(Master in Food Design)。人類知覺體驗的相關探討涵蓋了視、嗅、聽、觸、味等知覺的體驗，長期以來一直受到各領域專家學者所關注，這當中又以視覺的色彩體驗引發最多的研究與探索。
本研究使用網路爬蟲技術爬取Google Map上之台中美食圖片進行圖片色彩分析，並透過機器學習之K-means集群分析演算法來辨識每張圖片前三大比例之RGB色彩，透過RGB色彩來歸類劃分出10大HSV之色彩，並使用機器學習之邏輯斯迴歸(Logistic regression)、XGBoost、隨機森林(Random forest)、決策樹(Decision tree)、Lightgbm，來預測店家之Google Map上的評價為幾顆星，在測試資料集之準確分別為：邏輯迴歸：70.6%、決策樹：59.0%、隨機森林：69.6%、XGBoost：70.1%、LightGBM：70.1%，準確度最高之模型為邏輯迴歸，其準確度為70.6%，次高之模型為LightGBM與XGBoost，其準確度為70.1%。
